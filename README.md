# 🎁 Surprise Box

**15 tiny games. A few seconds each. How long can you last?**

Every round a gift box drops in, rattles, and pops open to reveal a random mini-game.
You get one word of instructions and a burning fuse. Win and the next box comes faster.
Lose and you lose a heart. Lose all four and it's game over.

## Play

Open `index.html` in any modern browser. That's it: one file, no install, no build step.

- **Mouse or touch** for everything
- **Space** works as a tap (great for MASH!, JUMP!, STOP!, STACK! and FIRE!)
- **M** toggles sound

To host it for friends, turn on GitHub Pages for this repo (Settings → Pages → deploy from `main`, root folder).

## The 15 surprises

| Game | What to do |
| --- | --- |
| POP! | Pop every balloon |
| DODGE! | Don't get squished by meteors |
| CATCH! | Grab the falling stars, skip the bombs |
| STOP! | Tap when the needle hits green |
| MASH! | Tap like crazy until the pufferfish pops |
| FIND IT! | Spot the odd one out |
| FEED! | Drag the donut into the monster's mouth |
| SWAT! | Squash the flies |
| SLICE! | Swipe through the fruit |
| DON'T! | Do **not** touch the button (it really wants you to) |
| FIRE! | Blast the UFO with your cannon |
| READ IT! | Tap the color the word *says*, not the color it's written in |
| COUNT! | How many chicks are bouncing around? |
| JUMP! | Hop over the spikes |
| STACK! | Drop blocks onto the tower |

## How it gets harder

- Every 4 rounds: **SPEED UP!** The whole game, music included, runs faster.
- Every 5 rounds: the games themselves get trickier (more balloons, moving targets, smaller zones).
- Every 10 wins: a bonus heart if you're missing one.

Your best score and rank title are saved in your browser. Can you reach **Legend of the Box**?

## Under the hood

Everything is drawn live on a single `<canvas>` (no images) and every sound and the chiptune
soundtrack are synthesized with the Web Audio API (no audio files).
