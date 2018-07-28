# jupyter

wget https://bootstrap.pypa.io/get-pip.py
sudo python3 get-pip.py

pip3 install jupyter
sudo python3 -m pip install pandas scipy plotly numpy matplotlib
jupyter notebook
http://localhost:8888/tree
ihm->new->python3
.ipynb file is a text file that describes the contents of your notebook in JSON

```python
import numpy as np

def square(x):
    return x * x

x = np.random.randint(1, 10)
y = square(x)

print('%d squared is %d' % (x, y))
```

## some usefull package

    Pandas: import data via a url and create a dataframe to easily handle data for analysis and graphing. See examples of using Pandas here: https://plot.ly/pandas/.
    NumPy: a package for scientific computing with tools for algebra, random number generation, integrating with databases, and managing data. See examples of using NumPy here: https://plot.ly/numpy/.
    SciPy: a Python-based ecosystem of packages for math, science, and engineering.
    Plotly: a graphing library for making interactive, publication-quality graphs. See examples of statistic, scientific, 3D charts, and more here: https://plot.ly/python.

import pandas as pd
import numpy as np
import scipy as sp
import plotly.plotly as py

## anaconda
jupyter notebook
https://jupyter.brynmawr.edu/services/public/dblank/Jupyter%20Notebook%20Users%20Manual.ipynb
https://media.readthedocs.org/pdf/jupyter-notebook/latest/jupyter-notebook.pdf
https://jupyter-notebook.readthedocs.io/en/stable/notebook.html

official course notebook
http://nbviewer.jupyter.org/github/jmportilla/Udemy-notes/tree/master/
numpy:
http://docs.scipy.org/doc/numpy/reference/
advanced numpy
http://cs231n.github.io/python-numpy-tutorial/