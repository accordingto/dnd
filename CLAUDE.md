# DND - Dungeons & Dragons English Conversation Practice Platform

This project uses a Dungeons & Dragons theme to create a fun, low-pressure environment for practicing spoken English. The moderator shares their desktop while participants communicate through voice only — no video required. All interaction is audio-driven, and the shared screen provides visual prompts to guide conversation.

## Key Constraints

- **Voice only**: participants speak; no video feed is needed
- **Screen sharing**: the moderator shares their desktop so all players see the same interface
- **Static site**: runs entirely in the browser (HTML/CSS/JavaScript), no backend or login required
- **Simple to run**: open one HTML file and go — zero setup, zero dependencies

## Core Purpose

Use D&D-style prompts, scenarios, and roleplay to motivate participants to speak English naturally. The game gives everyone a character, a situation, and a reason to talk — removing the awkwardness of blank conversation practice.

## Feature Scope

Keep the feature set small and focused on driving conversation:

- **Character Card Generator** — each player is assigned a simple character (name, class, one trait) to introduce themselves in English
- **Scenario Prompt Deck** — random D&D situations displayed on screen that players must describe or react to in English (e.g. "You enter a dark cave. What do you say to your party?")
- **Dice Roller** — a visible d20 roll that triggers a prompt category (describe, decide, roleplay, question)
- **Vocabulary Spotlight** — a highlighted English word or phrase tied to the current scene, encouraging players to use it
- **Turn Tracker** — shows whose turn it is to speak, keeping conversation flowing without confusion

## Interface Design

- Large fonts and high-contrast colors for easy reading during screen share
- Minimal clicking required — the moderator drives the screen, players just talk
- All visible text in English to reinforce the learning environment
- Dark fantasy aesthetic to match the D&D theme

## Development Approach

Build a single hub page first, then add 2–3 conversation-driving modules as simple standalone screens. Use plain HTML/CSS/JavaScript only. Prioritize clarity and ease of use over visual complexity — the screen is a conversation prop, not the main event.
