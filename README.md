# Tech Titans — Cyber Awareness 360°

A unified interactive cyber-awareness training application with two selectable 360° environments.

## Launch

Open the [Cyber Awareness Training App](./). The shared application shell provides persistent navigation between:

- **Office Training** — four cyber-risk hotspots, learning panels, progress tracking, and a five-question quiz.
- **Warehouse Training** — six warehouse security hotspots, scenario questions, a learner sign-in prototype, and results.

Both experiences run inside the same application shell. Use the top navigation to switch environments without leaving the app.

## Structure

- `index.html`: shared application shell and environment navigation.
- `office/index.html`: office training experience.
- `cyberawareprototype/index.html`: warehouse training experience.
- `aframe.min.js`, `assets/`, and `sounds/`: supporting office-scene assets.

## Run locally

Serve the repository root with a static web server, then open its root URL. For example:

```bash
python -m http.server 8000
```

Visit `http://localhost:8000/`.

## Technologies

HTML, CSS, JavaScript, and A-Frame. The project is compatible with GitHub Pages static hosting.
