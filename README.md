# ⚡ Dreamina High-Res Asset Downloader

A Chrome Extension that enables **one-click bulk downloading of High-Resolution assets** from CapCut/Dreamina, bypassing the low-res previews.

![Icon](icon.png)

## 🚀 Features

*   **⚡ Native Speed:** Uses a smart network interceptor that imposes **zero lag** on scrolling.
*   **📸 High-Res Quality:** Captures the original highets resolution source files (filtering out 600px thumbnails).
*   **🛡️ Smart Filtering:** Automatically ignores sidebar/recommended junk images.
*   **🖱️ Batch Selection:** Select All / Select None controls for bulk downloading.

## 🛠️ Installation

1.  **Clone or Download** this repository.
2.  Open Chrome and go to `chrome://extensions`.
3.  Enable **"Developer mode"** (top right).
4.  Click **"Load unpacked"**.
5.  Select the folder containing this `manifest.json`.

## 📖 How to Use

1.  Navigate to your CapCut/Dreamina assets page.
2.  Scroll down to load your images (the extension captures them silently in the background).
3.  Open the extension popup.
4.  Click **"QUICK SCAN"** ⚡.
5.  Select the images you want (or **SELECT ALL**).
6.  Click **"DOWNLOAD FULL QUALITY"**.

## 🔧 Technical Details

*   **Manifest V3:** Fully compliant with modern Chrome security standards.
*   **Main World Injection:** Uses `world: "MAIN"` to lazily intercept specific API calls (`get_local_item_list`) while strictly ignoring binary data to preserve performance.

## 📄 License
MIT

<img width="1919" height="908" alt="dreamina_downloader_01" src="https://github.com/user-attachments/assets/3d828620-86d3-4360-a331-7ef4f30fcf68" />
<img width="1919" height="910" alt="dreamina_downloader_02" src="https://github.com/user-attachments/assets/a38d02ee-7756-45e8-a6f3-f9d7398d27f9" />
<img width="383" height="505" alt="dreamina_downloader_03" src="https://github.com/user-attachments/assets/26753842-cfca-4967-81c8-8ea11df6f6e8" />
<img width="397" height="607" alt="dreamina_downloader_04" src="https://github.com/user-attachments/assets/171efa74-d055-4dce-a975-db50e901fa5c" />


