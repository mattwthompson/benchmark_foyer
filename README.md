### benchmark_foyer

This repository includes a few functions to evaluate the scaling of foyer's atom-typing and parametrization routines against a handful of variables, including system size, molecule size, and the use of a residue map.

Some code in this repository was used to generate Figure 4 in our manuscript about Foyer (see [the paper](https://www.sciencedirect.com/science/article/pii/S0927025619303040) or its corresponding [pre-print](https://arxiv.org/pdf/1812.06779.pdf)).

### Usage 

First, install requirements

```
conda install --file requirements.txt && conda update --all
```

and then run the notebook

```
jupyter-notebook benchmark-foyer.ipynb
```

It should take on the order of an hour to run; some ranges in loops can be modified for shorter execution.
