<div align="center">

# 🎬 VidSnap Studio Pro

**An Advanced Video Frame Extraction, Processing & Upscaling Suite built for Creators and Developers.**

[![Status](https://img.shields.io/badge/Status-Active-success.svg?style=for-the-badge)](#)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](#)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen.svg?style=for-the-badge)](#)

</div>

---

## ⚡ Project Overview

**VidSnap Studio Pro** is a high-performance web application designed to give users granular control over video frame extraction. It goes beyond simple screenshots by offering a complete image processing pipeline right in the browser. 

Whether you need a single perfect frame, a rapid burst of 10 shots, or automated interval captures, this tool handles it with zero lag. Coupled with AI-ready upscaling, precise color grading, and target-based file compression, it acts as a mini Photoshop specifically tailored for video frames.

---

## 🚀 God-Level Features

### 📸 1. Advanced Capture Engine
* **Precision Capture:** Extract exact frames from any video format.
* **Burst Mode (x10):** Capture 10 consecutive frames instantly with a single click.
* **Auto-Interval Extraction:** Set a time interval (e.g., every 2 seconds) and let the engine auto-capture frames while the video plays.
* **Live Zoom Preview:** Inspect fine details before capturing the frame.

### 🎛️ 2. Professional Image Processing
* **Color Grading:** Granular control over Brightness (B), Contrast (C), and Saturation (S).
* **Filters & LUTs:** Apply cinematic filters and LUT pickups to the extracted frames instantly.
* **Resolution & Resizing:** Force custom width and height, or maintain native aspect ratios.
* **Centered Cropping:** Crop freely or lock into specific aspect ratios.
* **Custom Watermarking:** Add customizable text watermarks to your exported frames to protect your content.

### 💾 3. Smart Output & Compression
* **Target-Based Compression:** Specify a target file size (e.g., 2MB), and the app uses a binary search algorithm to achieve the best possible quality under that limit.
* **Format Conversion:** Export seamlessly to PNG, JPEG, etc.
* **AI Upscaling Engine:** Apply 2x Upscale factor to enhance low-resolution frames without losing details.

### 📁 4. Batch Management (Gallery)
* **Real-time Gallery:** View all your captures instantly in the side panel.
* **Bulk Actions:** Download individual frames, clear the gallery, or compile everything into a single `.ZIP` file for easy downloading.

---

## 🛠️ Tech Stack & Architecture

* **Frontend:** React.js / Vanilla JS, HTML5 Video API, CSS3 (Dark Theme)
* **Processing:** Canvas API for rendering and color manipulation.
* **Archiving:** JSZip (or similar) for batch ZIP creation.

---

## 💻 How to Use

1. **Upload Video:** Click on `Choose Video` to load your local file.
2. **Set Output Preferences:** Go to the right panel to define Format, Quality, Resolution, and Filters.
3. **Capture:** - Hit `Capture` for a single frame.
   - Hit `Burst x10` for rapid shots.
   - Enter an interval and hit `Start Auto` for automated extraction.
4. **Edit & Upscale:** Adjust Brightness/Contrast or apply a 2x Upscale from the gallery settings.
5. **Export:** Click `Download All` or `Create ZIP` to save your assets.

---

<div align="center">
  <i>Developed by Satyam</i>
</div>
