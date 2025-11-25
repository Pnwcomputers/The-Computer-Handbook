---
# Chapter 6: Antivirus and Security Software
## Protecting Your Computer from Digital Threats
---

> "Fixing a computer issue doesn't mean you have to learn the entire system inside and out. It's like investing time, money and effort into learning all about forging metal, just to make a fork... understanding just enough can get the job done." - Jon P.

After over 20 years of computer security, repairs, and migrations, this chapter gives you the exact strategies and professional realities we use on the front lines to cover **Choosing and Using the Right Security Tools**.

## What You'll Learn in This Chapter:

* What antivirus software actually does (and what it doesn't do)
* How to choose reliable security software
* Step-by-step guide to cleaning an infected computer
* When to call for professional help
* How to prevent future infections

---

<p align="center">
  <img src="/Images/Chapter 6 - Antivirus and Security Software/total security.png" width="460" height="460" alt="Different types of Modern CPU's">
</p>

## Understanding Computer Security: The Basics

Think of your computer like your home—you want to keep the bad guys out, but you also need to let the good guys (legitimate programs) in.

### The Digital Bad Guys:

* **Viruses:** Digital diseases that delete files, slow down your computer, or steal information.
* **Malware:** The umbrella term for all malicious (bad) software. It includes viruses, but also the threats below.
* **Adware:** Programs that bombard you with unwanted advertisements, slowing your computer and tracking you online.
* **Spyware:** Software that secretly watches what you do (passwords, credit cards) and reports back to criminals.
* **Browser Hijacks:** When software takes control of your web browser, changing your home page, search engine, or redirecting you to fake sites.

### How Infections Happen (So You Can Avoid Them)

Understanding how these threats get onto your computer is your first line of defense:

* **Email Attachments:** Never open attachments from unknown people. Even friends' emails might be infected.
* **Fake Software Downloads:** Always download software from the **official website**.
* **Infected Websites:** Some sites automatically download malware to your computer just by visiting them.
* **Social Engineering:** When criminals trick you into installing malware by pretending to be helpful (e.g., a pop-up that says "Your computer is infected! Click here to clean it!").

<p align="center">
  <img src="/Images/Chapter 6 - Antivirus and Security Software/anivirus metaphors vs reality.png" width="460" height="460" alt="Different types of Modern CPU's">
</p>

---

<p align="center">
  <img src="/Images/Chapter 6 - Antivirus and Security Software/Gemini_Generated_Image_nvq7mrnvq7mrnvq7.png" width="460" height="460" alt="Different types of Modern CPU's">
</p>

## Choosing Antivirus Software: What Actually Works

*Based on 20+ years of field experience removing malware*

**The Truth About Antivirus Software:** There is NO "golden bullet" security solution that catches everything. If there was, I'd be selling it like crazy. Instead, the reality is that effective security requires a **layered approach**—and that's exactly what professional computer technicians use.

### The Stadium Security Approach

Think of computer security like security at a major stadium:

* **Windows Defender** is your **Main Ticket Gate**—the first line of defense that checks everyone coming in.
* **Secondary Tools (MBAM, ADWCleaner)** are your **Internal Security and Auditors**—they patrol inside and double-check everyone, even those who were "approved" at the gate.

Even if something gets past your primary antivirus by appearing legitimate, your secondary tools will audit and verify it anyway. This layered approach leads to more secure systems and more thoroughly cleaned computers when infections occur.

<p align="center">
  <img src="/Images/Chapter 6 - Antivirus and Security Software/paid for vs free av.png" width="460" height="460" alt="Different types of Modern CPU's">
</p>

### Windows Defender: Your Primary Gatekeeper

Good News: If you have Windows 10 or 11, you already have solid antivirus protection built-in—and it's what I use as the primary defense for most clients.

| What Windows Defender Does Well | What to Know |
| :--- | :--- |
| Automatically scans files as you download them. | No single antivirus catches 100% of threats—that's why we layer. |
| Updates itself regularly without user intervention. | Works silently in the background. |
| Free with Windows—no subscriptions needed. | Excellent detection rates for a primary defender. |
| Low system resource usage. | Integrates seamlessly with Windows. |

**About Paid Antivirus Software:** Paid solutions like Bitdefender, Kaspersky, or Norton often include extra features like VPNs, password managers, parental controls, and more automation. However, they don't fundamentally provide better core protection than Windows Defender when used in a proper layered security approach. The extra cost buys convenience and bundled features, not invincibility.

### The Layered Defense: Secondary Tools (What We Actually Use)

| Category | Product | Role in Layered Defense |
| :--- | :--- | :--- |
| **Primary Gatekeeper** | Windows Defender | Your main ticket gate—always running, first line of defense. |
| **Internal Auditor** | **Malwarebytes Anti-Malware (MBAM)** | Checks what got past the gate—excellent at finding threats other programs miss or approve. Essential for cleanup and verification. |
| **Specialized Auditor** | **ADWCleaner** (Free Tool from Malwarebytes) | Specializes in browser hijacks and adware that often masquerade as legitimate software. |

> **Why This Matters:** Malware authors specifically test their creations against popular antivirus programs to make sure they go undetected. By using multiple layers that audit each other, you catch threats that any single program would miss.

---

<p align="center">
  <img src="/Images/Chapter 6 - Antivirus and Security Software/protection flow chart.png" width="460" height="460" alt="Different types of Modern CPU's">
</p>

## Step-By-Step: Cleaning an Infected Computer

*Adapted from our professional virus removal procedures*

> ⚠️ **Important Safety Warning:** If your computer handles sensitive information (banking, business), and you suspect a keylogger, **stop using it for sensitive activities immediately.** Change your passwords from a different, clean computer.

### Signs Your Computer Might Be Infected:

* Dramatically **Slow Performance** (long startup/program open times).
* **Pop-up Advertisements** when you're not browsing the internet.
* **Changed Browser Settings** (different home page or search engine).
* **Unexpected Programs** you don't remember installing.

<p align="center">
  <img src="/Images/Chapter 6 - Antivirus and Security Software/clean up flow chart.png" width="460" height="460" alt="Different types of Modern CPU's">
</p>

### The Professional Cleaning Process

**Step 1: Disconnect from the Internet**

* **Why:** Prevents the malware from downloading more infections or sending your information to criminals.
* **How:** Unplug your ethernet cable or turn off WiFi.

**Step 2: Boot to Safe Mode**

Safe Mode loads Windows with minimal programs, making it easier to remove malware.

* **For Windows 10/11:** Hold the **Shift** key while clicking **"Restart."**
* Choose "Troubleshoot" → "Advanced Options" → "Startup Settings."
* Click "Restart" and then press **"4"** for Safe Mode.

**Step 3: Run Multiple Scans (Layered Security Approach)**

*Run these scans IN ORDER. Each tool catches different types of malware and serves as an auditor for the others.*

1.  **First: ADWCleaner** (Specialized auditor for adware/browser hijacks).
    * Run the program (no installation needed) and click **"Scan Now."**
    * Click **"Clean & Repair"** and restart when prompted.
2.  **Second: Malwarebytes Anti-Malware** (Internal security auditor for trojans/spyware).
    * Run a **full system scan** (not quick scan).
    * This tool will audit everything—even items that Windows Defender approved.
    * Remove all detected items and restart if prompted.
3.  **Third: Windows Defender** (Main gatekeeper verification).
    * Update your program and run a **full system scan** one last time.
    * This final scan ensures the primary defense system is clean and up-to-date.

> **The Layered Approach in Action:** You'll often find that each tool catches things the previous ones missed. MBAM might flag something Windows Defender approved, or ADWCleaner might remove browser extensions that seemed legitimate. That's not a failure—that's the layered approach working exactly as designed.

**Step 4: Check All Web Browsers**

*For Each Browser (Chrome, Firefox, Edge):*

* Remove suspicious extensions/add-ons.
* Reset your home page and default search engine.
* Clear browser data (cache, cookies, history).

**Step 5: Update Everything**

* Install all available **Windows Updates**.
* Update your **Browser** and essential software (like Adobe Reader/Java).

**Step 6: Create a Clean Restore Point**

After cleaning, create a system restore point so you can return to this clean state if needed.

---

<p align="center">
  <img src="/Images/Chapter 6 - Antivirus and Security Software/Gemini_Generated_Image_nehae4nehae4neha.png" width="460" height="460" alt="Different types of Modern CPU's">
</p>

## Prevention: Your Best Defense

**The 90% Rule:** 90% of computer infections are preventable with good habits.

### Safe Computing Habits:

* **Email Safety:** Never open attachments from strangers. Call the sender to verify if an urgent message is suspicious.
* **Download Safety:** Only download software from **official websites**. Avoid "Download Now" buttons in pop-up ads.
* **Browser Safety:** Keep your browser updated and use an **ad blocker** to reduce exposure to malicious ads.
* **General Safety:** Keep Windows updated and use caution with USB drives from other people.

### Setting Up Automatic Protection:

* **Windows Updates:** Set Windows to install updates automatically (and don't postpone security updates).
* **Windows Defender:** Make sure it's enabled and updating automatically. Schedule weekly full scans if desired.
* **Periodic Auditing:** Run MBAM scans monthly as a secondary audit of your system—even if nothing seems wrong.

---

<p align="center">
  <img src="/Images/Chapter 6 - Antivirus and Security Software/When to stop and call.png" width="460" height="460" alt="Different types of Modern CPU's">
</p>

## When to Call a Professional

*Based on our professional service experience*

You should call for help when:

* **Financial Security is Compromised:** You suspect a keylogger or banking virus, or unauthorized transactions appear.
* **The Infection Won't Go Away:** Multiple professional scans (Malwarebytes, ADWCleaner) don't solve the problem, or the computer keeps getting reinfected.
* **You're Not Comfortable:** Following the removal steps seems too complicated, or you're worried about damaging important data.
* **Critical Business Systems:** Your livelihood or regulatory compliance depends on the computer.

### Questions to Ask a Computer Repair Service:

* "Do you **guarantee** your virus removal work?"
* "Will you **back up my data** before starting?"
* "How will you help **prevent this** from happening again?"
* "Do you use a layered security approach for cleanup?"

***

## Chapter Summary: Key Takeaways

Review the most critical concepts learned in this chapter to cement your foundation:

* **There is NO golden bullet security solution**—effective protection requires a layered approach.
* **The Stadium Security Model:** Windows Defender is your main ticket gate, while tools like MBAM act as internal auditors that double-check everything.
* **Infection Protocol:** Disconnect from the internet, boot into Safe Mode, and run multiple scanning tools in sequence.
* **Good habits are your best protection.** Most infections are preventable.

### Professional Insight:

> "The knowledge you gain here isn't just theory—it's the front-line reality that keeps our clients secure and productive. Layered security isn't about redundancy—it's about having multiple specialized experts that audit each other's work."

## What's Next?

In **Chapter 7**, we'll cover **What to Do If You're Infected**—the essential knowledge you need to follow the exact step-by-step procedures we use to eliminate malware.

**Remember:** The people who get infected the least aren't necessarily the most tech-savvy - they're the most cautious. When in doubt, don't click. It's easier to prevent an infection than to clean one.
