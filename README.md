# Sequential Multi-Timer

A minimal, offline, fullscreen sequential multi-timer with an OLED pure-black aesthetic. Designed for productivity sprints, workouts, presentations, and structured intervals.

## Features

- **100% Offline & Standalone**: Single-file web app with built-in Web Audio API tone synthesis (no external MP3/CDN assets needed).
- **Sequential Multi-Interval**: Automatically transitions from Timer 1 to Timer 2, Timer 3, etc., until the queue finishes.
- **Uncapped Minutes**: Minutes can exceed 60 (e.g. `70:00`, `90:00`, `120:00`).
- **OLED Deep Black Theme**: Pure black background (`#000000`) and minimal white line SVG icons for maximum contrast and eye comfort.
- **Blurred Next Preview**: Floating frosted-glass preview of the next upcoming timer right below the active countdown.
- **Quick Stepper**: Quick adjustment buttons (`-10`, `-1`, `+1`, `+10`) for minutes and seconds, with direct numeric input.
- **Auto-Fade Interface**: All chrome/controls automatically fade out after 2.5 seconds of inactivity while running, keeping the display clean.
- **Customizable Typography & Palette**: Default Arial Black (Medium weight), with options for Impact, Monospace, and custom colors.
- **Keyboard Shortcuts**:
  - `Space` / Click screen: Start / Pause
  - `F`: Fullscreen toggle
  - `N`: Skip to next timer
  - `R`: Reset queue to beginning
  - `S` / `Esc`: Open / Close Settings
