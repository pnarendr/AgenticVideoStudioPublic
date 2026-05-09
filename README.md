# Agentic Video Studio

Agentic Video Studio is an experiment in human and AI collaboration for narrated technical video.

The goal is not a one-shot slide generator. It is a structured authoring workspace where a human can provide intent, an AI agent can assemble the story, diagrams, narration, timing, and review artifacts, and the result can compile deterministically into a finished explainer video.

## Demo

[Watch the Agentic Video Studio demo](https://photos.app.goo.gl/yLwkDNk9Atj52V436)

## Intent

Technical explainers are rarely just scripts. They need source material, diagrams, narration, timing, review, visual corrections, and a final render. The hard part is keeping all of that visible and editable while an AI agent helps produce it.

Agentic Video Studio explores a bounded production loop:

1. A human starts with intent and taste.
2. The agent turns that into a narration-first story plan.
3. Source documents, diagrams, and generated artifacts live in a shared workspace.
4. Beat timing is tied to narration timestamps.
5. A browser editor lets the human inspect and correct the work.
6. A deterministic compiler produces the renderable presentation model.
7. The final output is rendered as video.

The core idea is a collaborative story whiteboard that can render itself as a narrated video.

## Principles

- The authored project is the source of truth.
- Human edits must round-trip back into the authoring model.
- Diagrams and assets should stay inspectable, not baked into screenshots.
- Timing should follow the narration, not guesses.
- The compiler should preserve authored intent and report problems rather than silently redesigning the work.

## Status

This is an early working prototype. The video shows the direction: a human-plus-agent workflow for creating technical YouTube-style content from structured authoring, review, and renderable artifacts.
