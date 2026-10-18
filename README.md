# NPool

A pool game for two players on one screen, or one player against the computer. The whole game is a single file, `npool.html`, with no dependencies and no build step.

## Run it

Open `npool.html` in any modern browser. It works offline.

To put it online, upload `npool.html` to any static host (GitHub Pages, Netlify, Cloudflare Pages, or any web server).

## Game modes

- **8-Ball:** standard rules with a called pocket for the 8-ball, break rules, fouls, and ball in hand.
- **9-Ball:** hit the lowest ball first and sink the 9 to win.
- **Practice:** no rules or turns. Clear all 15 balls in as few shots as you can.

## Controls

- Click or drag on the table to aim. The arrow keys fine-tune the aim (hold Shift for tiny steps).
- Grab the cue stick and pull it back, then release to shoot. The farther you pull, the more power. Esc cancels a pull.
- Use the circular dial to set where the cue ball is hit: high for follow, low for draw, left or right for English.
- With ball in hand, drag the white ball to place it before you shoot.

## Options

- **Opponent:** switch between a second human player and the computer.
- **Felt and Wood:** pick the table colors. The caption under each row shows the current choice, and your choice is saved in the browser.
- **Guide:** turns the aiming line on or off.
- **Sound:** turns the synthesized sound effects on or off.

## Notes

- The winner screen shows a confetti celebration. It is skipped when the device is set to reduce motion.
- Table colors are the only setting saved between visits (in the browser's localStorage).
