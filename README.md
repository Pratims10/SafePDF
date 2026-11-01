# SafePDF.in 🛡️

> **A 100% private, client-side document toolkit running entirely within your browser.**  
> *Unlock bank statements, resize IDs to exact KB limits, and bundle documents offline with zero server uploads.*

[![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg)](LICENSE)
[![Privacy: 100% On-Device](https://img.shields.io/badge/Privacy-100%25%20On--Device-10b981.svg)](#️-privacy-guarantee)
[![Zero Uploads](https://img.shields.io/badge/Network-Zero%20Server%20Uploads-blue.svg)](#️-running-locally--offline)

---

## ✨ Key Features

* **🔓 Secure PDF Unlocker**
  * Automatically tests standard Indian bank, broker, and tax statement password formulas (HDFC, ICICI, SBI, Axis, Kotak, Zerodha, Groww, AIS, Form 16, etc.).
  * Uses a single-worker, memory-safe decryption approach via **PDF.js** and **PDF-Lib** with zero false positives.
  * Real-time decrypted document preview and bulk `.zip` downloads.
* **🖼️ Precision Photo & Document Resizer**
  * Compress images (`.jpg`, `.jpeg`, `.png`, `.webp`) and scanned documents (`.pdf`) down to exact target KB limits (`10 KB` to `1000 KB` / `1 MB`).
  * One-click portal presets (`20 KB` Signature, `50 KB` Passport/PAN Photo, `200 KB` ID Card, `500 KB` / `1 MB` Document).
  * Optional diagonal protective watermarking (*"FOR VERIFICATION ONLY - DO NOT REUSE"*).
  * Instant re-sizing and live preview before downloading.
* **📄 Multi-PDF Merger**
  * Combine multiple monthly statements, receipts, or single-page scans into a single organized PDF file locally.
  * Live multi-page preview of the combined document before saving.
* **🔒 Absolute Offline Privacy**
  * Operates completely inside your browser memory with a 5-step offline verification tracker.
  * Works even with your Wi-Fi or mobile data switched off. **Your files never leave your device.**

---

## 🚀 Tech Stack

SafePDF.in is built as a lightweight, zero-dependency single-page application using modern web standards:

* **HTML5 & CSS Variables** – Native Light/Dark theme engine with zero runtime flicker.
* **Tailwind CSS** – Responsive layout and utility styling.
* **Vanilla JavaScript (ES6+)** – Memory-safe async/await processing and Web Worker lifecycle management.
* **[PDF.js](https://mozilla.github.io/pdf.js/)** – Client-side cryptographic password verification and canvas page rendering.
* **[PDF-Lib](https://pdf-lib.js.org/)** – Client-side PDF creation, page embedding, and document merging.
* **[JSZip](https://stuk.github.io/jszip/)** – Local in-memory `.zip` archive generation for batch downloads.

---

## 🛠️ Running Locally & Offline

Because SafePDF.in has zero backend servers or build steps, you can run it immediately on any machine:

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/safepdf.git](https://github.com/YOUR_USERNAME/safepdf.git)
   ```
2. Navigate into the project directory:
   ```bash
   cd safepdf
   ```
3. Open **`index.html`** directly in any modern web browser (Chrome, Brave, Edge, Firefox, Safari).
4. *(Optional)* Switch off your Wi-Fi or enable Airplane Mode after loading the page to verify 100% offline execution.

---

## 🔑 Supported Formats & Password Rules

SafePDF includes a built-in reference directory and automatic candidate generator covering standard institutional formats:

* **Indian Banks (Savings & Credit Cards):** HDFC, ICICI, SBI, Axis, Kotak Mahindra, IDFC FIRST, IndusInd, Bank of Baroda, PNB, Yes Bank, Canara, Union Bank, RBL, Federal, AU Small Finance, Standard Chartered, HSBC, American Express, Bank of India.
* **Stock Brokers & Mutual Fund CAS:** Zerodha (Console/Kite), Groww, Angel One, Upstox, INDmoney, Dhan, NSDL/CDSL Consolidated Account Statements (CAS), CAMS & KFintech.
* **Income Tax & Government Portals:** Annual Information Statement (AIS/TIS), ITR-V Acknowledgement, Form 16 (Part A & B), Form 26AS (TRACES), e-PAN (NSDL/UTIITSL), UIDAI e-ID, and Airtel/Jio/Vi postpaid bills.

---

## 🛡️ Privacy Guarantee

> SafePDF.in contains **no analytics trackers, no telemetry, and no server upload endpoints**. Every byte of your PDF or image is processed strictly inside your browser's local RAM and is permanently wiped the moment you click **🧹 Clear Memory** or close the browser tab.

---

## 👤 Author

Built by **Pratim**.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).