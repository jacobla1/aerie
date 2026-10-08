# Aerie

A glider game set in a procedurally generated fjord at golden hour. It opens with a self-running cinematic flyby; press **Enter** (or click **Fly the fjord**) to start a 24-gate time trial.

Single self-contained `index.html` built on Three.js (loaded from jsDelivr). Terrain, shaders, effects and audio are all generated in code.

## Run

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8765
```

## Controls

- Mouse, arrow keys or WASD to steer; drag on touch screens
- **Esc** returns to the flyby
- **M** toggles sound

Append `#debug` to the URL to expose `window.__aerieStep(seconds)` for stepping the simulation frame by frame.
