# SC Kill Tracker LITE - Privacy Policy

**Effective Date:** January 15, 2025  
**Version:** 0.1.6.2

## 1. Introduction

Harley's Studio ("we", "us", "our") operates SC Kill Tracker LITE ("the Software"). This Privacy Policy explains how we collect, use, store, and protect your information when you use our Software.

**BY USING SC KILL TRACKER LITE, YOU CONSENT TO THE DATA PRACTICES DESCRIBED IN THIS POLICY.**

## 2. Information We Collect

### 2.1 Required Information (Cannot Opt Out)

**Account & Authentication Data:**
- License Key (provided at registration)
- Username (chosen during registration)
- SCKillTrac ID (auto-generated unique identifier)
- Hardware ID (HWID) - unique device identifier
- UUID - additional device identifier
- Registration timestamp
- Last login timestamp

**Technical & System Data:**
- Operating system version and architecture
- Software version and build number
- Application installation path
- Python runtime version
- Display resolution and DPI scaling
- Processor information
- Available memory (RAM)
- IP address (for API requests)
- Overlay theme preferences (day/night mode)
- Interaction mode settings (locked/unlocked default)

**Game Data:**
- Star Citizen log file location
- Game channel (LIVE, PTU, EPTU)
- Game version
- Kill/death events (parsed from logs)
- Actor names (player and NPC names from combat events)
- Kill statistics and counters
- Session timestamps

**Crash & Error Data:**
- Exception logs and stack traces
- Error messages and codes
- System state at time of crash
- Recently executed commands
- Application logs (last 500 lines)

### 2.2 Optional Information (Can Opt Out)

**Discord Integration (if enabled):**
- Discord username and discriminator
- Discord Rich Presence status
- Server join/leave events

**Analytics (when implemented):**
- Feature usage frequency
- Settings preferences
- Session duration
- UI interaction patterns

### 2.3 Information We DO NOT Collect

We do NOT collect:
- Passwords or credentials for other services
- Financial or payment information (handled by payment processors)
- Private messages or communications
- Star Citizen account credentials
- Personal identification documents
- Location data (except IP-derived country)
- Biometric data
- Third-party application data

## 3. How We Use Your Information

### 3.1 Required Uses

**Authentication & Access Control:**
- Validate your license key on startup
- Prevent unauthorized access and license sharing
- Enforce bans and restrictions (HWID, user, key bans)
- Track license activation and usage

**Core Functionality:**
- Parse and display kill/death statistics
- Classify NPCs vs. players using AI models
- Synchronize NPC database from GitHub
- Display overlay with real-time game data
- Store user preferences and settings

**Software Improvement:**
- Debug crashes and errors
- Identify and fix bugs
- Optimize performance
- Develop new features
- Improve NPC classification accuracy

**Security & Compliance:**
- Detect and prevent abuse or cheating
- Enforce Terms of Service
- Prevent license fraud and piracy
- Monitor for malicious activity

### 3.2 Optional Uses

**Community Features (if enabled):**
- Discord Rich Presence integration
- Share statistics (when sharing features added)

**Analytics (when implemented):**
- Understand feature usage patterns
- Prioritize development efforts
- Improve user experience

## 4. Data Storage and Security

### 4.1 Local Storage

**Data stored on your device:**
- User credentials (encrypted using Windows DPAPI)
- Application settings (encrypted)
- NPC cache (encrypted with HMAC verification)
- Log files (plaintext, in AppData)
- Crash reports (plaintext, in AppData)

**Local storage location:**
```
%LocalAppData%\Harley's Studio\Star Citizen Kill Tracker LITE\
```

### 4.2 Remote Storage

**Data transmitted to our servers:**
- License validation requests (HTTPS encrypted)
- NPC detection reports (HTTPS encrypted)
- Crash reports (HTTPS encrypted)
- Analytics events (HTTPS encrypted, when implemented)

**Server locations:**
- `api.sckilltracker.com` (primary API)
- `raw.githubusercontent.com` (NPC database)

**Data retention:**
- License validation logs: 90 days
- Crash reports: 30 days
- NPC detection reports: Indefinitely (for database improvement)
- User account data: Duration of active license + 1 year

### 4.3 Security Measures

**We implement industry-standard security:**
- HTTPS/TLS encryption for all network transmissions
- Windows DPAPI encryption for local credentials
- HMAC signature verification for cache files
- Rate limiting to prevent abuse
- Input validation and sanitization
- Regular security audits

**However, no system is 100% secure. We cannot guarantee absolute security.**

## 5. Data Sharing and Disclosure

