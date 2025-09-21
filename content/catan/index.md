# In pursuit of (im)balanced Catan boards

*Where to view this piece: [click here, in this Binder](https://mybinder.org/v2/gh/jackhiggins458/catan/HEAD?urlpath=%2Fdoc%2Ftree%2Fnotebooks%2Fanalyse_catan_board.ipynb).*

---

Recently, I was playing [Catan](https://en.wikipedia.org/wiki/Catan) with some friends, and we began to wonder: could you quantify how "balanced" a given board is?

![](assets/catan_board.png#center)

Curiosity got the better of me, and before I knew it I had a whole project planned out. This is very much a work in progress, but so far I've been working on:

- Writing a Python library for working with hexagonal grids.
- Writing another Python library for visualising the game state of Catan (used to generate the image above).
- Developing an "Catan Board Balance Index", composed of multiple metrics, to quantify the "balance" of a board.
- Generating a population of millions of randomly generated boards to apply my index to, to find some truly "balanced" (and some horribly "imbalanced") boards.

---