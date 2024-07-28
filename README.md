# QR Chunker

QR Chunker is a tool to split a long text into a sequence of QR codes to be sent or printed, and a wizard to manually scan printed QRs (or pictures from the gallery), one by one, and re-create the long text.

## Features

- **Generate QR Codes:** Split long text into chunks and generate QR codes for each chunk. You can define the chunk length between **500** and **2950** characters (default is **2000** characters). Above 2950 characters there are tech limitations.
- **Save and Share QR Codes:** Save individual QR codes as PNG files or share them directly from your mobile device.
- **Decode QR Codes:** Upload an image or capture one using your webcam to decode QR codes. Append decoded text to the existing text or clear the current scan and total text.
- **Download All QR Codes:** Download all generated QR codes in sequence automatically.

## Usage Guide

### Generate QR Codes

1. **Enter Text:**
   - Paste or type your long text into the textarea provided.

2. **Set Chunk Length:**
   - Define the chunk length using the input box (minimum 500, maximum 2950, default 2000).

3. **Generate QRs:**
   - Click the "Generate QRs" button to split the text into chunks and generate QR codes. Each generated QR code will be displayed as a small preview.

4. **Save or Share QR Codes:**
   - Each QR code preview has "Save" and "Share" buttons. Click "Save" to download the QR code as a PNG file, or "Share" to share it directly from your mobile device.

5. **Download All QR Codes:**
   - After generating the QR codes, a "Download All" button will appear. Click this button to download all generated QR codes sequentially.

### Decode QR Codes

1. **Upload an Image or Capture from Webcam:**
   - Use the "Choose File" button to upload an image containing a QR code, or click "Open Webcam" to capture an image using your webcam.

2. **Capture Image:**
   - If using the webcam, click the "Capture" button to take a picture of the QR code.

3. **Decode QR Code:**
   - Click the "Decode" button to read the QR code from the uploaded or captured image. The decoded text will appear in the "Current Scan" textarea, and the filename will be added to the list of scanned files.

4. **Append Decoded Text:**
   - Click the "Next" button to append the decoded text from "Current Scan" to the "Total Text" textarea.

5. **Clear Text:**
   - Use the "Clear" button to clear the "Current Scan" textarea, and the "Clear All" button to clear both the "Current Scan" and "Total Text" textareas and the list of scanned files.

6. **Copy Total Text:**
   - Click the "Copy" button to copy the entire text from the "Total Text" textarea to your clipboard.

## Open the App

You can open the app by clicking on the following link: [QR Chunker on GitHub Pages](https://n3me5is-git.github.io/qr-chunker/)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
