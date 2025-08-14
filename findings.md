# Task 7 – Identify and Remove Suspicious Browser Extensions

## Browser: Brave (Windows)

---

## Initial Extensions Found
1. **Google Docs Offline**  
   - **Developer**: Google  
   - **Permissions**: Edit, create, and view documents offline.  
   - **Risk Assessment**: ✅ Safe — official Google extension, widely used and trusted.

2. **Microsoft Power Automate**  
   - **Developer**: Microsoft  
   - **Permissions**: Enables web automation tasks; works with Power Automate desktop.  
   - **Store Rating**: **2.0 / 5 stars** (147 reviews)  
   - **Risk Assessment**: ⚠️ Potentially concerning — although it is from Microsoft, many users reported suspicious installation behavior.

---

## User Review Highlights (Microsoft Power Automate)
- **“bro what is this and why did it install randomly”** – Apr 18, 2025  
- **“Think I might have a virus that installed this”** – Mar 19, 2025  
- **“Why it tried to install? … red flag”** – Feb 24, 2025  
- **Positive Review:** “Very useful and intuitive automation tool… allows the Windows app to perform web automation functions” – Apr 13, 2025

---

## Actions Taken
- Verified both extensions' developers (Google & Microsoft).
- **Microsoft Power Automate** was **disabled** since:
  - It is not actively used.
  - Poor user ratings and multiple reports of unexpected installation raise security concerns.
- **Google Docs Offline** was kept active due to its legitimate and frequent use.

---

## After Cleanup
- Extensions active: **1** (Google Docs Offline)
- Extensions disabled: **1** (Microsoft Power Automate)
- Browser security risk: Reduced

---

## Conclusion
While no obviously malicious extensions were found, disabling unused extensions with poor ratings and suspicious user reports is a good security practice. Even official extensions should be periodically reviewed for changes in permissions or unusual behavior.

---

## Screenshot Reference
- [`extensions_list.png`](screenshots/extensions_list.png) — initial list of installed extensions  
- [`Microsoft_Power_Automate.png`](screenshots/Microsoft_Power_Automate.png) — user reviews from Chrome Web Store
