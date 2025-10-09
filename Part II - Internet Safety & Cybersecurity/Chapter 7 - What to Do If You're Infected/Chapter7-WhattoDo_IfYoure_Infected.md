---
# Chapter 7: What to Do If You're Infected
## Emergency Response: Professional Malware Removal Procedures That Actually Work
---

> "Every minute counts when dealing with malware. The right response in the first hour can save weeks of recovery time." - Professional reality after 20+ years of emergency cleanings.

After over 20 years of computer security, repairs, and migrations, this chapter gives you the exact strategies and professional realities we use on the front lines to cover **The Professional Malware Removal Procedures**.

### What You'll Learn in This Chapter:

* Professional infection recognition that catches problems early
* Step-by-step removal process used in thousands of successful cleanings
* When to attempt self-removal vs. calling for professional help immediately
* Prevention strategies that stop reinfection
* Emergency response protocols for different threat levels

---

## The Reality: Time is Critical When You're Infected

*From Our Emergency Response Experience*

| Incident Response Time | Success Rate | Average Cost | Result |
| :--- | :--- | :--- | :--- |
| **0–2 hours** | 95% | $150 | Minimal damage, quick resolution. |
| **24+ hours** | 70% | $300 | Moderate damage, more complex cleanup. |
| **1+ week** | 40% | $500+ | Potential data loss, often requires full OS reinstall. |

*Lesson: Quick professional response prevented financial disaster in a banking malware case. The speed and quality of the initial response determine the final cost and data safety.*

### Recognizing the Signs: Professional Assessment Checklist

*Early Detection Saves Everything. 80% of serious infections have warning signs 2–6 hours before major damage occurs.*

#### Immediate Action Required Signs

**STOP USING COMPUTER AND CALL FOR HELP:**

* **Financial Security Threats:** Banking or shopping sites look different, browser redirects during financial transactions, or unauthorized transactions appear.
* **System Compromise Indicators:** Antivirus software is disabled, computer won't start in **Safe Mode**, Blue Screen of Death errors, or files being **encrypted or renamed** (Ransomware).

*Professional Protocol: If ANY of these signs appear, disconnect from the internet immediately and seek professional help within 2 hours.*

#### Performance Warning Signs

*Indicates Possible Infection - Begin Assessment:*

* **System Behavior Changes:** Computer significantly slower than normal, frequent freezing/crashing, or hard drive constantly active when idle.
* **Browser Abnormalities:** Homepage changed without permission, new toolbars/extensions you didn't install, or search results redirected to advertising sites.

#### Professional Assessment Process (5 Minutes)

1.  **Task Manager Analysis (Ctrl + Shift + Esc):** Sort by **CPU usage**. Look for unknown programs using high CPU or running from suspicious locations (like a `Temp` folder).
2.  **Startup Program Review (Task Manager → Startup):** Look for unknown programs set to start automatically or entries with no manufacturer listed.
3.  **Browser Quick Check:** In each browser (Chrome, Firefox, Edge), check for unwanted extensions/add-ons and verify homepage/search engine settings.

*Professional Decision Point: If you find ANY suspicious items, proceed with the professional removal procedures.*

---

### Step-by-Step Removal Process: Professional Protocol

#### Phase 1: Immediate Containment (First 15 Minutes)

1.  **Isolation Protocol:** **Disconnect from the internet** (unplug ethernet/disable WiFi). Close all running programs.
2.  **Emergency Backup:** If possible, copy critical files to an external drive.
3.  **Boot Assessment:** Restart the computer. Try booting into **Safe Mode** (often required for malware removal).

#### Phase 2: Professional Malware Removal (1–4 Hours)

*The exact order matters. Run these tools sequentially:*

1.  **Tool 1: RKill (Malware Disabling):** Downloads from bleepingcomputer.com. **Purpose:** Disables active malware processes to allow other tools to function.
2.  **Tool 2: Malwarebytes Anti-Malware:** Run a **Full system scan**. **Action:** Quarantine ALL detected threats.
3.  **Tool 3: ADWCleaner:** Downloads from malwarebytes.com/adwcleaner. **Purpose:** Removes adware, toolbars, and browser hijackers.
4.  **Tool 4: Antivirus Full Scan:** Use your regular antivirus (Windows Defender or installed security suite). Run a **Full system scan** to confirm nothing was missed.

