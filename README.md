# venn_diagrams_in_python
### Creating Venn diagrams in Python

---

A Venn diagram shows all possible logical relationships between a finite collection of different sets.

Thankfully, creating Venn diagrams in Python is easy! The only library you will need is matplotlib_venn. This is easily installed via pip install in the command line.

import matplotlib.pyplot as plt
from matplotlib_venn import venn2, venn2_circles, venn2_unweighted
from matplotlib_venn import venn3, venn3_circles
venn2(subsets=(10, 10, 4), set_labels=('A', 'B'))

![equalsizevenn](https://user-images.githubusercontent.com/67603279/227802562-c39a3d58-6c76-481d-989c-8c967c84e207.png)

