HEX Web Emulator
HEX Web Emulator is a high-performance, retro web emulator optimized for devices with 8 GB RAM. It automatically probes your device capabilities, detects the console from your loaded ROM/ISO, and applies the best graphics, audio, and performance profile instantly.
Features
 * Auto-Detection & Tuning: Automatically detects console types from ROMs/ISOs and applies optimal core settings, thread counts, and rendering backends (WebGL preferred).
 * 8 GB RAM Optimization Profile: Automatically unlocks features like rewind capability, CRT shaders, high audio buffers, 2× texture scaling (for PSP/PS1), and up to 3× resolution scaling on light cores.
 * Smart ROM Loading: Supports direct URLs and automatically converts GitHub blob links to raw format before fetching. Defaults to Super Mario Bros. (NES).
 * Customizable Profiles: Manual override available via the Device profile dropdown (Desktop high-end, Desktop mid-range, Low-end laptop, Mobile high/low-end).
 * Real-time Performance Metrics: Live display of Frame Rate (FPS), Frame Time (FT), active core, emulation state, and auto-tuning status.
Keyboard Controls
| Key | Action |
|---|---|
| <kbd>↑</kbd> <kbd>↓</kbd> <kbd>←</kbd> <kbd>→</kbd> | D-Pad |
| <kbd>X</kbd> | A Button |
| <kbd>Z</kbd> | B Button |
| <kbd>S</kbd> | X Button |
| <kbd>A</kbd> | Y Button |
| <kbd>Q</kbd> | L Button |
| <kbd>W</kbd> | R Button |
| <kbd>Enter</kbd> | Start |
| <kbd>Shift</kbd> | Select |
| <kbd>Space</kbd> | Fast-forward |
| <kbd>F1</kbd> | Save State |
| <kbd>F2</kbd> | Load State |
| <kbd>F3</kbd> | EmulatorJS Menu |
| <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> | Toggle Panel |
| <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>F</kbd> | Toggle FPS |
Configuration Options
 * Frame Skipping: Set to Auto (recommended), Off, or skip 1–3 frames when cores fall behind.
 * Audio Buffer: Low (may crackle), Medium (balanced), or High (most stable; default for 8 GB).
 * Video Backend: Auto (WebGL preferred), Force WebGL, or Force Canvas (2D).
 * Shaders / Filters: Off (fastest), CRT scanlines, or 2× HQ scale.
 * Rewind: Off or On (~150 MB RAM consumption).
 * Texture Scaling: Off (native) or 2× (ideal for PSP/PS1 on 8 GB RAM profiles).
