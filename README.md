# Secret of the Pulsars — Interactive Theory Journey

A zero-dependency static prototype for presenting the NS-Capture theory as an interactive narrated scientific argument.

## What is included

- Seven-scene narrated synopsis
- Animated neutron-star encounter/capture sequence
- Explicit labels for observed facts, interpretation, and theory-specific predictions
- Live capture-energy experiment with user-controlled assumptions
- Mobile-responsive layout
- No framework, build step, package manager, or server required

## Run locally

Open `index.html` in a modern browser.

## Publish with GitHub Pages

In this repository, open **Settings → Pages** and under **Build and deployment** choose:

- **Source:** Deploy from a branch
- **Branch:** `main`
- **Folder:** `/ (root)`

Save. GitHub will publish the site at:

`https://roblevinson-cloud.github.io/secret-of-the-pulsars/`

## Narration

The page currently references the studio-quality narration generated for the prototype. If that remote audio cannot load, the interface falls back to browser speech synthesis so the experience remains testable.

## Scientific presentation principle

The interface intentionally separates three layers:

1. **Observed / established** — measurements and standard mechanics.
2. **Interpretation** — how NS-Capture connects those observations into an evolutionary sequence.
3. **Prediction** — claims specific enough to be tested or falsified.

The objective is not to hide assumptions; it is to let the visitor manipulate them and see where the proposed sequence succeeds or fails.
