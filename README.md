# AI Age Converter

Convert how long ago a thing was released into **AI years** — accounting for how fast AI technology advances.

> "What was released one year ago is like ages now."

**▶ Play it live:** https://arecibo-sys.github.io/ai-age-converter/

## How it works
1 AI year = one capability-doubling period (T). **AI years = human years ÷ T**

- **Conservative** (T=1.0) → 1:1
- **Standard** (T=0.5) → 1:2 — *ChatGPT = 3.7 human years = 7.4 AI years*
- **Aggressive** (T=0.25) → 1:4

## Features
- Date picker + milestone presets (ChatGPT, GPT-4, GPT-3, AlphaGo, Deep Blue, ELIZA) — computed live
- Rotating witty quips scaled by magnitude
- "If it were a person" stage mapping (Toddler → Elder) with color-coded badge
- Retro-futuristic ambient sounds (Nostromo-style hum, keystrokes, chime) with mute toggle
- Sci-fi neon-on-black aesthetic, mobile-first

## Tech
Single self-contained HTML file. Web Audio API for sounds. No external dependencies.
