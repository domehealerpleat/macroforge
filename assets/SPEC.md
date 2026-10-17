# Assets to create for macroforge

## logo.png вЂ” 256x256, transparent, dark theme
🖱️ Neon shield/gear motif matching $macroforge$ brand color. See master prompt in _shared docs.

## banner.png вЂ” 1280x640, background #0d1117
Large bold title $macroforge$, subtitle gray #8b949e, thin gradient line #00ff9dв†’#bc8cff.

## screenshots/main.png вЂ” 1280x800
Macro list with icons, durations, hotkey bindings

## screenshots/settings.png вЂ” 1280x800
Timeline editor — color-coded mouse/keyboard events

## screenshots/results.png вЂ” 1280x800
Lua script view with syntax highlighting and run output

## gifs/demo.gif вЂ” 800x500, 8s, 12fps, <8MB
1. Open app, 2. click main action, 3. status turns green, 4. toggle a feature, 5. return.
ffmpeg: -vf "fps=12,scale=800:-1:flags=lanczos,split[s0][s1];[s0]palettegen[p];[s1][p]paletteuse"