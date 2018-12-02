.. image:: https://travis-ci.com/PHPirates/tikz-collection.svg?branch=master
    :target: https://travis-ci.com/PHPirates/tikz-collection

---------------
TikZ Collection
---------------

Simple (block) schemas
----------------------

.. raw:: html

    <img src="results/schema.png" width="400px">

Contour plots
-------------


.. raw:: html

    <img src="results/contour-plot.png" width="400px">


Unit 'circles'
--------------

.. raw:: html

    <img src="results/unit-spheres.png" width="400px">

Drawing points on a circle
--------------------------

.. raw:: html

    <img src="results/points.circe.PNG" width="400px">

Markov Chain
------------

.. raw:: html

    <img src="results/markov-chain.png" width="400px">

Graphs
------

.. raw:: html

    <img src="results/graph.png" width="400px">

Tree
------------

.. raw:: html

    <img src="results/tree.png" width="400px">

Combinatorial Graphs
------------

.. raw:: html

    <img src="results/combinatorial.png" width="400px">
    
----------------------------
How to include TikZ pictures
----------------------------

Include the package ``tikzscale``, then put in a file ``stuff.tikz``

.. code:: tex

    \begin{tikzpicture}
        ...
    \end{tikzpicture}
    
and in your main LaTeX file:

.. code:: tex

    \begin{figure}
        \input{stuff.tikz}
        \caption{Description}
        \label{fig:stuff}
    \end{figure}
