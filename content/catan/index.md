# In pursuit of (im)balanced Catan boards

*Where to view this piece: [in this Binder](https://mybinder.org/v2/gh/jackhiggins458/catan/HEAD?urlpath=%2Fdoc%2Ftree%2Fnotebooks%2Fanalyse_catan_board.ipynb).*

---

Recently, I was playing [Catan](https://en.wikipedia.org/wiki/Catan) with some friends, and we began to wonder: how could determine how "balanced" a particular Catan board is?

![](assets/catan_board.png#center)

Curiosity got the better of me, and before I knew it I had a whole project planned out. This is very much a work in progress, but so far I've been working on:

- Writing a Python library for working with hexagonal grids.
- Writing another Python library for visualising the game state of Catan (which I used to generate the image above).
- Developing an index, composed of multiple measures, to put a number on how "balanced" a particular board is.
- Generating a synthetic population of millions of randomly generated boards to apply my index to, and to hopefully find some truly "balanced" (and some horribly "imbalanced") boards.

When I get the time, I'll also be looking to complete a write up on Catan board balance, what it means, how I've measured it, and what I've found.

---