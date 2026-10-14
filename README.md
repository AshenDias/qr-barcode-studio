# Instant QR & Barcode Studio ⚡

A high-performance, 100% client-side utility workspace for generating, customizing, bulk processing, and scanning QR codes and 1D barcodes with zero backend dependencies.

[![Live Demo](https://img.shields.io/badge/Live_Demo-GitHub_Pages-6366f1?style=for-the-badge&logo=github)](https://ashendias.github.io/qr-barcode-studio/)
[![Zero Backend](https://img.shields.io/badge/Architecture-100%25_Client--Side-10b981?style=for-the-badge)](https://ashendias.github.io/qr-barcode-studio/)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

---

## 🌐 Live Website

Access the live web app anytime at:  
👉 **[https://ashendias.github.io/qr-barcode-studio/](https://ashendias.github.io/qr-barcode-studio/)**

---

## ✨ Features

### 1. 📱 QR Code Studio
- **Multiple Payload Types**:
  - **URL / Website**: Quick protocol auto-formatting
  - **Plain Text**: Dynamic character counter
  - **Wi-Fi Setup**: Network SSID, Password, Encryption (WPA/WPA2/WPA3, WEP, None), Hidden Network support
  - **vCard 3.0**: Digital business contact cards
  - **Direct WhatsApp**: Prefilled message generation
  - **Email**: Pre-addressed mailto links with subject & body
- **Custom Styling**:
  - Custom foreground and background color pickers
  - Transparent background toggle
  - Resolution slider (128px to 1024px)
  - Error correction levels: Level L (7%), M (15%), Q (25%), and Level H (30%)
  - Center logo & icon overlay (Upload custom logo or pick built-in badges)
- **Export Options**:
  - High-resolution PNG download
  - Crisp Vector SVG download
  - One-click copy image to clipboard

### 2. 📊 Barcode Studio
- **Supported 1D Symbologies**:
  - **CODE128**: Universal alphanumeric
  - **EAN-13 & EAN-8**: International retail
  - **UPC-A**: North American retail
  - **CODE39**: Industrial and defense
  - **ITF-14**: Logistics and packaging
  - **MSI / Plessey**: Inventory
  - **Pharmacode**: Pharmaceutical tracking
- **Customization**:
  - Bar width and height scaling
  - Human-readable text display toggle & font size control
  - Custom line and background colors
  - Quiet zone margin slider
- **Export**:
  - High-DPI PNG download
  - Vector SVG download
  - Copy image to clipboard

### 3. 📦 Bulk Batch Generator
- Generate dozens or hundreds of codes at once from line-separated text or CSV data.
- Switch between QR Codes and multiple Barcode formats.
- Real-time generation progress bar and live preview gallery.
- Automated ZIP file bundling powered by `JSZip` including an automated `manifest.csv` index.

### 4. 📷 Scanner & Local History
- **Live Camera Scanner**: Scan QR codes and barcodes in real time using your phone or laptop webcam with animated scanning reticle.
- **Synthesizer Beep**: Built-in audio beep confirmation using Web Audio API (zero audio files needed).
- **File Scanner**: Drag & drop or upload screenshots/photos to decode instantly.
- **Local History**: Saves generated and scanned codes directly to browser `localStorage` with search, filter, and reload capabilities.

---

## 🛠️ Tech Stack & Libraries

- **Tailwind CSS** (Modern glassmorphic dark/light UI)
- **Lucide Icons** (Vector UI icons)
- **QRCode.js** (Vector matrix generation)
- **JsBarcode** (1D barcode symbology rendering)
- **JSZip** (Client-side ZIP archive creation)
- **Html5-Qrcode** (Webcam video stream scanner and image decoder)

---

## 🔒 Privacy & Security

- **100% Client-Side**: All QR codes, barcodes, and camera frames are processed entirely inside your local browser.
- **Zero Tracking**: No data is sent to any external server or third-party tracking service.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
