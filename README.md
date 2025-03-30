I want to play RuneScape on my MacBook, and Alt1Toolkit doesn't support me as I wish it did. I'm notoriously bad at finishing personal projects, but I do want to learn a bit of Rust, so why not be overambitious while I do?

# Augury - RuneScape 3 Overlay Toolkit

A cross-platform overlay toolkit for RuneScape 3 built with Tauri, React, and TypeScript. Augury provides an extensible plugin system for creating interactive overlays that enhance gameplay while respecting Jagex's rules.

## Project Overview

Augury creates overlays that can display helpful information like clue scroll solutions, XP trackers, and event timers. It's designed (🤞🏾) to be:

- Cross-platform (Windows and macOS)
- Lightweight and performant
- Secure and compliant with game rules
- Extensible through a plugin system

## Dev ToDo

Not necessarily in order and likely missing things, I have no idea what I'm doing.

### Core Framework

- [ ] Create transparent overlay window
- [ ] Implement click-through functionality
- [ ] Develop game window detection system
- [ ] Build overlay positioning and resizing mechanism
- [ ] Design event bus system for communication

### Plugin System

- [ ] Design plugin manifest format
- [ ] Create plugin loading/unloading mechanism
- [ ] Implement permission system
- [ ] Build sandboxing for plugins
- [ ] Develop plugin API bridge

### Game Integration

- [ ] Implement screen capture system
- [ ] Build game window detection
- [ ] Create interface element mapper
- [ ] Develop game state observer

### Built-in Plugins

### Important:

- [ ] Clue scrolls
- [ ] Quests

### If I get around to it:

- [ ] XP tracker plugin
- [ ] Event timer plugin
- [ ] Maybe more...

### Security & Compliance

- [ ] Implement permission validation
- [ ] Create plugin verification system
- [ ] Design security audit logging
- [ ] Ensure compliance with RuneScape rules

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)
