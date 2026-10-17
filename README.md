# Privacy Policy for Brainrot

**Last updated:** October 17, 2026

**Brainrot** ("we", "our", or "us") is dedicated to protecting your privacy and digital wellbeing. Brainrot is built with a **100% local-first, offline architecture**. We do not collect, transmit, sell, or share any personal data.

---

### 1. Data Collection & Storage
- **100% On-Device Storage:** All statistics (reel counts, watch durations, dopamine velocity metrics, and user preferences) are stored locally on your device in an encrypted SQLite database (`brainrot.db`).
- **No Cloud Servers:** Brainrot does not operate external servers, databases, or cloud accounts.
- **No Personal Identifiers:** We do not collect names, email addresses, phone numbers, location data, or device hardware IDs.

---

### 2. Android Accessibility Service API Disclosure (Mandatory)
Brainrot utilizes Android's **AccessibilityService API** strictly for the following core purpose:
- **Core Functionality:** To detect when supported video applications (Instagram and YouTube) are actively playing Reels or Shorts on screen.
- **Scroll & Time Tracking:** To measure time spent per reel and tally daily consumption against your self-imposed limits.
- **Limitation & Enforcement:** When your daily scroll limit is reached, the service assists in minimizing doomscrolling by returning to the home screen or displaying the in-app break challenge.

#### What the Accessibility Service DOES NOT do:
- Brainrot **never** reads, intercepts, or logs personal messages, chats, comments, passwords, keystrokes, or banking information.
- Brainrot **never** transmits screen contents or accessibility events over the network or to third parties.
- All detection is performed in real-time memory and immediately discarded.

---

### 3. Display Over Other Apps (Overlay Permission)
Brainrot requests the `SYSTEM_ALERT_WINDOW` permission to display an optional floating pill counter while you scroll reels. This overlay shows only your live count and daily limit. It does not collect any data.

---

### 4. Children’s Privacy
Brainrot does not knowingly collect any personally identifiable information from children under 13.

---

### 5. Changes to This Privacy Policy
Any updates to this policy will be reflected on this page with a revised date.

---

### 6. Contact Us
If you have questions about this Privacy Policy, you can reach out via GitHub or at:
- **Project Repository:** https://github.com/shivam108ku/Your-counts
