# task-2
# 📧 Phishing Email Analysis – Case Study

This project demonstrates a step-by-step forensic analysis of a **phishing email** to help raise awareness about common email-based threats and to showcase how email spoofing, header manipulation, and social engineering are used to deceive users.

## 📝 Overview

A suspicious email claiming to be from **Amazon Support** was analyzed using a structured checklist. The investigation covered spoof detection, email header analysis, and identification of phishing indicators in both the body content and technical metadata.


## 🧪 Analysis Steps

### ✅ Phishing Investigation Checklist:
1. **Obtained a phishing email sample**  
2. **Checked sender's email for spoofing** – `amaz0n-billing.com` is a lookalike domain  
3. **Analyzed email headers** – SPF, DKIM, and DMARC all failed authentication  
4. **Detected suspicious attachment** – `.zip` file likely contains malware  
5. **Identified threatening language** – e.g., “Account locked”, “Suspension in 24 hours”  
6. **Noted potential mismatched URL** – masked link behind "🔗 Verify Now"  
7. **Evaluated spelling/grammar** – clean grammar, but non-standard sign-off used  
8. **Summarized phishing traits** – including spoofed identity and urgency tactics

---


