# Privacy Policy for Promptly

**Effective Date:** February 10, 2025

## Introduction

Thank you for using Promptly ("the App"). This Privacy Policy explains how we collect, use, disclose, and retain information when you use the App. We are committed to protecting your privacy and ensuring your data is secure. By using the App, you agree to the practices described in this Privacy Policy.

## 1. Data Collection

### Screen Capture Data

- **What We Collect:**  
  When you invoke the screen capture feature, the App uses macOS’s built-in screenshot mechanism (via `/usr/sbin/screencapture`) to capture a single image file (PNG) of a user-selected portion of your screen. **Importantly, the App does not record video, audio, or any additional background data.**

- **How We Collect:**  
  The screenshot is generated only upon your explicit request, and the capture is a one-time action initiated by the user. There is no continuous or background recording.

- **User-Initiated Action:**  
  Screen capture is performed exclusively when you explicitly select and trigger the capture. No additional data (video, audio, or other) is recorded at any time.

## 2. Data Usage

- **OCR Processing:**  
  The captured screenshot is processed locally on your device using Apple’s Vision framework for Optical Character Recognition (OCR) to extract text. The extracted text is then used to power various AI-driven actions, such as summarization, translation, and reformatting only after your explicit request by selecting a prompt.

- **Temporary Storage:**  
  The screenshot image is stored temporarily in your system’s temporary directory (via `NSTemporaryDirectory()`) solely to perform OCR. Once the text is extracted, the image is permanently deleted.

- **Local Processing:**  
  All processing is performed locally on your device. No screenshot image or extracted text is transmitted to external servers or shared with third parties without your explicit consent.

## 3. Data Sharing and Disclosure

- **No Third-Party Sharing:**  
  We do not share, sell, or distribute any screenshot data or extracted text with third parties. All data processing remains local to your device.

## 4. Data Retention

- **Ephemeral Data:**  
  The screenshot image is retained only temporarily for the purpose of performing OCR. After extraction, the image is deleted and is not stored permanently.

## 5. Security

- **Data Protection Measures:**  
  We implement appropriate technical and organizational measures to safeguard your data from unauthorized access, alteration, disclosure, or destruction. Since all processing occurs on your device, your data remains under your control and is not exposed to external network-related vulnerabilities.

## 6. User Rights

- **Control Over Your Data:**  
  As the App does not permanently store your data, you retain full control over it. If you have any questions or require further details regarding our data handling practices, please contact us using the information provided below.

## 7. Changes to This Privacy Policy

We may update this Privacy Policy occasionally. Any changes will be communicated by updating this document within the App and on our website. We encourage you to review this Privacy Policy periodically to stay informed about our practices.

## 8. Contact Us

If you have any questions or concerns about this Privacy Policy or our data practices, please contact us at:

**Email:** [promptlyforai@gmail.com](mailto:promptlyforai@gmail.com)
