# Image-Based Irregular Shape Area Measurement Software

## 📌 Overview
This project is an advanced, image-based irregular shape area measurement software developed using HTML5, CSS3, JavaScript, and OpenCV.js. Serving as a lightweight, browser-based alternative to heavy desktop applications like ImageJ, the tool allows users to upload images, calibrate real-world scales, and seamlessly calculate both the area and perimeter of complex shapes.

## ✨ Key Features
* **Real-World Scale Calibration:** Implement a real-world calibration system to convert pixel distances into metric/imperial units (cm, mm, in).
* **Manual Polygon Tool:** Eliminate human measurement errors by utilizing computational geometry (Shoelace formula).
* **Automated Magic Wand (Flood-Fill):** Automatic shape segmentation using a color-based Magic Wand tool. It prevents browser memory overflow by implementing an iterative, stack-based algorithm using 1D typed arrays (Uint8Array) for extreme memory efficiency.
* **Advanced Edge Detection:** Integrates OpenCV.js to apply Grayscale conversion and Canny Edge Detection, allowing users to visualize sharp object boundaries.
* **Multi-Shape Tracking & Export:** Support multi-shape tracking to record and export measurements for multiple objects simultaneously. Users can export combined data for all shapes in a single detailed CSV report.
* **Broad Format Support:** Image uploading (JPG, PNG, BMP, TIFF) via drag-and-drop or file browser.

## 🛠️ Technologies Used
* **Frontend:** HTML5, CSS3, JavaScript (ES6)
* **Computer Vision Library:** OpenCV.js (v4.x)

## 💻 System Requirements
* **Environment:** Any modern Web Browser (Google Chrome, Mozilla Firefox, Safari) with JavaScript enabled.
* **Operating System:** Cross-platform (Windows, macOS, Linux).
