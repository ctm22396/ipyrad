.. include:: global.rst

.. _analysis:


Analysis tools
==============

ipyrad_ includes a suite of analysis tools that are designed to make it 
easy to run inference programs (e.g., STRUCTURE, TREEMIX, BPP) on the data
in an efficient way by sampling distributions of loci or SNPs from your RAD
data, grouping individuals into populations, filtering for missing data, 
and parallelizing computation. 

In this section of the documentation we have a number of example analyses
in the form of Jupyter notebooks, which is a useful tool for doing 
reproducible science. In fact, ipyrad has been designed since its inception 
for the goal of working seamlessly within jupyter. Check out the tutorials 
below on using ipyrad in Jupyter using its Python API. Then check out the
analysis tools notebooks. 


Using Jupyter notebooks 
^^^^^^^^^^^^^^^^^^^^^^^^^
This is an optional tool to use with ipyrad, but one that we strongly recommend. 

+ `Intro to Jupyter Notebooks <https://www.youtube.com/watch?v=HW29067qVWk&t=47s>`__ (Video)
+ `Running jupyter on a HPC cluster <http://ipyrad.readthedocs.io/HPC_Tunnel.html>`__  
.. + `Intro to ipyparallel (the parallel client used by ipyrad) <http://ipyrad.readthedocs.io/ipyparallel.html>`__
.. + `Using ipyrad with jupyter and git <http://ipyrad.readthedocs.io/Git_Sync.html>`__>`__


*ipyrad* API assembly
^^^^^^^^^^^^^^^^^^^^^^^^^^
These notebooks show example usage of the ipyrad API.

.. + Intro to the ipyrad API <tutorial_API.html>`__
.. + Quantify and plot shared RAD data with ipyrad <visualize.html>`__
+ `Pedicularis API <http://nbviewer.jupyter.org/github/dereneaton/ipyrad/blob/master/tests/cookbook-empirical-API-1-pedicularis.ipynb>`__ (run in jupyter-notebook)
+ `Finch API <http://nbviewer.jupyter.org/github/dereneaton/ipyrad/blob/master/tests/cookbook-empirical-API-2-Finches.ipynb>`__ (run in jupyter-notebook)  

.. + `Example RAD assembly with ipyrad API <http://nbviewer.jupyter.org/github/dereneaton/ficus-rad/blob/master/Ficus_Jander_assembly.ipynb>`__
.. + `Example PE GBS assembly with ipyrad API <http://nbviewer.jupyter.org/github/dereneaton/pedicularis-WB-GBS/blob/master/nb1-WB-assembly.ipynb>`__

*ipyrad* API analysis tools
^^^^^^^^^^^^^^^^^^^^^^^^^^^
These notebook show how to do parallelized downstream analyses in Jupyter-notebooks, and to 
generate advanced input files for many programs using the ipyrad analysis tools. 

+ `RAxML concatenation tree inference <http://nbviewer.jupyter.org/github/dereneaton/ipyrad/blob/master/tests/cookbook-raxml-pedicularis.ipynb>`__
+ `TETRAD quartet species tree inference <http://nbviewer.jupyter.org/github/dereneaton/ipyrad/blob/master/tests/cookbook-quartet-species-tree.ipynb>`__
+ `STRUCTURE population structure <http://nbviewer.jupyter.org/github/dereneaton/ipyrad/blob/master/tests/cookbook-structure-pedicularis.ipynb>`__
+ `BPP species tree and delimitation <http://nbviewer.jupyter.org/github/dereneaton/ipyrad/blob/master/tests/cookbook-bpp-species-delimitation.ipynb>`__
+ `TREEMIX admixture graph inference <http://nbviewer.jupyter.org/github/dereneaton/ipyrad/blob/master/tests/cookbook-treemix-pedicularis.ipynb>`__
+ `BUCKY concordance tree inference <http://nbviewer.jupyter.org/github/dereneaton/ipyrad/blob/master/tests/cookbook-bucky.ipynb>`__
+ `STRUCTURE with pop assignments <http://nbviewer.jupyter.org/github/dereneaton/ipyrad/blob/master/tests/example-structure-popdata.ipynb>`__


*command line programs*
^^^^^^^^^^^^^^^^^^^^^^^
These pages discuss further information about some command-line analysis tools 
that are frequently used with RAD-seq data.  

+ `RAxML phylogenetic inference CLI <http://ipyrad.readthedocs.io/raxml.html>`__
+ `TETRAD command line <http://ipyrad.readthedocs.io/tetrad.html>`__   

.. + ABBA BABA test for introgression <cookbook-dstats>`__
.. + PCA analysis of genetic structure <cookbook-PCA>`__

Other jupyter notebooks (ipyrad in the wild)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
+ You can contribute here. Let us know.
