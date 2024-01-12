# plot_tree

This module allows the user to plot a phylogenetic tree on an existing matplotlib axis.

This means that:
* Phylogenies can be incorporated into existing plots.
* Annotations can be added using standard matplotlib functionality.
* Plots can be output in png, pdf, svg or tiff formats.
* Automatically generated and updated figures can include phylogenies

The module depends on the ETE Toolkit, an existing Python framework for analysing and visualising phylogenetic trees, plus the matplotlib visualisation library.


## Quick Start

To draw a phylogeny under the default settings onto a blank figure.

```
f = plt.figure(figsize=(8, 10))
ax = plt.subplot()
results = plot_tree.plot_tree("examples/primates.nw", ax)
```

![Basic Tree](./examples/basic_tree.png "Basic Tree")



