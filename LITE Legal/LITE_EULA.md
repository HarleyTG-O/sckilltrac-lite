# SC Kill Tracker LITE - End User License Agreement (EULA)

**Effective Date:** January 15, 2025  
**Version:** 0.1.6.2

## IMPORTANT - READ CAREFULLY

This End User License Agreement ("EULA") is a legal agreement between you (either an individual or a single entity) and Harley's Studio for the SC Kill Tracker LITE software product, which includes computer software and may include associated media, printed materials, and online or electronic documentation ("Software").

**BY INSTALLING, COPYING, OR OTHERWISE USING THE SOFTWARE, YOU AGREE TO BE BOUND BY THE TERMS OF THIS EULA. IF YOU DO NOT AGREE TO THE TERMS OF THIS EULA, DO NOT INSTALL OR USE THE SOFTWARE.**

---

## 1. GRANT OF LICENSE

Subject to the terms and conditions of this EULA, Harley's Studio grants you a limited, non-exclusive, non-transferable, revocable license to:

**Install and use** one copy of the Software on a single computer for personal, non-commercial use, subject to:

- Valid license key activation
- Compliance with all EULA terms
- Acceptance of Terms of Service and Privacy Policy
- Continuous network connectivity for validation

**This license is NOT transferable** - You may not:
- Sell, rent, lease, or lend the license
- Transfer the license to another person
- Share your license key with others
- Use one license on multiple devices simultaneously

---

## 2. EARLY ACCESS STATEMENT

**SC Kill Tracker LITE IS EARLY ACCESS SOFTWARE - USE AT YOUR OWN RISK**

You acknowledge and agree that:

### 2.1 Development Status
- The Software is in active development (alpha/beta phase)
- Features are incomplete, experimental, and subject to change
- Functionality may be added, modified, or removed without notice
- User interface and design may change significantly

### 2.2 Stability and Reliability
- The Software may crash, freeze, or malfunction
- Data loss may occur (settings, statistics, configurations)
- Compatibility with future Star Citizen updates is not guaranteed
- Performance may vary significantly between systems

### 2.3 No Warranty
- The Software is provided "AS IS" without any warranty
- No guarantee of fitness for any particular purpose
- No warranty of merchantability or non-infringement
- Developer assumes no liability for any damages

### 2.4 User Responsibilities
- Back up important data regularly
- Report bugs and issues promptly
- Provide constructive feedback
- Understand that early access means ongoing changes

---

## 3. NETWORK CONNECTIVITY REQUIREMENT

**SC KILL TRACKER LITE REQUIRES INTERNET CONNECTION AND CANNOT OPERATE OFFLINE**

### 3.1 Mandatory Online Requirements

You acknowledge that the Software **REQUIRES** continuous or periodic internet connectivity for:

**Authentication & Licensing:**
- License key validation on every startup
- License status verification (active, suspended, revoked)
- Hardware ID (HWID) verification
- Anti-piracy measures

**Core Functionality:**
- NPC database synchronization (GitHub: raw.githubusercontent.com)
- Actor classification updates
- Real-time NPC detection and reporting
- Software update checks

**Quality & Support:**
- Crash report submission
- Error logging and diagnostics
- Performance metrics (when implemented)
- Version compatibility checks

### 3.2 Network Endpoints

The Software connects to the following services:

**Primary Services (Required):**
- `http://api.sckilltracker.com` - License validation API
- `http://localhost:20420` - Local license validation server (optional)
- `https://raw.githubusercontent.com/HarleyTG-O/sc-killfeed/main/actors.json` - NPC database
- `https://api.github.com` - GitHub API for database updates

**Optional Services (Can be disabled):**
- Discord webhook endpoints (NPC reporting)
- Discord Rich Presence API
- Update distribution servers

### 3.3 No Offline Mode

**YOU CANNOT USE SC KILL TRACKER LITE WITHOUT INTERNET ACCESS**

- Offline mode is not available and will not be implemented
- License validation cannot be bypassed
- Local-only operation is not supported
- All features require network connectivity

**Attempting to circumvent network requirements violates this EULA and will result in license revocation.**

---

## 4. DATA COLLECTION AND TRANSMISSION

**BY USING THIS SOFTWARE, YOU CONSENT TO DATA COLLECTION AND TRANSMISSION**

### 4.1 Data Collected (Cannot Opt Out)

The Software automatically collects and transmits:

**User Data:**
- License key and activation status
- Username and SCKillTrac ID
- Hardware ID (HWID) and system UUID
- Registration and login timestamps

**System Data:**
- Operating system and version
- Hardware specifications (CPU, RAM, GPU)
- Display configuration (resolution, DPI)
- Software version and installation path

**Game Data:**
- Star Citizen log file location and content
- Kill/death events and statistics
- Actor names (NPCs and players)
- Game version and channel (LIVE/PTU)
- Session start/end times

**Diagnostic Data:**
- Application logs and error messages
- Crash dumps and stack traces
- Performance metrics
- API response times

