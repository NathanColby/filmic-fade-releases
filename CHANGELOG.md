# Changelog

## 0.14.0

- Refreshes the built-in preset palette around eight looks, including Silver
  Retention Crush, Neon Practical Splice, and Two-Strip Optical Drift.
- Promotes visual controls for black/white point, wider tonal feathering,
  Specular Splice, Split Drift, timing Bezier handles, and stronger Chroma Hold.
- Adds profile-aware endpoint stability for LogC3, V-Log, and BMD Film Gen 5
  sources while preserving Managed / Rec.709 as the default.
- Improves GPU analysis behavior with highlight headroom and keeps the Metal
  path active for the new preset/control surface.

## 0.5.7

- Adds Tonal Input for Managed / Rec.709, ARRI LogC3, Panasonic V-Log, and
  Blackmagic Film Gen 5 footage.
- Makes Filmic Fade's tonal analysis profile-aware for log sources without
  applying a visible LUT or full gamut conversion.
- Keeps existing Managed / Rec.709 behavior as the default for older projects.

## 0.5.6

- Adds fade-in landing softness so late shadow recovery eases into the full image.
- Makes Range View a full-opacity diagnostic preview.
- Standardizes tonal colors: shadows blue, mids green, highlights yellow.
- Defaults Analysis Mode to Adaptive Range Only.
- Softens Neutral-family tonal zones to `0.16`.
- Sets Neutral-family Shadow Crunch to `0.30`.
