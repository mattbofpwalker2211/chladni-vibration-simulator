# Chladni Vibration Plate Simulator - Physics Simulation 2026

> **Explore Chladni figures in your browser with animated standing waves, configurable vibration modes, and sand particles that settle along nodal lines.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Latest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/mattbofpwalker2211/chladni-vibration-simulator?style=flat-square)](https://github.com/mattbofpwalker2211/chladni-vibration-simulator)

---

<p align="center">
  <a href="https://mattbofpwalker2211.github.io/chladni-vibration-simulator/">
    <img src="https://img.shields.io/badge/Download-Chladni%20Vibration%20Plate%20Simulator%20Latest-brightgreen?style=for-the-badge" alt="Download Chladni Vibration Plate Simulator">
  </a>
</p>

> **[Download Chladni Vibration Plate Simulator Latest](https://mattbofpwalker2211.github.io/chladni-vibration-simulator/)**

---

[Download Latest Build](https://mattbofpwalker2211.github.io/chladni-vibration-simulator/)

---

## Explore Chladni Vibration Plate Simulator

Chladni Vibration Plate Simulator is an interactive browser experiment showing how vibration can produce distinct geometric formations on a surface. Using an animated Canvas API view, it represents sand particles moving toward the nodal lines created by standing waves.

The project is intended for students, teachers, and curious users who want to investigate Chladni figures visually. Sliders let you change horizontal and vertical vibration modes, and the particle population and vibration speed can both be modified while the simulation continues running.

---

## Highlights

- Produce Chladni-like figures by selecting horizontal and vertical modes
- Watch simulated sand collect around nodal lines
- Modify the number of particles without stopping the display
- Tune vibration speed during playback
- Render the animation smoothly through the Canvas API
- Study standing-wave effects using direct interactive controls
- Try multiple mode pairings from within a web browser
- Run the project without installing a separate desktop runtime

---

## Getting Started

Download the project files or clone the repository:

```bash
git clone https://github.com/mattbofpwalker2211/chladni-vibration-simulator.git
cd REPO
```

Open the primary HTML file in a modern browser. Some browsers limit functionality when files are opened directly from disk; in that case, start a basic local server from the project directory and use the address it provides.

For systems with Python available:

```bash
python -m http.server 8000
```

Open the following URL:

```text
http://localhost:8000
```

---

## Using the Simulator

1. Open the simulator in a web browser.
2. Move the horizontal mode control to alter one wave direction.
3. Set the vertical mode to test a different pattern combination.
4. Select the desired sand particle count.
5. Change the vibration speed while observing the animation.
6. Compare the nodal-line formations produced by different control values.

Changes are applied as you work, so new configurations can be tested without reloading or restarting the page.

---

## Available Controls

There is no separate configuration file. The simulator is operated through its browser-based controls:

- Horizontal vibration mode
- Vertical vibration mode
- Sand particle count
- Vibration speed

Use these settings to build and compare a range of simulated standing-wave patterns.

---

## System Requirements

- A modern browser that supports the Canvas API
- JavaScript enabled in the browser
- The local HTML project files or access to the hosted build
- Sufficient browser resources for the chosen particle count and animation settings

Normal browser operation does not require a separate runtime or desktop installation.

---

## Common Questions

### What is shown in the visualization?

The simulator models Chladni figures by representing sand moving across a vibrating plate. The particles tend to accumulate near the simulated nodal lines.

### How can I produce another pattern?

Change the horizontal and vertical mode sliders. Different combinations create different standing-wave arrangements.

### Is vibration speed adjustable during playback?

Yes. The speed setting can be changed while the simulation is active.

### Can the particle quantity be changed while it runs?

Yes. Use the interface to alter the sand particle count in real time.

### Are settings saved anywhere?

Controls are managed in the browser interface. The project profile does not define persistent settings storage.

### What can I do if the animation runs slowly?

Try lowering the particle count or reducing the vibration speed, then observe the result again. The available performance depends on the browser and device.

### How do I find the newest version?

Open the hosted build for the latest available release, or pull updated repository changes when they are published.

### Where should I report a problem?

Check the repository documentation, then open an issue at [GitHub](https://github.com/mattbofpwalker2211/chladni-vibration-simulator). Include your browser, device, selected settings, and a description of the issue.

---

## Planned Improvements

- Further polish interactive pattern exploration
- Make vibration-mode comparison controls more useful
- Continue improving the animated Canvas presentation
- Add more documentation for browser-based experiments

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