#### Phase 3: Browser Restoration (30 Minutes)

* **Cleanup:** In each browser, use the built-in "Reset and clean up" (Chrome), "Refresh" (Firefox), or "Reset settings" (Edge) feature.
* **Harden:** Remove all unwanted extensions, verify homepage, and **install uBlock Origin** (essential ad blocker).

#### Phase 4: Advanced Threat Detection (Optional)

* **For Persistent Threats:** Use specialized tools like **TDSKiller** (Kaspersky's rootkit detector) or **HitmanPro** (a second opinion scanner).
* **For System Boot Issues:** Use **Windows Defender Offline** (Microsoft's bootable antivirus) to scan the system before Windows loads.

#### Phase 5: System Verification and Hardening (45 Minutes)

1.  **System Integrity Check:** Open Command Prompt as Administrator and run **`sfc /scannow`** to check Windows integrity.
2.  **Updates:** Install all available Windows Updates and update all software/drivers.
3.  **Verify Security:** Ensure real-time protection is **active** on your security software.

---

### When to Seek Professional Help: Clear Decision Points

| Immediate Professional Help Required (Call Within 2 Hours) | DIY Removal Appropriate (Safe to Attempt Self-Removal) |
| :--- | :--- |
| Banking/financial malware detected. | Adware/PUP infections (browser redirects, pop-ups). |
| **Ransomware infection** (files encrypted or computer locked). | Simple virus detections with a clear removal path. |
| System won't boot (blue screens, boot loops). | Performance issues only (no security/financial threats). |
| Multiple failed removal attempts. | Technical comfort level is high. |
| Business computer infected. | System boots normally and all tools run without errors. |

*Professional ROI: Time savings alone often justify professional service for business users or complex infections. A professional service offers a **95% success rate with a guarantee**.*

---

### Prevention Going Forward: Professional Hardening

Stopping Reinfection Before It Starts

#### Immediate Post-Cleaning Security

* **Security Software Upgrade:** Uninstall any trial antivirus and install professional-grade protection (Bitdefender, Kaspersky, or Malwarebytes Premium).
* **Browser Security:** **Install uBlock Origin** and **HTTPS Everywhere**. Remove suspicious extensions.
* **Windows Security Configuration:** Enable **Windows Firewall**, configure **User Account Control (UAC)**, and **Disable AutoRun** to prevent USB malware spread.

#### Long-term Protection Strategy

* **Behavior Modifications:** Download software from **official sites only**, read installation screens carefully (to uncheck bundled software), and **verify email attachments**.
* **Technical Safeguards:** Enable **automatic backups** (local and cloud) and use a **Standard User account** for daily tasks.
* **Monthly Maintenance:** Run a full system scan, review browser extensions, and verify software updates.

### Emergency Response Protocols

| Emergency Type | Immediate Action (First 30 Minutes) |
| :--- | :--- |
| **Banking Malware** | Disconnect internet. Change banking passwords from a **clean device**. Contact banks immediately. |
| **Ransomware** | **Disconnect from network** (prevent spread). Document ransom message. Check backups immediately. **Contact professional assessor before payment.** |
| **Business Network** | Network isolation of affected systems. Incident response team activation. Professional forensics and removal. |

***

### Chapter Summary: Key Takeaways

Review the most critical concepts learned in this chapter to cement your foundation:

* **Time is Critical:** Quick response determines the final cost and data safety.
* **Containment:** Disconnect from the internet immediately when a threat is confirmed.
* **Professional Help:** Seek help for ransomware, financial malware, or if the system won't boot.

#### Professional Insight:

> "The knowledge you gain here isn't just theory—it's the front-line reality that keeps our clients secure and productive."

### What's Next?

In **Chapter 8**, we'll cover **Keeping Your Computer Healthy**—the essential knowledge you need to master the routine care that prevents problems before they become emergencies.

**Remember:** Malware infection isn't a matter of if, but when. Being prepared with professional response procedures turns potential disasters into manageable inconveniences.
