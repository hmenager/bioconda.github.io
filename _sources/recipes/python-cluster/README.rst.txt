:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'python-cluster'
.. highlight: bash

python-cluster
==============

.. conda:recipe:: python-cluster
   :replaces_section_title:

   python\-cluster is a \"simple\" package that allows to create several groups \(clusters\) of objects from a list

   :homepage: https://github.com/exhuma/python-cluster
   :license: GPL / LGPL-2.1
   :recipe: /`python-cluster <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/python-cluster>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/python-cluster/meta.yaml>`_

   


.. conda:package:: python-cluster

   |downloads_python-cluster| |docker_python-cluster|

   :versions: 1.4.1.post1-1, 1.4.1.post1-0, 1.4.1-2, 1.4.1-0, 1.3.3-0
   
   :depends python: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install python-cluster

   and update with::

      conda update python-cluster

   or use the docker container::

      docker pull quay.io/biocontainers/python-cluster:<tag>

   (see `python-cluster/tags`_ for valid values for ``<tag>``)


.. |downloads_python-cluster| image:: https://img.shields.io/conda/dn/bioconda/python-cluster.svg?style=flat
   :target: https://anaconda.org/bioconda/python-cluster
   :alt:   (downloads)
.. |docker_python-cluster| image:: https://quay.io/repository/biocontainers/python-cluster/status
   :target: https://quay.io/repository/biocontainers/python-cluster
.. _`python-cluster/tags`: https://quay.io/repository/biocontainers/python-cluster?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/python-cluster/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/python-cluster/README.html