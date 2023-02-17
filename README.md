# Network science: CS552

## Tutorial on igraph

Some Datasets are here: [Datasets for Network Science](https://github.com/chatox/networks-science-course/blob/master/practicum/data/README.md)

## Installation Instructions

Installation can be non-trivial. But, the following steps should work on any Windows computer:

* Create an anaconda environment that runs python3.5 (installing everything)
* Download the wheel here: https://www.lfd.uci.edu/~gohlke/pythonlibs/#python-igraph
* Change directory to where the above is saved and run: `python -m pip install *.whl`
* Run `Conda install pycairo`
OR for google colab run
```
!pip install python-igraph==0.8.3
!apt install libcairo2-dev pkg-config python3-dev
!pip install python-igraph leidenalg cairocffi 
```

