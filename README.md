# cookbook
Miscellaneous IPython notebooks about chemical physics and science teaching.

This repository aims to show examples of python source code applied mainly to
chemical physics and material science.
Some of them are used for teaching python or basic mathematical concepts.

The [IPython Notebook](http://ipython.org/notebook.html) extend the python
interactive shell IPython as an interactive computational environment, in
which you can combine code execution, rich text, mathematics, plots and rich
media.

The IPython Notebooks present in this repository required the following python
modules :

* [pymatgen](http://pymatgen.org/) (Python Materials Genomics) A robust, open-source Python library for materials analysis.
* numpy
* scipy
* matplotlib
* [plotly](https://plot.ly/) A platform for publishing beautiful, interactive graphs from Python to the web.

All notebooks can be read through the notebook viewver of github or on
http://nbviewer.ipython.org/. The notebook of this repository can be found
here : http://nbviewer.ipython.org/github/gvallverdu/cookbook.

## List of notebook

Hereafter, a brief description of notebooks is given :

### Quantum chemistry

* plotly_bandDiagram [en]

    Plot a band diagram with plotly and pymatgen libraries with a colorscale in
    order to highlight s and p contributions to a band or to the DOS.

* plotly_bandDiagram_SpinPolarized [en]

    Plot a band diagram with plotly and pymatgen libraries with a colorscale in
    order to highlight s and p contributions to a band or to the DOS. This
    notebook deals with a spin polarized system (MnO).

* gaussian_pymatgen [en]

    How to use the pymatgen library in order to manage Gaussian input/output
    files.

* plane_waves [en]

    Example of plane waves.

* atomic_orbitals [fr]

    Plots of radial and angular part of atomic orbitals. Electronic density.

### Numpy / scipy

* skewed_fit [en]

    How to use curve fit with normal distribution or a skewed distribution.

* MoindresCarres [fr]

    Tutoriel pour découvrir python, numpy et matplotlib au travers de la
    méthode des moindres carrés et la régression linéaire.

* IntegrationNumerique [fr]

    Tutoriel pour découvrir python et numpy au travers de l'intégration
    numérique.

* curve_fit [en]

    A detailed example of curve_fit from reading the data on a csv file with pandas
    to plot the result of a non linear fit.

### Plot

* intro_matplotlib [fr]

   Short introduction to matplotlib

* intro_plotly [fr]

   Short introduction to plotly

* anscombe [fr]

   Quartet d'Anscombe

* pandas_capp [fr]

    Introduction à pandas et exemples de graphiques avec matplotlib (barh, xy, pie chart, wedges, treemaps).
    Utilisations des données de la CAPP.

* mpl_seaborn_styles [en]

    Matplotlib seaborn styles in order to obtain aesthetic plots.

### Miscellaneous

* colorscale [en]

    manage colors and palette using matplotlib, colorlover or seaborn

* RegularExpressionExamples [en]

    Practical examples of regular expressions with python and module re.

* genetique [fr]

   Apprendre python via des exercices sur l'ADN. Manipulation des dictionnaires
   et écriture d'une classe.
