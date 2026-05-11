# ⚡ Signal Chain — Reactivity Visualized

## Concept
A visual chain of 3–4 connected "nodes" on screen. The kid moves a slider (the source), and they watch the value ripple through the chain in real time — each node reacts and transforms the value, lighting up as it updates. Directly represents what signals and reactive programming do.

## What it teaches
- Reactivity: when one thing changes, everything connected to it updates automatically
- Data can be transformed as it flows (add 10, double it, convert to text)
- This is exactly how modern apps (Angular signals, React state) work under the hood

## How it works
- A source slider at the left (value 0–100, labeled "temperature in °C")
- Connected nodes that transform it:
  1. **Raw value** — shows the number
  2. **Converted** — converts to °F (×1.8 + 32)
  3. **Status** — shows "🥶 Cold / 😊 Comfy / 🔥 Hot" based on value
  4. **Emoji Thermometer** — a visual bar that fills up
- When the slider moves, each node lights up in sequence (animated pulse)
- Connecting arrows animate the "flow" of data

## Key interaction
> "In the app I build, when you change your language from Portuguese to English, a signal fires and EVERY piece of text on the screen updates automatically — just like this chain!"

## Fun twist
A **"Break the chain!"** button that disconnects one node — showing what happens when a signal doesn't propagate (the rest goes stale). Then a **"Fix it!"** button reconnects.

## Wow factor ⭐⭐⭐⭐⭐
Highest technical concept, but visually the most mesmerizing. The flowing animation is captivating.

## Complexity to build
Medium. Animated SVG/Canvas for the chain, reactive JS state, CSS keyframe pulses.

## Talking points for you
- "This is literally called 'signals' — it's the newest and most modern way to build apps, and it's what I use at work"
- "Before signals, developers had to manually tell the page to update. Signals do it automatically"
- "The whole internet is basically data flowing through chains like this"

## Suggested aesthetic
Dark background (space/circuit board feel). Neon glow on the chain nodes. Animated particle flow along the connecting lines. Feels like hacking or seeing the matrix. Very cool for kids.
