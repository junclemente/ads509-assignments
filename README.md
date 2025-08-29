# ads509-assignments

# Weekly Readings

| Week | Albrecht, J. |
| :--: | :----------: |
|  1   |     2, 3     |
|  2   |     1, 4     |
|  3   |      5       |
|  4   |     6, 7     |
|  5   |      8       |
|  6   |      11      |
|  7   |    10, 13    |

--

## Data Science on AWS

<img src="./media/blueprints_textbook.png
" height="200">

Albrecht, J., Ramachandran, S., & Winkler, C. (2020). Blueprints for text analytics using Python. O’Reilly Media. ISBN: 9781492074045

# Environments Creating a conda environment from a yml file

To create an environment with a specific name:

```
conda env create -n ENVNAME -f ENVNAME.yml
```

To create an environment using the name in the YAML file:

```
conda env create -f ENVNAME.yml
```

Update environment:

```
conda env update -f local.yml --prune
```

To prevent printing double chapters when exporting a notebook to PDF, use the following command in a markdown cell:

```{markdown}
\setcounter{secnumdepth}{0}

```

Import custom library:
[https://github.com/junclemente/jcds](https://github.com/junclemente/jcds)

```{python}
# import custom library
!pip install git+https://github.com/junclemente/jcds.git
```