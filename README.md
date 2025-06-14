# 🧬 LifeLines – Visual Life Mapping Engine

**Status:** 🚧 Work In Progress  
**Core Purpose:** Interactive life visualization  
**Tech Stack:** Python · SQLite · Flask · Stream Deck · Custom Frontend UI  

---

## What is LifeLines?

**LifeLines** is an innovative, animated interface that displays a person’s life across multiple time-based **streams** — designed for clarity, memory recall, and visual storytelling.

It breaks a life into parallel threads, such as:

- *Places Lived*  
- *Jobs / Career*  
- *Pets*  
- *Relationships*  
- *Family & Friends*

Each stream is rendered as part of a unified, scrollable **map of your life** — helping users **see**, **navigate**, and **understand** the shape of their personal journey.

---

## Visual Design

The LifeLines UI is built as a **zoomable horizontal canvas**, where you can scroll through your entire life chronologically.  
Each life stream flows across this canvas in its own band — with important events marked along the way.

📸 **Photos** (with date and location metadata) act as visual **anchors** or **milestones** — placed automatically to highlight meaningful moments. These serve as **preview points** (formerly “keyframes”) when navigating the timeline. You can expand any photo to reveal full context: people, places, and linked memories.

---

## Use Cases

- Personal reflection and life storytelling  
- Dementia-friendly life navigation (used by the **Memory Assistant**, but works standalone)  
- Generational family mapping  
- Biographical archiving for artists, parents, or public figures  
- Interactive documentary timelines  

---

## Core Features

- 🧭 **Visual Life Map** – Stream-based UI for timeline navigation  
- 🔗 **Multi-Person Linking** – See where life paths intersect with others  
- 🖼️ **Photo Anchors** – Date/geotagged photos populate the canvas as visual milestones  
- 📁 **Modular Backend** – Stores clean structured data for flexible querying and storytelling

---

## Project Status

LifeLines is actively being developed as a standalone engine.
It is also used as a visual module inside the broader **Memory Assistant**, but does **not** depend on it.
