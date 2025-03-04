HemeKG
======
Assembling and modeling the knowledge around heme pathogenicity and pathway dysregulation in the context of hemolytic
disorders. The data hosted in this repo was curated by `Farah Humayun <https://github.com/Fahumayun>`_ in context of her
Master's Thesis. The curated documents are located in the ``hemekg`` directory.

Citation
--------
If you find HemeKG useful in your work, please consider citing:

.. [1] Humayun, F., *et al.* (2020). `A computational approach for mapping heme biology in the context of hemolytic
       disorders <https://doi.org/10.3389/fbioe.2020.00074>`_. *Front. Bioeng. Biotechnol.* 8:74.

Installation
------------
The ``hemekg`` python package can be installed from `PyPI <https://pypi.org/project/hemekg>`_
with the following code in your shell:

.. code-block:: sh

    $ pip install hemekg

The development version can be installed from `GitHub <https://github.com/hemekg/hemekg>`_
with:

.. code-block:: sh

    $ git clone https://github.com/hemekg/hemekg.git
    $ cd hemekg
    $ pip install -e .

Commands
--------
To see all the commands, simply run:

.. code-block:: sh

    $ hemekg

Usage
-----
To get the BEL graph, use the following code:

.. code-block:: python

    >>> import hemekg
    >>> graph = hemekg.get_graph()
    >>> graph.summarize()

Annotations
~~~~~~~~~~~
Auxiliary annotations are located in the hemekg/annotations directory.
These include:

1. TimePoint.
2. Species.
3. Concentration.

More BEL Content
----------------
See `A Listing of Publicly Available Content in the Biological Expression Language (BEL)
<https://cthoyt.com/2020/04/30/public-bel-content.html>`_ on Charles Tapley Hoyt's blog
for more BEL content.
