# 🛗 ElevatorWatch | Vigilancia de Elevadores

![Preview of ElevatorWatch demo](./preview.png)

ElevatorWatch is a resident-powered accountability tool designed to bridge the gap between building management claims and the lived reality of tenants. By crowdsourcing elevator status and tracking maintenance excuses, the app builds an irrefutable record for housing advocacy.

## ✨ Key Features

* **Bilingual First:** Fully localized for **Mexican Spanish**, ensuring the app is accessible to the community it serves.
* **Accountability Dashboard:** Live calculation of "Building Uptime" and tracking of management excuses (e.g., "Waiting for Parts").
* **Resident Verification:** Allows users to "Verify" when a repair is actually completed, catching discrepancies in management logs.
* **Multimedia Evidence:** Support for voice notes and photo/video uploads to provide timestamped proof of failures.
* **Legal Playbook:** An integrated Resident Action Guide that explains how to escalate data to 311 or local officials.

---

## 🚀 User Story Walkthrough

To demonstrate the power of ElevatorWatch, follow this standard user journey:

### 1. The Dashboard (Status Quo)
Upon entering, the resident sees the **Building Status**. All elevators are listed with high-contrast color coding. 
* **Action:** Toggle the language button (ESPAÑOL) to see the idiomatic translation (e.g., "Elevador" vs "Ascensor").

### 2. Reporting a Failure
A resident notices **Elevator B** is making a grinding noise and isn't moving.
* **Action:** Click `+ Report a Problem` -> Select `Elevator B` -> Select `Out of Service`.
* **Accountability:** The resident selects "Waiting on parts" from the management excuse dropdown and attaches a photo of the "Out of Order" sign.

### 3. Impact Analysis
Once submitted, the app returns to the dashboard.
* **Visual Change:** Elevator B is now **RED**. The **History Log** shows the report with a 📸 icon.
* **Data Capture:** The "Days Down" counter increments automatically, and the 30-Day Performance grade reflects the new downtime.

### 4. Closing the Loop (Verification)
Hours later, a neighbor sees the elevator is back in service.
* **Action:** Click `✅ It's working now` on the Elevator B card.
* **Result:** The status flips back to **GREEN**. The app logs the exact time of repair, creating a data point to compare against management's official maintenance records.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript (ES6+)
* **Design Language:** Bootstrap 5.3 (Mobile-First, High Accessibility)
* **Localization:** Dynamic JSON-based translation for Mexican Spanish
* **Icons:** Emoji-based (High compatibility, low payload)