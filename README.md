# AetherPulse Cannon Interactive 3D Web Project

AetherPulse Cannon is an open source interactive 3D web project featuring a high-tech weapon viewer, Three.js rendering, animated sci-fi visuals, a responsive heads-up display, clickable weapon interactions, and skill controls with cooldowns and live telemetry.

## Install

1. Save the project code as `index.html`.
2. Open the file through a local web server so browser modules load correctly. For example, from the project directory run:

   ```bash
   python3 -m http.server 8000
   ```

3. Open `http://localhost:8000` in a modern web browser.
4. The project loads Three.js and OrbitControls from jsDelivr, so an internet connection is required unless those dependencies are downloaded and served locally.

## Use

- Drag across the 3D scene to rotate the camera around the weapon.
- Scroll to zoom within the configured camera distance limits.
- Click the scene to fire the plasma beam.
- Click a skill button in the Combat Skills panel to activate it.
- Press `1` to use Pulse Shot.
- Press `2` to use Phase Dash.
- Press `3` to activate Overdrive.
- Watch the telemetry panel for core output, thermal load, ammo status, and system state.
- Resize the browser window to view the responsive HUD layout on smaller screens.

---

More open source project projects by EnderDevelopment: https://github.com/EnderDevelopment

Project page: https://dash.enderdevelopment.com/community/9069fba7-1bc3-409a-b572-5722dbaf9469?utm_source=github&utm_medium=readme&utm_campaign=auto_publish&utm_content=9069fba7-1bc3-409a-b572-5722dbaf9469