### 4.2 Data Transmission

**ALL DATA IS TRANSMITTED EXCLUSIVELY TO KILL TRACKER SERVICES:**

- Data is encrypted in transit (HTTPS/TLS)
- Data is sent to our servers for processing
- Some data is stored permanently (license records, NPC database)
- Some data is retained temporarily (logs, crash reports)

**We do NOT sell or share your data with third parties for marketing purposes.**

### 4.3 NPC Database Contributions

**You acknowledge that NPC names you encounter will be:**
- Collected automatically from game logs
- Classified using AI algorithms
- Submitted to the community NPC database
- Made publicly available on GitHub
- Used to improve detection accuracy

**NPC contributions cannot be retracted once submitted.**

### 4.4 Crash Reporting

When the Software crashes:
- Full crash report is generated automatically
- Report includes system state, logs, and stack trace
- Report may include your username and SCKillTrac ID
- Report is transmitted to our servers for analysis
- You will see a crash report dialog

**Crash reporting cannot be disabled.**

---

## 5. RESTRICTIONS AND PROHIBITED CONDUCT

You may NOT:

### 5.1 Reverse Engineering
- Decompile, disassemble, or reverse engineer the Software
- Attempt to derive source code
- Analyze the Software's internal workings
- Create derivative works based on the Software

### 5.2 Modification and Tampering
- Modify, adapt, or create derivative versions
- Remove or alter copyright notices or watermarks
- Bypass or disable license validation
- Circumvent technical protection measures
- Inject code or manipulate memory

### 5.3 Distribution
- Redistribute, sell, or rent the Software
- Share your license key publicly
- Create or distribute cracks, patches, or key generators
- Upload the Software to file-sharing sites
- Bundle the Software with other products

### 5.4 Commercial Use
- Use the Software for commercial purposes (without permission)
- Charge others for access to the Software
- Provide the Software as a service
- Use the Software in a business setting

### 5.5 Malicious Use
- Use the Software to cheat or gain unfair advantages
- Automate or bot the Software
- Abuse APIs or services
- Harass, stalk, or harm other users
- Violate Star Citizen's Terms of Service

**Violation of these restrictions will result in immediate license revocation and possible legal action.**

---

## 6. INTELLECTUAL PROPERTY RIGHTS

### 6.1 Ownership

The Software and all intellectual property rights therein are owned by Harley's Studio and protected by:

- Copyright laws (domestic and international)
- Trademark laws
- Trade secret laws
- Other intellectual property laws and treaties

### 6.2 Trademarks

- "SC Kill Tracker" and "SCKillTrac" are trademarks of Harley's Studio
- "Star Citizen" is a registered trademark of Cloud Imperium Games
- This Software is not affiliated with or endorsed by Cloud Imperium Games

### 6.3 No Transfer of Rights

This EULA grants you a **license to use** the Software, not ownership. All rights not expressly granted are reserved by Harley's Studio.

---

## 7. UPDATES AND MODIFICATIONS

### 7.1 Automatic Updates

The Software may automatically:
- Download and install updates
- Modify existing features
- Add or remove functionality
- Update terms and policies

**You cannot disable critical security updates.**

### 7.2 Changes to Software

Harley's Studio reserves the right to:
- Modify or discontinue features
- Change system requirements
- Alter user interface and design
- Deprecate or remove functionality
- Change license terms (with notice)

**Continued use after updates constitutes acceptance of changes.**

---

## 8. LICENSE ENFORCEMENT AND BANS

### 8.1 License Validation

Your license will be validated:
- On every application startup
- Periodically during use (every 24 hours)
- When connecting to services
- After system changes (hardware upgrades)

**Failure to validate will result in application termination.**

### 8.2 Ban System

Harley's Studio may ban:

**User Bans:**
- Applies to your username/SCKillTrac ID
- Prevents login with banned username
- May apply to all your licenses

**License Key Bans:**
- Applies to specific license key
- Prevents activation and use
- License marked as revoked

**Hardware ID (HWID) Bans:**
- Applies to your computer's unique ID
- Prevents use on banned hardware
- Applies to all licenses on that device

**IP Address Bans:**
- Temporary or permanent IP blocks
- Prevents API access from banned IP

**SCKillTrac ID Bans:**
- Account-level ban across all services
- Most severe enforcement action

### 8.3 Ban Reasons

Bans may be issued for:
- EULA violations
- Terms of Service violations
- Cheating or exploiting
- Harassment or abuse
- License sharing or fraud
- Circumventing technical protections
- Malicious activity

### 8.4 Ban Appeals

To appeal a ban:
- Contact support with your SCKillTrac ID
- Explain the situation and provide evidence
- Appeals are reviewed within 7-14 days
- Decisions are final and at developer's discretion

**No refunds for bans resulting from EULA violations.**

---

## 9. WARRANTY DISCLAIMER

**THE SOFTWARE IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND.**

Harley's Studio disclaims all warranties, express or implied, including but not limited to:

