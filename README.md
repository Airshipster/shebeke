# Shebeke: Digital Glass

An interactive digital-art installation inspired by the shebeke of Sheki: ornamental wooden lattices and stained-glass windows assembled from small pieces of colored glass. Here, the geometry of a palace window becomes a living light surface whose color, shimmer, and particles respond to music, microphone input, and movement in front of the camera.

The Azerbaijani word *shebeke* means "net" or "lattice." The work carries that layered architectural idea into a screen and sound space: the viewer becomes a source of motion, while audio becomes a source of light.

Open the installation directly: https://airshipster.github.io/shebeke/

The Alihan Mamedov track starts automatically when the browser allows audible autoplay; the control switches to `Pause music` during playback and to `Start music` when stopped. A custom audio file can be selected with `Load music`. Camera and microphone controls require browser permission.

## Files

- `index.html` - main contour-reactive GitHub Pages entry point.
- `final-contours.html` - contour-reactive version with the same defaults.
- `final.html` - alternate light-comet version.
- `Alihan SAMEDOV SARI GELIN - Alihan Samedov (128k).mp3` - bundled audio track.

The project does not use external JavaScript libraries; the visualization uses browser WebGL, SVG, and Web Audio APIs. The background particle and trail shader is adapted from the OpenProcessing sketch by Jason Labbe, profile name theRussetPotato. The current implementation extends that shader architecture with its own shebeke SVG, audio, microphone, and camera systems.
