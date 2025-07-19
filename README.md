# 🛋️ Sofa Image Rotator Viewer

A lightweight, interactive 360° sofa viewer built with HTML, CSS, and JavaScript. Supports multiple sofa types, autoplay rotation, manual swipe, keyboard shortcuts, and SVG-based controls.

## 🚀 Features

* 🔄 **360° Image Rotation** from static images
* 🛋️ **Dropdown Sofa Selector** (`BC1`, `BC2`, etc.)
* ▶️ **Start / Stop Autoplay** with SVG play/pause button
* ⏮️ **Previous / Next Frame Navigation**
* 🖱️ **Click + Drag Rotation Control**
* ⌨️ **Keyboard Shortcuts**
* ♻️ **Reset to First Frame**
* 🧠 **Smart Image Fade Transition**
* 🖼️ **SVG Icons for Controls**

---

## 🧭 Usage

### 🔧 Controls

| Action              | Method                      |
| ------------------- | --------------------------- |
| Start/Stop autoplay | Click "▶️ / ⏸️" button      |
| Next Frame          | Click `Next` or → Arrow key |
| Previous Frame      | Click `Previous` or ← key   |
| Reset Rotation      | Click `Reset` or `R` key    |
| Toggle Play/Pause   | Press `Spacebar`            |
| Manual Rotate       | Click + drag left/right     |
| Switch Sofa Type    | Use dropdown at top right   |

---

## ⌨️ Keyboard Shortcuts

| Key       | Action               |
| --------- | -------------------- |
| `Space`   | Toggle start/stop    |
| `R`       | Reset to first image |
| `→` Arrow | Next image           |
| `←` Arrow | Previous image       |

---

## 🖼️ Assets Folder Structure

```
/img
  └── /bc3
      ├── 1.jpg
      ├── 2.jpg
      └── ...
  └── /bc4
      ├── 1.jpg
      ├── 2.jpg
      └── ...
  └── /basic
      ├── play.svg
      ├── pause.svg
      ├── left.svg
      ├── right.svg
      └── reset.svg
```

---

## 📦 How to Use

1. Clone/download this repository
2. Place your image sequences inside `/img/<directory>` as `1.jpg`, `2.jpg`, ..., `n.jpg`
3. Update `<select>` options with new sofa directories if needed
4. Open `index.html` in any modern browser

---

## 📱 Mobile Support

Touch drag support can be added for mobile devices — ask to enable it if needed!