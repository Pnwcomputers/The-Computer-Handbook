---
# Chapter 10: Basic Troubleshooting
## Simple Solutions for Common Problems
---

> "There are no mistakes; only opportunities for improvement." - Jon P.

After over 20 years of computer security, repairs, and migrations, this chapter gives you the exact strategies and professional realities we use on the front lines to cover **Solving Common Computer Problems**.

### What You'll Learn in This Chapter:

* The professional approach to diagnosing problems
* When to restart vs. when not to restart
* Simple solutions that fix 80% of common issues
* How to avoid making problems worse
* When you've reached the limits of DIY repair

---

## The Professional Mindset: How We Approach Problems

When a professional encounters a computer problem, we follow a systematic approach called the **OODA Loop** (Observe, Orient, Decide, Act).

* **OBSERVE:** What exactly is happening? When did it start?
* **ORIENT:** What could cause this problem? What changed recently?
* **DECIDE:** What's the safest, simplest solution to try first?
* **ACT:** Try the solution, then observe the results.

> **The Golden Rule of Troubleshooting: One change at a time.** If you try three solutions simultaneously and the problem gets fixed, you won't know which one worked—or which one caused a new problem.

### Before You Start: The Safety Checklist

#### Document the Problem:

* **What exactly is happening?** (Be specific)
* When did this start?
* Has anything changed recently? (New software, updates, hardware?)

#### Check the Obvious (Seriously):

* **Power Connections:** Is everything plugged in securely? Are power strips turned on?
* **Display Connections:** Is the monitor plugged in, turned on, and connected securely to the correct port?
* **Peripheral Connections:** Are your keyboard, mouse, and other USB devices properly inserted/charged?

#### The "Have You Tried Turning It Off and On Again?" Reality

A restart often works because it clears memory conflicts, stops misbehaving programs, and reloads system files cleanly.

* **When restarting helps:** Computer running slowly, programs not responding, strange error messages.
* **When NOT to restart:** During software installations or updates, if you are getting hardware failure warnings, or when the computer is making unusual noises.

---

### Common Problems and Simple Solutions

#### Problem: Computer Won't Start At All

**Symptoms:** No lights, no sounds, no screen activity when you press the power button.

1.  **Power Supply Check:** Verify the cord is secure at both ends, check power strips, and try a different outlet.
2.  **Simple Hardware Reset (Professional Technique):**
    * Completely disconnect power (unplug desktop or remove laptop battery).
    * **Hold the power button for 15–30 seconds** (drains residual power).
    * Reconnect power and try again.

#### Problem: Computer Starts But Screen Stays Black

**Symptoms:** You hear fans/drives working, but the screen shows nothing.

1.  **Display Connection Check (Most Common Cause):** Ensure the monitor is on, set to the correct input (HDMI 1, DisplayPort, etc.), and connected to the correct port on the computer.
2.  **Hardware Seating Check (DIY for the comfortable):** For a desktop, power off and unplug the computer. Gently remove and reseat the RAM modules, ensuring they click securely into place.

#### Problem: Computer Starts But Runs Very Slowly

**Symptoms:** Several minutes to boot, programs take forever to open, sluggish performance.

1.  **Resource Check (Task Manager):** Press **Ctrl + Shift + Esc**. Check the **Processes** tab for unknown programs using high CPU or Memory. **End** unnecessary programs (only end what you recognize).
2.  **Startup Program Management:** Open **Task Manager → Startup**. Disable programs you don't need immediately at startup (e.g., Spotify, Adobe updaters).
3.  **Storage Space Check:** Open **File Explorer → This PC**. You need at least **15–20% free space**. Run **Disk Cleanup** to clear temporary files.
4.  **Check for Malware:** Run a full scan with your antivirus (Chapter 6).

#### Problem: Programs Keep Crashing or Freezing

**Symptoms:** Applications suddenly close, "Not Responding" messages, computer locks up.

1.  **Identify the Pattern:** Is it one program (update/reinstall needed) or all programs (likely hardware/system issue)?
2.  **Software Solutions:** Update the problem program, or reinstall it if the problem persists.
3.  **System Solutions (Memory):** Run **Windows Memory Diagnostic** (Type in Start menu). This tests your RAM for errors, which is a common cause of random crashes.

#### Problem: Internet Connection Issues

**Symptoms:** Can't access websites, slow internet, intermittent connectivity.

1.  **Isolate the Problem:** Test other devices (phone, tablet) on the same network.
    * If they work: Problem is your computer.
    * If nothing works: Problem is your router/ISP.
2.  **Network Adapter Reset:** Right-click network icon → Open Network & Internet settings → **"Network reset"** (at the bottom). Restart the computer.
3.  **DNS Reset (Advanced Technique):** Open Command Prompt (Admin) and type: **`ipconfig /flushdns`**

---

### Advanced Beginner Techniques

These are Windows built-in tools that can fix deeper system issues:

| Tool | When to Use | How to Run | What it Does |
| :--- | :--- | :--- | :--- |
| **System File Checker (SFC)** | System errors, crashes, corrupted Windows files. | Open **Command Prompt (Admin)** and type: `sfc /scannow` | Scans all Windows system files and replaces corrupted ones. |
| **Check Disk (CHKDSK)** | Hard drive errors, file corruption. | Open **File Explorer**, right-click main drive → **Properties → Tools → Check** | Scans the hard drive for errors and attempts repairs. |
| **System Restore** | After bad software installation or mysterious problems. | Type **"Create a restore point"** in Start menu, then click **"System Restore."** | Returns Windows settings to a previous working state (does not affect personal files). |

### When to Stop and Call a Professional

Knowing your limits prevents small problems from becoming catastrophic.

#### Red Flags: Stop Immediately and Call for Help

* **Financial/Security Issues:** Suspected banking malware, ransomware, or identity theft indicators.
* **Hardware Warnings:** Unusual burning smells, excessive heat, hard drive **clicking or grinding noises**, or repeated hardware failure messages.
* **Data at Risk:** Any situation where data loss would be catastrophic and files are not backed up (Chapter 9).
* **Beyond Your Comfort Level:** Opening computer cases, modifying the system registry, or guessing at solutions.

#### Questions to Ask Yourself Before Continuing:

* **"Can I make this worse?"** If yes, consider professional help.
* **"Is this data irreplaceable?"** If yes, **backup first** or call a professional.
* **"Am I guessing at solutions?"** If yes, stop and research or ask for help.

***

### Chapter Summary: Key Takeaways

Review the most critical concepts learned in this chapter to cement your foundation:

* **OODA Loop:** Follow the professional approach: Observe, Orient, Decide, Act, making **one change at a time.**
* **First Steps:** Check power, connections, and always run Task Manager to diagnose slow performance.
* **Know Your Limit:** Stop immediately and call for help if you hear clicking/grinding noises or suspect banking malware.

#### Professional Insight:

> "The knowledge you gain here isn't just theory—it's the front-line reality that keeps our clients secure and productive."

### What's Next?

This completes the foundational chapters! We recommend creating a **Final Chapter or Conclusion** to review all key takeaways and provide resources for continued learning.

**Remember:** The most successful computer users know their capabilities and aren't afraid to ask for help when they reach those limits.
