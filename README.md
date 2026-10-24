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

## Why this memory method helps

The routine reduces eight wire positions to four pairs and a consistent sequence. It uses established learning principles; it is a memory aid, not a guarantee.

- **Fixed anchors:** Blue and brown stay in the same positions in both standards, reducing what you must work out each time.
- **Chunking:** Remember four pairs and a repeatable routine instead of eight disconnected facts.
- **Distinctive cues:** Basketball orange and alien-snot green connect each standard to a vivid image that can help you retrieve the starting color.
- **A clear exception:** Stripe first within each pair by pin number, except blue: solid at 4, stripe at 5.
- **Retrieval practice and feedback:** Close the guide, build from empty pins, check your answer, and correct mistakes. Recalling the order gives you practice that simply looking at the answer does not.
- **Spacing and mixing:** Return tomorrow, then a few days later. Once you can do each standard, alternate A and B to practice choosing the right order.

**One correct attempt is not mastery.** Aim to wire both standards correctly from memory across several sessions. With practice, recall can become faster and require less conscious effort. These are learning principles, not claims that this particular game has been experimentally validated or that a specific brain region explains its effects.

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
