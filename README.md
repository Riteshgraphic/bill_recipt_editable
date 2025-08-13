# 🧾 Editable Hotel Receipt

<img width="364" height="589" alt="image" src="https://github.com/user-attachments/assets/8c7b8cc7-2b5f-465a-aa55-4e84f563eb7c" />


A simple **editable hotel receipt generator** built with **HTML, CSS, and JavaScript**.  
This project allows users to **edit** receipt details, **add items**, **calculate totals automatically**, and **print** the receipt directly from the browser.  
Works entirely **offline** and requires **no backend**.

---

## ✨ Features
- 🖊 **Editable Fields** – Click and edit hotel name, guest details, items, and prices.
- 🔢 **Auto Calculations** – Subtotal, GST (9%), SGST (9%), and Grand Total update in real-time.
- ➕ **Add Items** – Add new line items with editable names and amounts.
- 🖨 **Print Ready** – One-click print option for clean, professional receipts.
- 📱 **Responsive** – Looks neat on desktop and mobile.

---

---

## 🚀 How to Use
1. **Download & Open**
   - Save `editable-receipt.html` to your computer.
   - Open it in a web browser.

2. **Edit Receipt**
   - Click on any text to edit it directly.
   - Change amounts in the "Amount" column.

3. **Add Items**
   - Click the **"+ Add Item"** button.
   - Enter the item name and amount.

4. **Print Receipt**
   - Click **"Print Receipt"** to open the browser's print dialog.
   - Print or save as PDF.

---

## 📜 Code Breakdown
### **HTML**
- `contenteditable="true"` → Makes text fields editable.
- `.amount` → Class for all price fields included in calculations.

### **CSS**
- Minimal styling for a clean receipt look.
- `.line` → Dashed dividers between sections.

### **JavaScript**
- `calculateTotals()` → Calculates subtotal, GST, SGST, and grand total.
- `addItem()` → Dynamically adds new editable rows.
- `printReceipt()` → Formats and sends the receipt to the printer.

---

## 📌 Notes
- Client-side only – no server required.
- Works offline in any modern browser.
- Not intended for official billing – for demo or educational use.

---

## 📄 License
This project is licensed under the **MIT License** – you are free to use, modify, and distribute it.

---
