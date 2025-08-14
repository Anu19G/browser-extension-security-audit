# Browser Extension Security Audit


## 🎯 Objectives
- Learn to spot and evaluate potentially harmful browser extensions.
- Remove or disable risky extensions without breaking legitimate workflows.
- Apply browser security best practices to prevent future threats.
- Demonstrate initiative by using **advanced security tools**.

---

## 🛠 Tools Used
**Given Tools:**
- Google Chrome (Windows)
- Mozilla Firefox ESR (Kali Linux)

**Additional Tools for Extended Analysis:**
- [CRXcavator](https://crxcavator.io/) – Automated Chrome extension security scanner.
- [Extension Source Viewer](https://chrome.google.com/webstore/detail/view-chrome-extension-so/) – View extension code before installing.

---

## 📋 Process & Steps
### Step 1 — Create a Baseline Inventory
- Listed all installed extensions with name, version, permissions, source, and ID.
- Screenshots captured for **before-removal** state.

### Step 2 — Review Extensions for Risk
- Checked permissions scope, source authenticity, developer reputation, and necessity.
- Searched for known security issues.
- Flagged each extension as ✅ Safe, ⚠ Medium Risk, or 🚨 High Risk.

### Step 3 — Safe Removal / Disabling
- Used CRXcavator & Extension Source Viewer to verify suspicion.
- Removed or disabled flagged extensions.
- Cleared browser cache and verified removal.

### Step 4 — Preventive Best Practices
- Limited number of active extensions.
- Checked permissions before installation.
- Used only official extension sources.
- Scheduled monthly extension audits.

### Step 5 — Final Outcome
- All browsers left with only **safe, essential extensions**.
- Delivered security recommendations for long-term safety.

---

## 📊 Risk Assessment Summary

| Browser | Extension Name | Risk Level | Summary |
|---|---|---|---|
| Chrome | Google Docs Offline | ✅ Safe | Official Google extension; site-specific permissions. |
| Chrome | Grammarly | ⚠ Medium Risk | Well-known; broad permissions to all sites & browsing history. |
| Chrome | Merlin | ⚠ Medium–High Risk | Lesser-known; broad permissions on all sites. |
| Firefox | Dark Reader | ✅ Safe | Popular; permissions match purpose. |
| Firefox | Consent-O-Matic | ✅ Safe | University-developed; focused functionality. |
| Firefox | Pink Dark Stars theme | ✅ Safe | Theme only, no data access. |
| Firefox | OneTab | ⚠ Medium Risk | Requires broad tab management permissions. |
| Firefox | LeechBlock NG | ✅ Safe | Trusted productivity extension. |

---

## ✅ Final Deliverables
- **PDF Report**: `Suspicious_Browser_Extension_Audit_and_Removal_Report.pdf`
- **Risk Assessment Table** 
- **Preventive Best Practices Documentation**

---

## 📚 References
- [Google Chrome Extension Documentation](https://developer.chrome.com/docs/extensions/)
- [Mozilla Firefox Add-ons Security](https://extensionworkshop.com/documentation/publish/add-on-security/)
- CRXcavator – https://crxcavator.io/
- Extension Source Viewer – https://chrome.google.com/webstore/detail/view-chrome-extension-so/

