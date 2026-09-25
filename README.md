# Idol Gems — prototype

A playable single-file slot prototype with a K-pop cute-casino theme. **Play money only.**

**Play:** https://georgeburda.github.io/idol-gems-proto/ (built for phones in portrait; works on desktop too)

- Tap anywhere to spin. Tapping during an animation skips ahead.
- Pots (jars) fill up with sparkles for show only. They never pay anything.
- Bonus: mystery trigger, about 1 in 200 spins. It's a Hold & Spin on a 4×3 grid: crystals of the target color fly into the Fan Box, and the bonus ends when the grid is full.

Debug options:
- `?seed=123` makes the random numbers repeatable.
- `?bonus=pink|mint|lavender|sky|yellow|coral` makes the next spin trigger that bonus.
- `?turbo=1` speeds up animations.
- Tap a jar to arm its bonus for the next spin.
- Long-press the balance to open the debug panel (reset balance, empty jars, turbo).
