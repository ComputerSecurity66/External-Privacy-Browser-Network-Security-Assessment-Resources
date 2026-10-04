# 🔐 Privacy & Security Resources

A collection of useful third-party web resources for **privacy awareness, browser fingerprinting assessment, IP exposure testing, and DNS/WebRTC leak detection**.

These resources can help users understand what information their browser and network connection may reveal to websites and online services.

---

## 🌐 Recommended Privacy & Security Websites

### 🕵️ Am I Unique?

**Am I Unique?** is a browser fingerprinting research and assessment website.

It allows users to examine characteristics of their browser and device that can contribute to browser fingerprinting, including information such as browser characteristics, operating system information, timezone, language, HTTP headers, screen properties, Canvas/WebGL information, and other browser attributes.

Useful for:

* Browser fingerprint assessment
* Understanding device uniqueness
* Privacy awareness
* Browser tracking research
* Learning about fingerprinting techniques
* Reviewing information exposed by a browser

🔗 Open AmIUnique Website

Third-Party Notice: AmIUnique is an independent third-party website. It is not developed, operated, or owned by this project.
---

### 🌐 IP/DNS Detect — IPLeak

**IPLeak** provides tools for examining information that may be exposed through a web connection.

Its testing pages can display information relating to:

* Public IP addresses
* WebRTC IP exposure
* DNS requests
* Torrent-address detection
* Browser-based geolocation
* Other browser/network information

The website specifically notes that websites and embedded services can see and collect certain connection and browser information.

Useful for:

* IP exposure checks
* DNS leak testing
* WebRTC leak testing
* VPN privacy verification
* Network privacy awareness
* Browser geolocation testing

🔗 Open IPLeak Website

Third-Party Notice: IPLeak is an independent third-party website. It is not developed, operated, or owned by this project.
---

# 🛡️ Why Use These Resources?

Modern websites can obtain information about visitors through normal web requests, browser APIs, JavaScript, network connections, and other mechanisms.

Privacy-testing websites can help users understand what their current configuration may reveal.

A practical assessment can include:

```text
Browser
   │
   ├──► Browser Fingerprint
   │         │
   │         └──► AmIUnique
   │
   └──► Network Information
             │
             ├──► Public IP
             ├──► WebRTC
             ├──► DNS
             └──► Geolocation
                       │
                       └──► IPLeak
```

---

# 🔍 Suggested Privacy Check

Before performing a privacy assessment, review:

### Browser Fingerprinting

Use AmIUnique to examine how identifiable or distinctive your browser configuration may appear.

### IP Address

Check whether the expected public IP address is being exposed.

### DNS

Check whether DNS requests appear to be going through the intended DNS provider, particularly when using a VPN.

### WebRTC

Check whether browser WebRTC behavior exposes network addresses that should remain private.

### Geolocation

Review whether browser-based location information is accessible to websites.

---

# ⚠️ Important Privacy Notice

These websites may collect or process information as part of their respective testing and research functions.

Before using any external privacy-testing website, review its:

* Privacy policy
* Terms of service
* Data-collection practices
* Cookie policy
* Research or diagnostic purposes

Do not assume that a privacy-testing website provides complete anonymity.

These tools are useful for **testing and awareness**, not as a guarantee of complete online privacy.

---

# 🚫 Third-Party Disclaimer

The websites referenced in this repository are independent third-party services.

This project:

* Does not own these websites
* Does not operate these websites
* Does not control their infrastructure
* Does not control their privacy policies
* Does not guarantee their availability
* Does not guarantee the accuracy of their results
* Is not affiliated with these services unless explicitly stated

All trademarks, names, and third-party services remain the property of their respective owners.

---

# 🔒 Security & Privacy

Use privacy-testing services only for legitimate security and privacy assessment.

Do not submit confidential information, private documents, credentials, authentication tokens, or other sensitive material to third-party websites unless you understand and accept the associated risks.

---

# 📚 External Resources

**AmIUnique**
Browser fingerprinting and privacy-awareness resource.

**IPLeak**
IP, DNS, WebRTC, torrent-address, and browser privacy testing resource.

---

## 🔒 Copyright

Copyright © 2026 VALOR. All Rights Reserved.
