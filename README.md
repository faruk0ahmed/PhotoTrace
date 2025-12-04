# 📸 PhotoTrace

**Advanced Image Metadata, Forensic Analysis & Steganography Tool**  
*Developed by [NexloCode]*

PhotoTrace is a secure, client-side web application designed to extract hidden EXIF data from images, analyze potential editing signatures (Forensics), and perform Steganography (hiding secret messages inside images with password protection).

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Technology](https://img.shields.io/badge/built%20with-HTML5%20%7C%20JS-orange)

---

## 🚀 Features

### 1. 🔍 Metadata Extraction (EXIF)
Extracts deep technical details from digital photos:
- **Device Info:** Camera Brand, Model, Resolution.
- **Camera Settings:** ISO, Shutter Speed, Aperture, Flash usage, Focal Length.
- **Timestamp:** Original date and time the photo was taken.

### 2. 🕵️‍♂️ Forensic Analysis
Detects if an image has been manipulated:
- Checks software signatures (e.g., Adobe Photoshop, Lightroom, GIMP).
- Displays a warning if the image is likely edited vs. original.

### 3. 📍 Geolocation Tracking
- Extracts GPS coordinates (Latitude & Longitude) from the image.
- **One-Click Map:** Instantly view the exact location on Google Maps.

### 4. 🔐 Steganography (Secret Messages)
Hide and retrieve encrypted messages inside images:
- **Encryption:** Uses password-based XOR encryption to hide text within image pixels.
- **Privacy:** Only someone with the specific password can reveal the hidden message.
- **Format Support:** Auto-converts to `.png` to prevent data loss during compression.

### 5. 📱 Modern UI/UX
- **Glassmorphism Design:** Modern, translucent aesthetic.
- **Fully Responsive:** Works perfectly on Desktop, Tablet, and Mobile devices.
- **Dark Mode:** Eye-friendly dark interface.

---

## 🛠️ Technology Stack

- **Frontend:** HTML5, CSS3 (Custom Properties, Flexbox/Grid).
- **Scripting:** Vanilla JavaScript (ES6+).
- **Libraries:** `exif-js` (CDN) for metadata parsing.
- **Technique:** LSB (Least Significant Bit) manipulation for Steganography.

---

## 📖 How to Use

### 📥 Installation
No server installation required!
1. Clone or download this repository.
2. Open `index.html` in any modern web browser (Chrome, Edge, Firefox).

### 🕵️ Using Metadata & Forensics
1. Click the upload area or drag & drop an image (JPG/JPEG recommended for EXIF).
2. Scroll down to view Device Info, Settings, and Location data.

### 🤫 Using Secret Messages (Steganography)
**To Hide a Message:**
1. Upload any image.
2. Scroll to the **"Secret Message"** section.
3. Enter a **Password** and your **Message**.
4. Click **"Save Message in Image"**.
5. The image will download as a `.png` file. *Keep this file safe!*

**To Read a Message:**
1. Refresh the page.
2. Upload the **downloaded PNG** image (the one with the hidden message).
3. Go to the **"Read Message"** tab.
4. Enter the **same password** you used to lock it.
5. Click **"Reveal Message"**.

---

## ⚠️ Privacy Note
**PhotoTrace runs 100% on your browser.** No images are uploaded to any external server. Your photos and secret messages remain completely private on your device.

---

## 👨‍💻 Developer Info

- **Developer:** NexloCode
- **Project Name:** PhotoTrace
- **Year:** 2025

---
*Feel free to star ⭐ this repository if you find it useful!*
