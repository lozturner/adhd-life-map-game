# ADHD Life Map Game

**Interactive life-navigation tool using Google Maps interface metaphor for ADHD users. Built with GDevelop web engine.**

---

## 🎯 SYSTEM PROMPT FOR AI ASSISTANTS

> **CRITICAL**: This section contains the restoration prompt for any AI assistant working on this project. If you're starting a new chat session, copy this entire section into your first message.

### Project Overview

You are working on the **ADHD Life Map Game** - a web-based interactive application that uses a Google Maps-style interface to help ADHD users navigate their daily life, tasks, and mental states.

### Core Concept

- **Interface**: Interactive map (like Google Maps) with pan, zoom, and markers
- **Metaphor**: Life locations/states are "places" on the map
- **Input**: Two boxes ("From" / "To") become "Where I am" / "Where I want to be"
- **Output**: Visual path showing steps, time estimates, mental effort required
- **Side Panel**: Layers for different life areas (Work, Health, Admin, Relationships, etc.)
- **ADHD-Optimized**: Low clutter, high contrast, large touch targets, minimal config

### Technical Stack

**Option 1: GDevelop (Current)**
- Web-based 2D game engine at https://editor.gdevelop.io/
- No-code visual event system
- Exports to HTML5 for web deployment
- Built-in sprite and map editors
- Mobile-friendly by default

**Option 2: Custom HTML/CSS/JS**
- Leaflet.js for interactive maps
- Stylized/abstract map tiles (not real geography)
- LocalStorage for data persistence
- Single HTML file deployment

### Current Project State

- ✅ GitHub repository created: `turnerworks/adhd-life-map-game`
- ✅ GDevelop account pathway explored (can work without login)
- ✅ Basic platformer template tested in GDevelop
- ⏳ Need to build actual life-map interface
- ⏳ Need to design abstract map visualization
- ⏳ Need to implement journey/path logic

### Key Features to Implement

1. **Map Canvas**
   - Drag to pan, scroll to zoom
   - Abstract/surreal visual style (not literal streets)
   - Layers that can be toggled on/off

2. **Input System**
   - Two main input boxes: "Current state" and "Goal state"
   - Auto-suggest from saved locations
   - Quick presets for common journeys

3. **Journey Visualization**
   - Path drawn on map between two points
   - Steps broken down as clickable markers
   - Each step shows: time estimate, effort level, notes

4. **Life Locations (Markers)**
   - Persistent saved states/goals
   - Examples: "Inbox Zero", "Gym Routine", "Deep Work Mode"
   - User can add/edit/delete
   - Tagged by category/layer

5. **ADHD Modes**
   - Presets that filter/highlight different markers
   - "Low Energy Mode": show only easy wins
   - "Urgent Mode": highlight time-sensitive items
   - "Exploration Mode": show aspirational goals

### Design Principles

- **Friction-Free**: No complex setup, works immediately
- **Visual-First**: Maps and spatial thinking over lists
- **Forgiving**: Easy undo, no data loss fears
- **Mobile-Ready**: Works on phone for on-the-go use
- **Offline-Capable**: LocalStorage, no required backend

### File Structure (Target)

```
adhd-life-map-game/
├── README.md (this file)
├── index.html (main app)
├── style.css (ADHD-optimized styling)
├── app.js (map logic, journey generation)
├── data/
│   └── sample-data.json (example locations and journeys)
└── assets/
    ├── map-tiles/ (if using custom tiles)
    └── icons/ (marker icons)
```

### Next Steps for AI Assistant

1. **If continuing from GDevelop**: 
   - Design map-based scene replacing platformer template
   - Create custom objects for markers, paths, and UI panels
   - Implement event logic for pan/zoom and location selection

2. **If switching to Leaflet/HTML**:
   - Create `index.html` with Leaflet CDN
   - Design abstract tile layer or solid color background
   - Implement two-box input system
   - Build marker creation and path generation logic

3. **Core Deliverable**:
   - A working prototype where user can:
     - View an abstract map
     - Add a "From" and "To" location
     - See a generated path with 3-5 steps
     - Click steps to see details

### Restoration Command for New Chat

```
I'm continuing work on the ADHD Life Map Game from https://github.com/turnerworks/adhd-life-map-game

Please read the README System Prompt section and pick up where we left off. Current status is that we have the repo set up and explored GDevelop as the game engine. Next: build the actual map-based interface (either in GDevelop or switch to Leaflet.js + HTML).
```

---

## 📚 Resources

- **GDevelop Editor**: https://editor.gdevelop.io/
- **GDevelop Docs**: https://wiki.gdevelop.io/
- **Leaflet.js**: https://leafletjs.com/ (if going custom route)
- **This Repo**: https://github.com/turnerworks/adhd-life-map-game

## 🤝 Contributing

This is a personal ADHD tool project. Feel free to fork and adapt for your own needs.

## 📄 License

Open source, no specific license yet. Use freely.
