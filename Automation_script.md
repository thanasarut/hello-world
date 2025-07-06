# 🤖 Automation Script Template: Notion → Google Sheets via Zapier

## 📦 Overview

This automation script outlines how to synchronize entries from your Notion meditation log into Google Sheets using Zapier.

---

## 🔄 Zapier Setup Steps

### Trigger: Notion
- **App**: Notion
- **Event**: New Database Item
- **Database**: Mindfulness Log (from Notion Template)

### Action: Google Sheets
- **App**: Google Sheets
- **Event**: Create Spreadsheet Row
- **Spreadsheet**: mindfulness_tracker.xlsx
- **Worksheet**: Sheet1
- **Mapped Fields**:
  - `Date` → Date
  - `Meditation Time` → Meditation Time
  - `Focus Score (1-5)` → Focus Score (1-5)
  - `Mind Wanders (count)` → Mind Wanders (count)
  - `Notes` → Notes

---

## 🧠 Tips

- ✅ **Filter drafts**: Use Zapier's filter to only send entries that are marked complete.
- 🛠️ **Formatter (optional)**: Format timestamps or numbers before sending to Sheets.
- 🔁 **Bi-directional sync?**: Use “Update Spreadsheet Row” if you want edits from Notion to reflect in Sheets.
- 📧 **Weekly Digest**: Add "Email by Zapier" to send a summary every 7 days.
- 🚨 **Error handling**: Enable auto-skip on Zap error fallback.

---

## ✅ Expected Result

Every time you create a new log entry in Notion, it will automatically appear in your Google Sheet with the correct columns, ready for analysis and graphing.

---

Happy automating! 🧘‍♂️📈🤖