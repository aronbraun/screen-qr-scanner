# QR & Barcode Scanner 🔍

A powerful, browser-based QR code and barcode scanner that allows you to capture any area of your screen and instantly decode QR codes or barcodes within that area.

## ✨ Features

- **Direct Area Selection**: Select any area directly on your screen without taking a full screenshot first
- **Cross-Tab Functionality**: Maintains selection overlay even when switching between browser tabs
- **Real-time QR Code Detection**: Uses the jsQR library for accurate QR code scanning
- **Responsive Design**: Modern, mobile-friendly interface with smooth animations
- **Browser Compatibility**: Works with modern browsers supporting Screen Capture API
- **Keyboard Shortcuts**: 
  - `ESC` to cancel area selection
  - `Enter` to confirm selected area
- **Fullscreen Mode**: Automatically requests fullscreen for better overlay visibility

## 🚀 How to Use

1. **Open the Application**: Simply open `index.html` in any modern web browser
2. **Select Screen Area**: Click "Select Screen Area" to start the selection mode
3. **Choose Your Area**: Click and drag to select the area containing the QR code or barcode
4. **Confirm Selection**: Click "Confirm" or press `Enter` to confirm your selection
5. **Capture & Scan**: Click "Capture & Scan" to capture the selected area and decode any codes
6. **View Results**: The decoded text will appear in the results section

## 🌐 Browser Support

- **Chrome** (version 72+)
- **Firefox** (version 66+)
- **Edge** (version 79+)
- **Safari** (with limitations on screen capture)

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript**: No build process required
- **External Dependencies**: 
  - jsQR library (loaded from CDN)
- **APIs Used**:
  - Screen Capture API (`getDisplayMedia`)
  - Canvas API for image processing
  - Fullscreen API for enhanced overlay experience

## 📱 Usage Tips

- Ensure the QR code or barcode is clearly visible and not blurry
- Select an area that closely crops around the code for better detection
- The application works best with high-contrast codes
- For best results, avoid selecting areas with complex backgrounds

## 🔒 Privacy & Security

- **No Data Collection**: All processing happens locally in your browser
- **No Network Requests**: Except for loading the jsQR library from CDN
- **Secure Screen Capture**: Uses browser's built-in screen capture permissions

## 🎯 Use Cases

- Scanning QR codes from websites, documents, or applications
- Reading barcodes from product images or catalogs
- Extracting text from QR codes in presentations or videos
- Quick access to URLs, contact information, or other encoded data

## 🤖 AI Development

This project was created using **Junie**, an AI assistant developed by JetBrains, on August 14, 2025. The application was built through iterative development and enhancement based on user requirements and feedback.

## 📄 License

This project is open source and available under the MIT License.

---

*Created with ❤️ by Junie AI Assistant - August 14, 2025*
