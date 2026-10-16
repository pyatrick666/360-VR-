# Tech Titans — Warehouse Cyber Awareness 360° Training

An interactive 360° warehouse cyber-awareness training application featuring six security hotspots, scenario-based questions, progress tracking, learner sign-in demo, results, and audio feedback.

## Launch

Open the [Cyber Awareness Training App](./).

## Features

- Explore a 360° warehouse environment.
- Investigate six interactive cybersecurity hotspots.
- Answer scenario questions and receive immediate feedback.
- Track hotspot completion and review training results.
- Use the **Sound on / Sound off** control to enable or mute audio cues.
- Audio feedback includes marker clicks, correct and incorrect answers, completion, and results.

## Project structure

- `index.html`: main warehouse training application.
- `cyberawareprototype/index.html`: standalone copy of the warehouse training experience.
- `sounds/`: shared training audio files.
- `office/`: removed from the active application.

## Run locally

Serve the repository root with a static web server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000/`.

## Technologies

HTML, CSS, JavaScript, and A-Frame. Compatible with GitHub Pages static hosting.
