# face detection

real-time face detection experiment using WebRTC and canvas. cyberpunk aesthetic with japanese influences.

adapted from [wesbos/HTML5-Face-Detection](https://github.com/wesbos/HTML5-Face-Detection)

## features

- real-time face detection via webcam
- visual effects: mesh overlay, glitch mode, color inversion
- neon cyberpunk UI with CRT effects
- fps counter and face tracking

## setup

clone and serve locally:

```bash
git clone https://github.com/eznj/face-detection.git
cd face-detection
```

## run

the app needs to run on localhost or https for camera access:

```bash
# using python
python -m http.server 8000

# or using node
npx serve
```

then open `http://localhost:8000` in your browser.

## controls

- **GLASSES** - toggle groucho marx overlay
- **MESH** - enable detection grid
- **GLITCH** - chromatic aberration effect
- **INVERT** - invert colors

## tech

- modern getUserMedia API
- ES6+ javascript
- CCV.js for face detection
- canvas 2D API

## notes

requires modern browser with webcam support. works best in chrome/firefox/edge.
