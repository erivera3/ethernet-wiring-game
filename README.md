# Ethernet Wiring Practice Game

An interactive game for practicing the T568A and T568B Ethernet wiring standards. I created this with AI assistance as a hands-on study tool while training for IT support and CompTIA A+.

## How to play

1. Choose T568A or T568B.
2. Drag each wire into pins 1–8, or select a wire and then select a pin.
3. Select **Check my wiring** for feedback.
4. Shuffle and try again, or switch standards.

All eight pins start empty. Optional hints are available when needed.

## My method for remembering the wire order

I memorize the fixed wires first, then use the letter to choose the starting color.

1. **Brown at the end: pins 7–8.** White/brown first, then solid brown.
2. **Blue in the middle: pins 4–5.** Flip the usual stripe-first order: solid blue at 4, white/blue at 5.
3. **Check A or B, then fill pins 1–2.**
   - **B = Basketball = Orange:** white/orange at 1, solid orange at 2.
   - **A = Alien snot = Green:** white/green at 1, solid green at 2.
4. **Fill the remaining pins: 3 and 6.** Use the color left over—green for B, orange for A. White-striped wire at 3, solid wire at 6.

**My sequence: 7–8 → 4–5 → 1–2 → 3–6.**

The stripe comes first in each pair when read by pin number, except blue: **4 is solid, 5 is striped**.

Practice from an empty connector, check your answer, then shuffle and repeat. Switch between A and B once you can do each reliably.

## Technical details

- HTML, CSS, and JavaScript in a single `index.html` file
- Responsive layout with click/tap and drag-and-drop controls
- Separate answer checking for each wiring standard
- Hosted with GitHub Pages; no backend, account, or installation needed

## Run locally

Download `index.html` and open it in a web browser.

## Connector orientation

View the gold contacts facing you, with the clip away and the cable pointing down. Read pins 1–8 from left to right.

Built with AI assistance. This is a personal learning project, not an official CompTIA resource.
