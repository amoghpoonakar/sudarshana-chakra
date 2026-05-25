# Sudarshana Chakra

An interactive, gesture-controlled cinematic experience inspired by the divine Sudarshana Chakra.

This project combines real-time hand tracking, procedural graphics rendering, physics-based interaction, dynamic lighting, and immersive sound effects directly inside the browser using pure JavaScript and HTML5 Canvas.

---

# Features

## Real-Time Hand Tracking

Powered by MediaPipe Hands for smooth and accurate gesture recognition.

---

# Gesture-Based Interaction

## 🔹 Summon Gesture
Raise only your index finger to summon the chakra.

## 🔹 Stabilization
Hold your hand steady to stabilize and charge the chakra.

## 🔹 Flick Detection
Flick your hand to launch the chakra across the screen.

---

# Procedural Chakra Rendering

The Sudarshana Chakra is fully rendered mathematically using Canvas APIs.

### Includes

- Multi-layer concentric rings
- Dynamic gradients and metallic shading
- Perspective tilt simulation
- Rotating spokes and spikes
- Real-time glow compositing
- Motion trails during launch

No external 3D models or rendering engines were used.

---

# Advanced Visual Effects

## Lightning Summon Effect
A procedurally generated lightning strike appears during chakra summoning.

## Glow Rendering
Additive blending creates cinematic bloom and aura effects.

## Motion Trails
Launched chakra leaves behind fading rotational trails.

## Dynamic HUD
Interactive cinematic status system:

- Summoning...
- Chakra Ready
- Launching...

## Atmospheric Overlay
Darkened cinematic tint for immersion.

---

# Audio Effects

Integrated sound effects for:

- Lightning summon
- Chakra activation
- Energy stabilization
- Launch effect

Audio synchronization is handled in real-time for cinematic feedback.

---

# Technical Highlights

## State Machine Architecture

The project uses a clean interaction state system:

```txt
IDLE → SPAWNING → READY → LAUNCHED
```

This keeps gesture interactions smooth and manageable.

---

## Motion Buffering

Flick gestures are detected using buffered positional analysis:

- Tracks fingertip motion
- Calculates directional velocity
- Detects launch threshold dynamically

---

## Custom Rendering Engine

Everything is rendered manually using:

- HTML5 Canvas
- Dynamic geometry calculations
- Layered rendering passes
- Glow compositing techniques

---

# Tech Stack

## Frontend

- HTML5
- CSS3
- Vanilla JavaScript

## Graphics

- HTML5 Canvas API

## Computer Vision

- MediaPipe Hands
- Camera Utilities

---

# How To Run

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/sudarshana-chakra.git
```

---

## 2️⃣ Open Project Folder

```bash
cd sudarshana-chakra
```

---

## 3️⃣ Run Locally

Simply open:

```txt
index.html
```

in your browser.

OR use VS Code Live Server for best results.

---

# How It Works

## Step 1
Allow camera access.

## Step 2
Show your hand to the webcam.

## Step 3
Raise only your index finger.

## Step 4
Lightning appears and the chakra materializes.

## Step 5
Hold steady to stabilize the chakra.

## Step 6
Flick your hand to launch it.

---

# Controls

| Gesture | Action |
|----------|--------|
| Index finger up | Summon chakra |
| Hold steady | Stabilize |
| Flick motion | Launch chakra |

---

# Project Structure

```txt
📁 project
 ┣ 📄 index.html
 ┣ 📄 lightning.mp3
 ┣ 📄 README.md
```

---

# Future Improvements

## Planned Features

- Multiple Astras system
- Different gesture combinations
- Return/boomerang chakra physics
- Fire and particle effects
- Mobile support
- Voice chanting activation
- Fullscreen cinematic mode
- Multiplayer synchronized effects
- WebGL-enhanced rendering

---

# Challenges Faced

- Real-time gesture detection stability
- Smooth motion tracking
- Maintaining performance during heavy glow rendering
- Flick detection calibration
- Perspective rendering mathematics
- Synchronizing audio and VFX

---

# Inspiration

Inspired by:

- Indian mythology
- Cinematic VFX systems
- Real-time graphics programming
- Interactive gesture-controlled interfaces

---

# What Makes This Special?

Unlike traditional projects relying on libraries for visuals, this project manually builds:

- Rendering
- Geometry
- Glow systems
- Motion effects
- Interaction logic

using pure browser technologies.

This project explores the intersection of:

- Mythology
- Computer Vision
- Graphics Programming
- Human-Computer Interaction

---

# Creator

## Amogh Poonakar

Passionate about:

- Real-time graphics
- Cinematic experiences
- Interactive systems
- Mythology-inspired tech concepts

---

# Project Intent

This project was created as a fun experimental concept to push the limits of what can be achieved using only browser technologies.

It combines:

- Mythology
- Real-time rendering
- Procedural graphics
- Gesture recognition
- Immersive interaction

into one cinematic experience.

---

> “Weapons do not make legends.  
> The one who wields them does.”

---

# Radhey Radhey ✨❤️
