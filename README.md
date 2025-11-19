```
 ██████╗██╗   ██╗██████╗ ███████╗██████╗ ███████╗ █████╗  ██████╗███████╗
██╔════╝╚██╗ ██╔╝██╔══██╗██╔════╝██╔══██╗██╔════╝██╔══██╗██╔════╝██╔════╝
██║      ╚████╔╝ ██████╔╝█████╗  ██████╔╝█████╗  ███████║██║     █████╗
██║       ╚██╔╝  ██╔══██╗██╔══╝  ██╔══██╗██╔══╝  ██╔══██║██║     ██╔══╝
╚██████╗   ██║   ██████╔╝███████╗██║  ██║██║     ██║  ██║╚██████╗███████╗
 ╚═════╝   ╚═╝   ╚═════╝ ╚══════╝╚═╝  ╚═╝╚═╝     ╚═╝  ╚═╝ ╚═════╝╚══════╝
```

# 電脳顔検出 // NEURAL FACE DETECTION

> **A cyberpunk experiment in real-time face detection**
> WebRTC + Canvas API + Neon Aesthetics + 日本語

```
STATUS: ONLINE
MODE: EXPERIMENTAL
YEAR: 2025
TECH: HTML5 • ES6+ • Canvas • WebRTC
```

---

## ⚡ FEATURES // 機能

```
[✓] REAL-TIME DETECTION    → リアルタイム検出
[✓] CYBERPUNK UI           → サイバーパンクUI
[✓] GLITCH EFFECTS         → グリッチエフェクト
[✓] MESH OVERLAY           → メッシュオーバーレイ
[✓] SCANLINE SIMULATION    → スキャンライン
[✓] CHROMATIC ABERRATION   → 色収差
[✓] FPS COUNTER            → FPSカウンター
[✓] NEON AESTHETICS        → ネオン美学
```

### VISUAL MODES

- **GLASSES** — Classic Groucho Marx overlay
- **MESH** — Cyberpunk facial recognition grid (顔検出)
- **GLITCH** — Real-time chromatic aberration & color shift
- **INVERT** — Color inversion mode

---

## 🚀 QUICK START // クイックスタート

```bash
# Clone this reality
git clone https://github.com/eznj/face-detection.git
cd face-detection

# Serve locally (required for camera access)
python -m http.server 8000
# or
npx serve

# Navigate to
http://localhost:8000/face.html
```

**IMPORTANT:** Must run on `localhost` or `https://` — camera API requires secure context.

---

## 🎮 CONTROLS // 操作

| BUTTON | FUNCTION | 機能 |
|--------|----------|------|
| **GLASSES** | Toggle Groucho Marx overlay | グラスの表示/非表示 |
| **MESH** | Enable cyber detection grid | サイバーグリッド表示 |
| **GLITCH** | Activate chromatic aberration | グリッチエフェクト起動 |
| **INVERT** | Invert color channels | カラー反転 |

---

## 🔮 TECH STACK // 技術スタック

```javascript
{
  "core": [
    "Modern getUserMedia API",
    "ES6+ Classes & Async/Await",
    "Canvas 2D API",
    "CCV.js (Face Detection)"
  ],
  "aesthetic": [
    "IBM Plex Mono (Google Fonts)",
    "CSS Animations (Scanlines, Glitch)",
    "Neon Color Palette (Cyan/Magenta/Green)",
    "Japanese Typography (電脳/顔検出/サイバー)"
  ],
  "effects": [
    "CRT Screen Simulation",
    "Chromatic Aberration",
    "Real-time FPS Tracking",
    "Terminal-style UI Overlays"
  ]
}
```

---

## 📡 ARCHITECTURE // アーキテクチャ

```
┌─────────────────────────────────────┐
│  CYBERFACE DETECTION PIPELINE       │
├─────────────────────────────────────┤
│                                     │
│  [WebRTC Camera Stream]             │
│         ↓                           │
│  [Canvas Rendering Loop]            │
│         ↓                           │
│  [CCV.js Face Detection]            │
│         ↓                           │
│  [Visual Effects Layer]             │
│    • Glasses Overlay                │
│    • Mesh Grid (顔検出)             │
│    • Glitch/Chromatic Aberration    │
│    • Color Inversion                │
│         ↓                           │
│  [Cyberpunk UI Overlay]             │
│    • Scanlines                      │
│    • FPS Counter                    │
│    • CRT Effect                     │
│    • Corner Brackets                │
│                                     │
└─────────────────────────────────────┘
```

---

## 🎨 COLOR PALETTE // カラーパレット

```css
--neon-cyan:    #00ffff  /* Primary UI */
--neon-magenta: #ff00ff  /* Accents & Mesh */
--neon-green:   #00ff41  /* Status Text */
--deep-black:   #0a0a0a  /* Background */
--glitch-pink:  #ff0080  /* Error States */
```

---

## 🌐 BROWSER SUPPORT // ブラウザサポート

Requires modern browser with:
- `navigator.mediaDevices.getUserMedia()`
- `async/await` support
- Canvas 2D API
- ES6+ features

**Tested on:**
- Chrome 90+
- Firefox 88+
- Edge 90+
- Safari 14+

---

## 📝 CREDITS // クレジット

**Original Concept:**
Adapted from [wesbos/HTML5-Face-Detection](https://github.com/wesbos/HTML5-Face-Detection)

**Face Detection:**
[CCV.js](https://github.com/liuliu/ccv) — Computer vision library

**Cyberpunk Modernization:**
Complete rewrite with ES6+, modern APIs, and experimental aesthetics

---

## ⚠️ NOTES // 注意事項

```
[!] Camera access required
[!] HTTPS or localhost only
[!] Performance varies by device
[!] Experimental — for fun and learning
```

---

## 📜 LICENSE

Original code under respective licenses.
Cyberpunk modifications — use freely, break things, build cool stuff.

---

```
SYSTEM STATUS: OPERATIONAL
CONNECTION: ESTABLISHED
NEURAL LINK: ACTIVE
接続完了 // CONNECTION COMPLETE
```

**[ACCESS DENIED]** → Just kidding, it's open source 🎭

---

**Made with ⚡ in the neon-lit streets of cyberspace**
**電脳空間で作成**
