# Changelog

All notable changes to this project will be documented in this file.

## [1.0.0] - 2026-06-08

### Added
- Initial release of 3D Cyber Rival Arena
- First-person shooter gameplay with mouse-lock controls
- Two game maps with distinct visual themes:
  - Neon Grid (cyan cyberpunk)
  - Vulcan Dystopia (red volcanic - visual only)
- Three weapons with different characteristics:
  - Basic Laser Pistol (free, balanced)
  - Plasma Rifle (50 credits, fast-firing)
  - Hyper Cannon (120 credits, powerful)
- AI enemy system with basic chase AI
- Physics simulation using Cannon.js
- 3D graphics rendering using Three.js
- Lobby UI with map and weapon selection
- In-game HUD with score and weapon status
- Credit/currency system
- Scoring system (10 points + 5 credits per kill)
- Dynamic enemy spawning (max 8 concurrent)
- Pointer lock aiming system
- Game state management
- Window resize handling
- Return to lobby functionality (ESC key)

### Technical
- Built with vanilla JavaScript (no frameworks)
- Three.js r128 for 3D graphics
- Cannon.js 0.6.2 for physics
- Pure CSS3 for UI styling
- Single HTML file distribution

### Notes
- This is the initial feature-complete version
- Game is fully playable in any modern browser
- No external dependencies beyond Three.js and Cannon.js (CDN hosted)

---

## Future Versions

### [1.1.0] - Planned
- [ ] Sound effects and background music
- [ ] Additional weapon types
- [ ] Enemy visual variety
- [ ] Map obstacles and cover mechanics
- [ ] Difficulty scaling

### [2.0.0] - Planned
- [ ] Modular code architecture
- [ ] Player progression/levels
- [ ] Cosmetic customization
- [ ] Multiple game modes
- [ ] Leaderboard system
- [ ] Mobile support with touch controls

### [3.0.0] - Planned
- [ ] Multiplayer support (local/online)
- [ ] Custom map editor
- [ ] Advanced AI with pathfinding
- [ ] Power-ups system
- [ ] Boss fights

---

## Version History

### v1.0.0 (Current)
- Release date: 2026-06-08
- Status: Stable
- Browser support: Chrome 90+, Firefox 88+, Safari 14+, Edge 90+
