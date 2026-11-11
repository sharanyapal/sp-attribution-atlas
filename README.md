<div align="center">

# Attribution Atlas

**Attribution is a question of assumptions, not just a dashboard.**

`HTML · CSS · JavaScript` · Educational implementation · Source available

[Concept](#concept) • [Run](#run) • [Source tour](#source-tour) • [Caveats](#caveats)

</div>

---

## Concept

A functional standalone, offline-capable browser application, built without vendor API keys or a backend. Open `index.html` locally or deploy the repository as a static website.

## Run

```bash
python -m http.server 8000
```
Visit **http://localhost:8000/**.

## Source tour

| In this repository | Role |
|:--|:--|
| [`README.md`](./README.md) | Technical context |
| [`app.js`](./app.js) | Application logic |
| [`index.html`](./index.html) | Web interface |
| [`style.css`](./style.css) | Styling and layout |

## Caveats

Treat this as a reproducible educational project. Simulation outputs depend on the project assumptions; use synthetic inputs, inspect edge cases and review the source before applying any approach to a production system.

<details>
<summary>Original documentation and implementation notes</summary>

# Attribution Atlas

A functional standalone, offline-capable browser application, built without vendor API keys or a backend. Open `index.html` locally or deploy the repository as a static website.

## Engineering notes
- Actual algorithms run inside the browser.
- Sample/generated data is explicitly described as a simulation; uploaded local data stays on-device.
- Accessibility: keyboard-operated controls and readable status output.
- No tracking, cookies, CDN dependencies, or hardcoded credentials.

Run: `python -m http.server 8080` from this directory.

</details>

---

<sub>Code and commentary in the [Sharanya Pal project index](https://github.com/sharanyapal?tab=repositories).</sub>
