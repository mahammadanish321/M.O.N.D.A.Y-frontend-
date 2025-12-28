This repository contains the frontend experience layer for M.O.N.D.A.Y (Modular Omni-intelligent Neural Dialogue Assistant Yielding).

The frontend is responsible for everything the user sees, hears, and interacts with. It translates backend responses into real-time voice output and animated avatar behavior, maintaining the illusion of a living assistant.

Responsibilities

Capture user input (text or voice)

Stream audio or text to the backend via WebSocket

Play speech responses using the Web Audio API

Animate the avatar using SVG and real-time audio analysis

Maintain low-latency, continuous interaction

React instantly to backend events

What this repo does not handle

AI decision-making

LLM calls

Data persistence

Business logic

Secrets or API keys

Those responsibilities belong to the backend.

Architecture role

The frontend exists to preserve presence, immediacy, and believability. It does not think or decide; it performs and reacts in real time based on backend output.

Related repository

This frontend communicates with the MONDAY backend:

👉 Backend repo:
https://github.com/mahammadanish321/M.O.N.D.A.Y-backend-