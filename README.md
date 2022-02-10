PyGIMLi-tests

### Installation

Create a conda environment:

```
conda create -n pg -c gimli -c conda-forge pygimli=1.2.3
```

```
conda activate pg
```

**Optional**: Run tests

```
python -c "import pygimli; pygimli.test(show=False, onlydoctests=True)"
```