# Project Sharp

## This is my personal journey on staying sharp amidst the growth of AI seeping in every corner of human creativity and engineering.

I will be building projects in multiple languages.

For now, I will be focusing on Rust, and I will be building towards embedded systems.

## Current Progress
| # | Skill | Task | Time |
|---|---|---|---|
| 0 | Rust fundamentals | write a non-trivial program without fighting the borrow checker | 3–4 wk |
| 1 | Bare metal | boot a chip and control a pin with no libraries, using only the datasheet | 3–4 wk |
| 2 | Interrupts and concurrency | react to hardware events and share state between them without bugs | 2 wk |
| 3 | Serial protocols | write a UART, I2C or SPI driver from a datasheet alone | 3–4 wk |
| 4 | Abstractions | explain what a HAL or async framework does underneath, because you've built that layer yourself | 2 wk |
| 5 | External devices | drive a component you've never used before, using only its datasheet | 3–4 wk |
| 6 | Host communication | have the device and a laptop exchange structured data reliably | 2–3 wk |
| 7 | Persistence and power | survive a reboot, store data in flash, sleep to save battery | 3–4 wk |
| 8 | Capstone | build something you designed that uses everything above | open |

## Spec template
- Goal: what it does, in one sentence
- Skill proven: which row above it covers
- Done when: a pass/fail test you can demo
- Out of scope: what you deliberately won't build
- Unknowns: what you'll need to research

## What to watch in your own specs
- Picking a project that skips the hard part. If your spec for row 1 uses a library, it doesn't count.
- Making it too big. If you can't demo something within about 4 weeks, split it in two.
- Writing a vague "done when". "Works well" is not a test. "Survives 100 power cycles" is.

## Rules
- Datasheet first, compiler errors second.
- NEVER EVER EVER use AI for the entire progress.
- If a phase takes twice its estimate, that's fighting. Don't skip it.
- Keep a log of where you got stuck and how you got unstuck.

# If you're here to observe a human do human-things, feel free to watch! :)
