# JustReceipt Pro

**JustReceipt Pro** is a modern, lightweight, open-source web application that allows small businesses to generate professional bill receipts for their customers — complete with PDF export, QR codes, unique IDs, and barcode tokens. It's a simple solution for creating instant receipts and tracking basic income details.

---

## ✨ Features

- 🧾 Generate PDF receipts quickly and easily.
- 🔐 Unique Receipt ID and Secret Token on every receipt.
- 📱 Scannable **QR Code** and **Barcode** for each receipt.
- 📊 Simple built-in dashboard to track total income and receipts.
- 🌐 Works entirely in the browser — no backend required.
- 💻 Can be hosted on any web server or run locally.

---

## 🚀 Getting Started

### 1. Clone or Download the Project

```bash
git clone https://github.com/your-username/justreceipt-pro.git
cd justreceipt-pro
```

Or [Download as ZIP](https://github.com/your-username/justreceipt-pro/archive/refs/heads/main.zip)

### 2. Open in Browser

Simply open the `index.html` file in your browser:

```bash
# Local preview (optional)
open index.html
```

> ✅ For persistent data, you must host the site locally or online. Opening the file directly does not save receipts permanently.

---

## 📦 Technologies Used

- **HTML / CSS / JavaScript**
- [`jsPDF`](https://github.com/parallax/jsPDF) – Exporting receipts to PDF
- [`html2canvas`](https://html2canvas.hertzen.com/) – Rendering HTML to image for PDF
- [`qrious`](https://github.com/neocotic/qrious) – QR Code generation
- [`JsBarcode`](https://github.com/lindell/JsBarcode) – Barcode generation

---

## 🔧 Project Status

- ✅ Receipt generation is functional
- ✅ Dashboard shows total income and generated receipts
- ❌ No login/authentication yet
- ❌ Receipts stored only in browser localStorage (data will be lost if host is down or storage is cleared)
- 🔜 Planned updates:
  - Add secure login system
  - Desktop version (via Electron or similar)
  - Cloud or encrypted local storage
  - Private/public hosting options

---

## 🧠 Use Case

When a customer purchases something, a receipt is generated with a secret token, receipt ID, QR code, and barcode. For refunds or verification, the customer can show the receipt or scan the code to prove the purchase.

---

## 🔓 License

This project is licensed under the **MIT License**.

You are free to fork, modify, or use this code for any purpose, including commercial use. Attribution is not required.