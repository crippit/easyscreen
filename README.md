# **EasyScreen Studio**

EasyScreen Studio is a lightweight, browser-based tool designed to help developers create professional-looking screenshots for the Apple App Store. It automatically wraps your raw screenshots in high-quality device frames, adds marketing text, and exports them at the exact resolutions required by Apple.

## **🚀 Features**

* **Device Framing**: Automatically wraps screenshots in modern iPhone (Pro style) and iPad frames.  
* **Smart Resizing**: Two modes to handle images:  
  * **Fill Screen**: Crops the image to fill the device screen.  
  * **Fit Image**: Ensures the entire image is visible (letterboxed).  
* **App Store Ready Exports**: Supports all major required dimensions:  
  * 6.9" (iPhone 16 Pro Max)  
  * 6.7" (iPhone 15 Pro Max & 14 Pro Max)  
  * 6.5" (iPhone 11 Pro Max)  
  * 5.5" (iPhone 8 Plus)  
  * 12.9" (iPad Pro)  
* **Customization**:  
  * Add **Titles** and **Subtitles** with custom colors.  
  * Change background to **Solid** colors or beautiful **Gradients**.  
  * Adjust vertical positioning of the device.  
* **Privacy Focused**: All processing happens locally in your browser. No images are uploaded to a server.

## **🛠️ Tech Stack**

* **React 18**: UI and state management.  
* **HTML5 Canvas**: High-performance image rendering and composition.  
* **Tailwind CSS**: Styling and responsive design.  
* **Lucide React**: Iconography.  
* **Single File Architecture**: Uses Babel Standalone to run JSX directly in the browser without a build step.

## **📄 License**

This project is open source and available under the [MIT License](https://www.google.com/search?q=LICENSE).

*Note: This tool uses CDN links for React, ReactDOM, Babel, and Tailwind CSS. An internet connection is required to load these dependencies initially.*

