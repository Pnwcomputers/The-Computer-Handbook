---
# Chapter 14: Internet Troubleshooting
## Simple Solutions for Common Problems
---

> "Make sure there is a valid IP on the printer if using a network connection... Try different driver versions until one works... This isn't about becoming a network engineer - it's about solving the 90% of internet problems that can be fixed at home before calling for expensive professional service."

After over 20 years of computer security, repairs, and migrations, this chapter gives you the exact strategies and professional realities we use on the front lines to cover **Solving Connectivity Issues Before Calling the ISP**.

### What You'll Learn in This Chapter:

* Professional network diagnostic procedures (OODA Loop for networking)
* Common connectivity issues and their real solutions
* WiFi problems that aren't actually WiFi problems
* Smart home device setup and troubleshooting
* When your ISP is actually the problem vs. when it's not
* Professional tools for network diagnosis

---

## The Reality of Internet Troubleshooting

*Professional Insight: "The first rule of network troubleshooting: the problem is probably within 10 feet of the person complaining about it. Check everything local before blaming the internet."*

#### The Network Path Reality:

Your internet connection has 4 distinct segments: **Your Device** → **Your Local Network** → **Your ISP** → **The Destination**. Most problems occur in your local equipment (Device and Local Network).

#### The Professional OODA Loop for Network Issues:

1.  **Observe:** Gather data on affected devices, error patterns, and recent changes.
2.  **Orient:** Analyze patterns. *Single device problems = local configuration/hardware.* *All devices, wired and wireless = ISP/Modem issue.*
3.  **Decide:** Choose the safest strategy. **Check physical connections first.**
4.  **Act:** Implement systematic solutions, **changing one thing at a time.**

---

### Common Connectivity Issues: Professional Solutions

#### Problem: "Internet is Down" (Complete Connectivity Loss)

1.  **Check Physical Layer:** Verify router and modem power lights (must be solid, not blinking/red). Check Ethernet cables.
2.  **Test Device Connectivity:** **Connect directly to the modem with an Ethernet cable.**
3.  **Professional Power Cycle Sequence:** **Unplug modem and router for 30 seconds.** Plug in the **modem first** (wait 2 minutes), then plug in the **router** (wait 2 minutes).

* *If wired to modem works:* Router problem.
* *If wired to modem fails:* ISP or modem problem.

#### Problem: "Internet is Slow" (Performance Issues)

1.  **Professional Speed Test:** Connect via **Ethernet directly to the router**. Close all background programs. Test from `fast.com` and `speedtest.net`. Compare to advertised speed.
2.  **Professional Interpretation:** **Under 50%** of advertised speed is a **Likely ISP problem** (if tested wired). **50-89%** is a **Possible local network issue**.

*Common Causes:* Old **WiFi standards** (802.11g is 20Mbps max, regardless of ISP speed), **distance** from router, or **network congestion**.

---

### WiFi Problems and Solutions: Professional Approach

#### WiFi Speed Reality Check:

| WiFi Standard (2.4GHz) | Real-world Max Speed |
| :--- | :--- |
| **802.11g** | $\approx 20\text{Mbps}$ |
| **802.11n** | $\approx 50\text{Mbps}$ |
| **802.11ac (5GHz)** | $\approx 200\text{Mbps}-400\text{Mbps}$ |

*Why this matters:* If your device only supports an older standard, the problem isn't your ISP.

#### Problem: "WiFi Keeps Disconnecting" (Intermittent Connectivity)

* **WiFi Signal Analysis:** **Router placement** must be central, elevated, and not enclosed. Check for **Interference sources** (microwaves, baby monitors).
* **Professional Solutions:** If all devices disconnect, the router may be **overheating** or have **outdated firmware**. If a single device disconnects, its **WiFi adapter may be failing**.

#### Smart Home Device Setup: Professional Approach

* **Network Design:** **2.4GHz WiFi is required for most smart devices.** Ensure strong coverage throughout the home.
* **Setup Tip:** Install devices **closest to the router first** to establish a baseline. Verify the 2.4GHz network is broadcasting and accessible, as many devices will not work on 5GHz.

---

### When to Call Your ISP: Professional Decision Making

#### ISP vs. Local Problem: Professional Diagnostic Criteria

| Call ISP When: | DON'T Call ISP When: |
| :--- | :--- |
| **Modem shows no internet connection** (specific status lights). | Only **WiFi devices** are affected (router/WiFi problem). |
| **Direct Ethernet to modem fails speed tests** (document results). | Only **one device** is affected (device problem). |
| Multiple neighbors report the same issue. | Speed test passes via Ethernet (local network problem). |

*Professional Preparation:* **Test with Ethernet directly to the modem** before calling. Run speed tests to establish a baseline. Check the ISP's website for service outages.

---

### Professional Network Diagnostic Tools and Procedures

#### Command Line Diagnostic Tools (Windows):

* `ipconfig /all`: Shows your network adapter configuration.
* `ping 8.8.8.8`: Tests basic internet connectivity (Google DNS).
* `nslookup google.com`: Tests DNS resolution (if this fails, you can't translate domain names to IP addresses).
* `tracert google.com`: Shows the network path to the destination (identifies routing failures).

#### Network Information Retrieval:

* **Router Access:** Find your router's IP address (the **Default Gateway** in `ipconfig`). Access the admin page by entering the IP in a web browser.
* **WiFi Password Retrieval:** Use the command `netsh wlan show profile name="NETWORK_NAME" key=clear` in an administrator Command Prompt to find the stored password (**Key Content**).

***

### Chapter Summary: Key Takeaways

Review the most critical concepts learned in this chapter to cement your foundation:

* **Professional Diagnostic Approach:** 90% of "internet problems" are local. Test **physical layer first**, then test with **Ethernet to eliminate WiFi variables**.
* **ISP vs. Local Issues:** **Test Ethernet directly to the modem** to isolate an ISP problem. WiFi-only problems are **local network problems**.
* **WiFi Reality Check:** WiFi is always slower than Ethernet. Your device's capabilities limit the actual speed you get.

#### Professional Insight:

> "The knowledge you gain here isn't just theory—it's the front-line reality that keeps our clients secure and productive."

### What's Next?

In **Chapter 15**, we'll cover **Printer Setup and Troubleshooting**—the essential knowledge you need for professional installation and problem-solving for your peripherals.

**Remember:** A well-configured network is the best security. Now that you've mastered connectivity, you're ready for the next level of security and networking.