- **MERCHANTABILITY** - No warranty that Software is suitable for sale
- **FITNESS FOR A PARTICULAR PURPOSE** - No warranty that Software meets your needs
- **NON-INFRINGEMENT** - No warranty that Software doesn't violate others' rights
- **ACCURACY** - No warranty that data is accurate or complete
- **RELIABILITY** - No warranty of uninterrupted or error-free operation
- **SECURITY** - No warranty that Software is secure or free from vulnerabilities

**YOU USE THE SOFTWARE AT YOUR OWN RISK.**

---

## 10. LIMITATION OF LIABILITY

**TO THE MAXIMUM EXTENT PERMITTED BY LAW, HARLEY'S STUDIO SHALL NOT BE LIABLE FOR:**

### 10.1 Indirect Damages
- Loss of profits or revenue
- Loss of data or information
- Loss of business opportunities
- Loss of goodwill or reputation
- Cost of substitute services

### 10.2 Consequential Damages
- Damages arising from Software use or inability to use
- Damages from errors, bugs, or defects
- Damages from data loss or corruption
- Damages from security breaches
- Damages from third-party actions

### 10.3 Special or Incidental Damages
- Personal injury or property damage
- Emotional distress
- Reliance damages
- Any other damages not expressly covered

**TOTAL LIABILITY SHALL NOT EXCEED THE AMOUNT YOU PAID FOR YOUR LICENSE (IF ANY).**

**Some jurisdictions do not allow limitation of liability, so these limitations may not apply to you.**

---

## 11. TERMINATION

### 11.1 Termination by You

You may terminate this EULA at any time by:
- Uninstalling the Software
- Deleting all copies of the Software
- Ceasing all use of services
- Requesting license deactivation

**No refunds will be provided for voluntary termination.**

### 11.2 Termination by Developer

Harley's Studio may terminate this EULA immediately if you:
- Breach any term of this EULA
- Violate Terms of Service or Privacy Policy
- Engage in prohibited conduct
- Fail license validation
- Are subject to a ban

### 11.3 Effect of Termination

Upon termination:
- Your license is immediately revoked
- You must cease all use of the Software
- You must delete all copies of the Software
- Your access to services is blocked
- Your data may be deleted (subject to retention policies)
- No refunds will be provided

**Sections regarding disclaimers, limitations of liability, and intellectual property survive termination.**

---

## 12. INDEMNIFICATION

You agree to indemnify, defend, and hold harmless Harley's Studio from any claims, damages, losses, liabilities, and expenses (including legal fees) arising from:

- Your use or misuse of the Software
- Your violation of this EULA
- Your violation of any law or regulation
- Your infringement of third-party rights
- Your negligence or willful misconduct

---

## 13. GOVERNING LAW AND JURISDICTION

### 13.1 Governing Law

This EULA is governed by the laws of [Your Jurisdiction], without regard to conflict of law principles.

### 13.2 Jurisdiction

Any disputes arising from this EULA shall be resolved exclusively in the courts of [Your Jurisdiction].

### 13.3 Arbitration

For disputes under $10,000, parties agree to binding arbitration before litigation.

---

## 14. GENERAL PROVISIONS

### 14.1 Entire Agreement

This EULA, together with the Terms of Service and Privacy Policy, constitutes the entire agreement between you and Harley's Studio regarding the Software.

### 14.2 Severability

If any provision of this EULA is found invalid or unenforceable, the remaining provisions remain in full force and effect.

### 14.3 Waiver

Failure to enforce any provision does not constitute a waiver of that provision or any other provision.

### 14.4 Assignment

You may not assign or transfer this EULA. Harley's Studio may assign this EULA to any successor or affiliate.

### 14.5 Force Majeure

Harley's Studio is not liable for delays or failures due to causes beyond reasonable control (natural disasters, wars, strikes, etc.).

### 14.6 Export Compliance

You agree to comply with all export laws and regulations. You may not export or re-export the Software to prohibited countries or entities.

---

## 15. CONTACT INFORMATION

**Developer:** Harley's Studio  
**Email:** sckilltracker@gmail.com  
**Website:** https://sckilltracker.com  
**Discord:** https://discord.gg/jxfHnGQqj7

For EULA questions, contact: sckilltracker@gmail.com

---

## 16. ACKNOWLEDGMENT

**BY CLICKING "I AGREE", INSTALLING, OR USING THE SOFTWARE, YOU ACKNOWLEDGE THAT:**

✅ You have read and understood this EULA  
✅ You agree to be bound by its terms  
✅ You understand this is early access software  
✅ You consent to data collection and transmission  
✅ You understand internet connectivity is required  
✅ You accept all risks associated with use  
✅ You agree to the warranty disclaimers and liability limitations  

**IF YOU DO NOT AGREE, DO NOT USE THE SOFTWARE.**

---

**Last Updated:** January 15, 2025  
**Version:** 0.1.6.2  
**EULA ID:** SCKT-LITE-EULA-v0.1.6.2

© 2025 Harley's Studio. All rights reserved.

