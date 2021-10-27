# pgcore
pyGIMLi core library (pure meta-repo for building conda packages)

Please note that this repository does not hold the hardware-dependent binaries.
`pgcore` should be installed by `conda` using

```
conda install -c gimli -c conda-forge pgcore
```

or into a new environment using

```
conda create -n pg -c gimli -c conda-forge pgcore
conda activate pg
```

In order to work with pyGIMLi, you can 
1. install pyGIMLi by conda
2. clone pyGIMLi by `git clone https://github.com/gimli-org/gimli` and 
* `conda develop gimli`
* setting PYTHONPATH to gimli directory
3. install pyGIMLi by `pip install git+https://github.com/gimli-org/gimli`
