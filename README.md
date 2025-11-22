# LiteScrRec

A lightweight screen recording application written in C++.

## 🎯 Objective
LiteScrRec aims to be a **lightweight application that records the screen with quality**, without consuming excessive resources and while keeping usage simple.

## 🧭 Philosophy

- **Lightweight:** run on modest machines without requiring high-end hardware.  
- **Compatibility:** work on as many devices and Windows versions as possible.  
- **Quality:** deliver clear and stable recordings.  
- **Performance:** prioritize efficiency, avoiding lags or unnecessarily huge files.  

## 🚀 How to Use

1. Launch the application.  
2. Use the simple interface to:
   - **Start recording**: begins capturing the screen as video.  
   - **Stop recording**: finalizes and saves the `.mp4` file.  
   - **Take screenshot**: saves a screen capture as `.png`.  
3. The elapsed recording time is displayed in the UI.  
4. Notifications inform when recording starts or stops.  

## ⚙️ Technologies

- **DirectX Desktop Duplication API** → screen capture.  
- **Windows Media Foundation** → video encoding (H.264).  
- **WIC (Windows Imaging Component)** → save screenshots.  
- **Qt/ImGui** → simple and lightweight interface.  

## 📜 License
This project is licensed under the **MIT License** – see the LICENSE file for details.
