# 📝 JINO – Jira Note Organizer

A lightweight, browser-based web application to manage Jira ticket highlights with structured notes, retailer tags, and use cases. JINO is ideal for QA professionals, analysts, or project managers who frequently work with Jira tickets and want to streamline note-taking without relying on spreadsheets or third-party tools.

![JINO Screenshot](./Files/jino-preview.png) <!-- Optional: Add a screenshot in the repo -->

---

## 🚀 Features

- ✅ Save Jira ticket details: Ticket ID, Custom Note, Retailer Name, and Use Case
- 🧠 Organize your keynotes for each ticket in one place
- 💾 Uses `localStorage` for instant browser-side saving (no backend required)
- 📝 Edit and delete notes dynamically
- 📄 Export saved notes to **PDF** for documentation or sharing
- 🎨 Sleek dark theme UI with responsive design
- ⚡ Fully client-side app – just open and use

---

## 📷 Preview

![Demo GIF](./Files/demo.gif) <!-- Add a GIF or screenshot of app functionality -->

---

## 📂 How to Use

1. Clone or download the repository
2. Open `index.html` in any modern web browser
3. Enter ticket details and click **Save Ticket**
4. Use the **Edit** or **Delete** buttons to manage your entries
5. Click **Export to PDF** *(coming soon or if implemented)* to download your notes

---

## 🧰 Tech Stack

- HTML5  
- CSS3  
- JavaScript (Vanilla)  
- LocalStorage API  
- [Optional] `jsPDF` or `html2pdf.js` for PDF export

---

## 📄 PDF Export

If you’ve implemented PDF export using `html2pdf.js` or `jsPDF`, you can describe it like this:

```javascript
// Example (inside save or render function)
html2pdf().from(document.getElementById("ticketList")).save("jino-notes.pdf");
