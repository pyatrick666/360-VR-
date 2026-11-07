# Tech Titans — Warehouse Cyber Awareness 360° Training

An interactive cybersecurity awareness learning experience set inside a 360° warehouse environment. Learners explore the scene, identify workplace cyber risks, answer scenario-based questions, and review their results.

<p align="center">
  <a href="https://pyatrick666.github.io/360-VR-/"><strong>Launch the live experience →</strong></a>
</p>

> Application screenshots and 360° scene captures will be added in a later update.

## Project overview

This project demonstrates how an immersive environment can support practical cybersecurity awareness training. Its warehouse setting presents learners with interactive risk hotspots and short decision-making scenarios.

The experience is an educational prototype, not a production identity, assessment, or training-management platform.

## Learning experience

1. Open the 360° warehouse environment.
2. Explore the scene and inspect the six cybersecurity risk hotspots.
3. Read each scenario and choose an answer.
4. Review immediate feedback and track progress.
5. View the final score and scenario-by-scenario review.

## Features

- Interactive 360° warehouse scene
- Six cybersecurity risk hotspots
- Scenario-based multiple-choice questions
- Immediate answer feedback
- Progress tracking and final score
- Scenario-by-scenario results review
- Sound toggle and audio feedback for answers, progress, and results
- Demo sign-in for exploring the prototype

## Demo access

| Role | Username | Password |
| --- | --- | --- |
| Trainee | `trainee` | `warehouse123` |
| Admin | `admin` | `admin123` |

**Security note:** These are public demo credentials for a front-end prototype. Authentication is client-side only and must not be used for real accounts, private information, or production access.

## Technology

- HTML for application structure
- CSS for layout and presentation
- JavaScript for scene interaction, quiz logic, progress, sound, and demo sign-in
- A-Frame, loaded from its hosted CDN, for the 360° experience
- Warehouse panorama asset from Poly Haven
- Six short audio effects stored in the project

The 360° framework and panorama are loaded from external sources, so an internet connection is required.

## Run locally

### Hosted version
Visit the [live application](https://pyatrick666.github.io/360-VR-/).

### Local copy
```bash
git clone https://github.com/pyatrick666/360-VR-.git
cd 360-VR-
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000). You can also open `index.html` directly, although a local HTTP server is more reliable for browser-loaded resources.

## Project structure

```text
360-VR-/
├── index.html   # Markup, styles, scene, and interaction logic
└── sounds/      # Six short audio effects
```

The application is intentionally kept in a compact single-page structure for this prototype.

## Limitations

- Demo sign-in is client-side only and is not secure authentication.
- The project is an educational prototype, not a production training platform.
- A-Frame and the warehouse panorama require an internet connection.
- Demo accounts and scores should not be treated as secure user records.

## Project contribution

Developed as part of the **Tech Titans — Cyber Awareness 360° enterprise project**. My contribution focused on programming and implementation.

## Links

- **Live experience:** [360-VR-](https://pyatrick666.github.io/360-VR-/)
- **Source code:** [GitHub repository](https://github.com/pyatrick666/360-VR-)
- **Developer portfolio:** [Pratik Poudel](https://pyatrick666.github.io/Professional-Portfolio/)

<div align="center">

**Explore. Identify. Learn.**

</div>
