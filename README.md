# Web-AR Image Recognition Project

This project implements a professional AR experience using **MindAR** and **A-Frame**.

## 🚀 Features
- **Image Tracking**: Point your camera at a target to trigger AR.
- **3D Model**: Animated 3D model appears on top of the target.
- **Video Player**: Floating video plays automatically when the image is detected.
- **Text Info**: Interactive Glassmorphism UI pops up to provide details.

## 📂 Project Structure
- `index.html`: The main entry point with AR logic and styling.
- `assets/`: Folder to put your custom targets, 3D models (.gltf), and videos.

## 🛠️ How to Test Locally
1. You need a local server (like Live Server in VS Code).
2. Or run: `npx serve .` in this directory.
3. Open the URL on your **phone** for the best experience.

## 📤 How to upload to GitHub
Run these commands in your terminal:

```bash
# 1. Initialize git
git init

# 2. Add files
git add .

# 3. Commit
git commit -m "Initialize Web-AR project"

# 4. Connect to your repo (Change naviddiff to your actual account)
git remote add origin https://github.com/naviddiff/web-ar-image-recognition.git

# 5. Push code
git branch -M main
git push -u origin main
```

## 📸 Target Image to Scan
For the current demo, use this target image:
[Click to view Target Image](https://cdn.jsdelivr.net/gh/hiukim/mind-ar-js@1.2.2/examples/image-tracking/assets/card-example/card.png)
