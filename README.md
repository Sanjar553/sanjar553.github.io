# Brawl Ultra — Pro Multi-File Edition

Professional modular structure prepared from the existing Brawl Ultra project.

## Structure

- `index.html` — application shell
- `css/` — global styles, components and themes
- `js/core/` — application/game bootstrap and shared state
- `js/game/` — gameplay systems
- `js/ui/` — menus, settings and HUD
- `js/ai/` — bot difficulty/AI
- `js/storage/` — profile, settings and auto-login
- `js/audio/` — sound system
- `js/input/` — keyboard/mouse/touch controls
- `js/utils/` — shared helpers
- `assets/` — images, icons and sounds

The existing game logic is preserved in `js/app.js` and the new modules are organized so future development can move code out of the monolith safely.
