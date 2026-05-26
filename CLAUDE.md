# DND - Dungeons & Dragons Companion Platform

This project is a lightweight web-based companion tool for Dungeons & Dragons sessions, designed to run entirely in the browser without any backend infrastructure.

## Key Constraints

The application must run as a static site (HTML/CSS/JavaScript only) with no server-side dependencies. All game state lives in the browser session. The interface must be legible on a shared screen during tabletop sessions and work on both desktop and mobile.

## Core Requirements

Tools must support the core D&D workflow: character creation, dice rolling, and encounter tracking. The interface should use large, readable fonts and a dark fantasy aesthetic suited to long gaming sessions. All visible UI text appears in English; technical documentation and comments may use Chinese.

## Feature Scope

The planned feature set includes:

- **Dice Roller** — animated roll results for d4, d6, d8, d10, d12, d20, and d100
- **Character Sheet** — editable stat blocks, HP tracker, and skill list
- **Encounter Tracker** — initiative order management and HP per combatant
- **Spell Reference** — searchable quick-lookup for common spells
- **Random Generators** — NPC names, loot tables, and encounter seeds

## Development Approach

Build the game hub entry page first, then complete 2–3 core tools as standalone modules using plain HTML/CSS/JavaScript. Avoid frameworks and build steps to keep the project zero-dependency and instantly deployable. Commit directly to `main`; no feature branches required.
