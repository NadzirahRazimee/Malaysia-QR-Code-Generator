# Malaysia-QR-Code-Generator
Malaysia QR Code Generator/Scanner is a bilingual web app with a Malaysian-themed design that allows users to easily generate and scan QR codes. It includes quick presets for local use cases like Malaysian phone numbers, websites, WiFi, and locations, and supports real-time scanning via camera or image upload.

## Features Overview

### 🇲🇾 Malaysian-Themed Design
- Red and gold gradient (inspired by the Malaysian flag)
- Malaysian flag emoji for styling
- Bilingual interface (English / Bahasa Melayu)
- Malaysia-specific presets for common use cases

### QR Code Generator
- **Multiple Types:** Text, URL, Phone, SMS, Email, WiFi, Contact Cards, Location
- **Malaysia Presets:** Predefined buttons for common Malaysian formats
- **Custom Styling:** Borders, shadows, and professional layout
- **Downloadable:** Save generated QR codes as PNG

### QR Code Scanner
- **Live Camera Scanning:** Uses device camera for real-time QR detection
- **Image Upload:** Scan QR codes from uploaded gallery images
- **Auto-detection:** Instantly shows results when a QR is found

---

## Step-by-Step Implementation

### Step 1: HTML Structure
- Header with Malaysian branding
- Tab-based navigation (Generator / Scanner)
- Dynamic form fields based on QR type
- Video element for live camera scanning
- Result display area for output

### Step 2: CSS Styling
- Malaysian color palette (red & gold gradient)
- Mobile-first responsive layout
- Smooth UI transitions & animations
- Button hover effects and modern UI elements

### Step 3: JavaScript Functionality

#### QR Code Generation
- Built with `qrcode.js`
- Auto form rendering based on type
- Supports formats like WiFi, vCard, and more
- Canvas-based QR image generation

#### QR Code Scanning
- Powered by `jsQR`
- Camera integration via `getUserMedia()`
- File upload handled by `FileReader`
- Real-time scanning loop with auto feedback

---

## How to Use

### For QR Code Generation:
1. Select QR type from dropdown
2. Use preset buttons for Malaysian use cases
3. Fill in the required form fields
4. Click **"Generate QR Code"**
5. Download the PNG file

### For QR Code Scanning:
1. Switch to the **Scanner** tab
2. Click **"Start Camera"** to scan in real time
3. Position the QR code inside the viewfinder
4. Or upload an image file with a QR code
5. Wait for automatic detection and result display

---

## Technical Features
- **Libraries:** `qrcode.js`, `jsQR`
- **Camera:** `getUserMedia` API (rear camera support)
- **Image Handling:** `FileReader` API for uploads
- **Canvas:** Used for both generation and decoding
- **Responsive Design:** Works across desktop and mobile devices
- **Error Handling:** Displays helpful error messages for invalid input or permissions

---
## Quick Start Instructions

1. Set Up Project Structure
Open the folder in **VS Code**.

2. Install Dependencies
## Backend
```bash
cd backend
npm install

3. Run the application
npm run dev
npm start

---

## Author
**Nadzirah Razimee**