### 5.1 Third-Party Sharing

**WE DO NOT SELL YOUR DATA.**

**We share data ONLY with:**

**GitHub (NPC Database):**
- Actor names detected in-game
- NPC classification scores
- Automated pull requests (if enabled)
- Purpose: Improve community NPC database

**Discord (Optional, if enabled):**
- Rich Presence status
- Game activity
- Purpose: Social features

**Payment Processors (for purchases):**
- Transaction data (handled directly by processor)
- We do NOT see or store payment details

### 5.2 Legal Disclosure

We may disclose information if required by:
- Valid legal process (subpoena, court order)
- Law enforcement requests (with proper authorization)
- Protection of our rights or property
- Emergency situations (imminent harm)

**We will notify you of legal requests unless prohibited by law.**

## 6. Your Rights and Choices

### 6.1 Access and Correction

You have the right to:
- Request a copy of your data
- Correct inaccurate information
- Update your username or preferences
- View your license status and activation history

**To request data:** Contact support with your SCKillTrac ID

### 6.2 Data Deletion

You have the right to:
- Delete your local data (uninstall + delete AppData folder)
- Request server-side data deletion (may impact license)

**Note:** Some data cannot be deleted:
- License transaction records (required for accounting)
- Ban records (required for enforcement)
- NPC database contributions (public database)

### 6.3 Opt-Out Options

**You CAN opt out of:**
- Discord Rich Presence (disable in settings)
- Optional analytics (when implemented)
- Automatic updates (not recommended)

**You CANNOT opt out of:**
- License validation (required for access)
- NPC database synchronization (core functionality)
- Crash reporting (essential for debugging)
- Critical security measures

## 7. Children's Privacy

SC Kill Tracker LITE is intended for users 13 years and older. We do not knowingly collect data from children under 13.

Star Citizen is rated PEGI 16 / ESRB T (Teen). If you are under the required age, do not use this Software.

## 8. International Data Transfers

Your data may be transferred to and stored on servers in different countries. By using the Software, you consent to international data transfers.

We comply with applicable data protection laws (GDPR, CCPA, etc.) where applicable.

## 9. Data Breach Notification

In the event of a data breach affecting your information:
- We will notify affected users within 72 hours
- We will describe the breach and impacted data
- We will provide steps to protect yourself
- We will report to authorities as required by law

## 10. Changes to Privacy Policy

We may update this Privacy Policy to reflect:
- Changes in data practices
- New features or functionality
- Legal or regulatory requirements
- User feedback

**Notification of changes:**
- In-app notification on next launch
- Email notification (if provided)
- Discord announcement
- Updated "Last Modified" date

**Continued use after changes constitutes acceptance.**

## 11. California Privacy Rights (CCPA)

If you are a California resident, you have additional rights:

- **Right to Know:** What data we collect and how it's used
- **Right to Delete:** Request deletion of your data (with exceptions)
- **Right to Opt-Out:** Opt out of data sales (we don't sell data)
- **Right to Non-Discrimination:** No discrimination for exercising rights

**To exercise CCPA rights:** Contact sckilltracker@gmail.com

## 12. European Privacy Rights (GDPR)

If you are in the EU/EEA, you have additional rights:

- **Right to Access:** Request copy of your data
- **Right to Rectification:** Correct inaccurate data
- **Right to Erasure:** Request deletion ("right to be forgotten")
- **Right to Restriction:** Limit processing of your data
- **Right to Data Portability:** Receive data in portable format
- **Right to Object:** Object to certain processing
- **Right to Withdraw Consent:** Withdraw consent at any time

**To exercise GDPR rights:** Contact sckilltracker@gmail.com

## 13. Contact Information

**Privacy Inquiries:**
- Email: sckilltracker@gmail.com
- Discord: https://discord.gg/jxfHnGQqj7
- Website: https://sckilltracker.com

**Support:**
- Email: sckilltracker@gmail.com
- Discord: https://discord.gg/jxfHnGQqj7

**Response time:** We aim to respond to privacy requests within 30 days.

## 14. Cookies and Tracking

**SC Kill Tracker LITE does not use cookies or web tracking** (it's a desktop application, not a website).

Our website (sckilltracker.com) may use cookies - see website privacy policy for details.

## 15. Acceptance

By using SC Kill Tracker LITE, you acknowledge that you have read, understood, and agree to this Privacy Policy.

---

**Last Updated:** January 15, 2025  
**Version:** 0.1.6.2

**For questions or concerns about privacy, please contact: sckilltracker@gmail.com**

