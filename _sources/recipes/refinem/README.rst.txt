:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'refinem'
.. highlight: bash

refinem
=======

.. conda:recipe:: refinem
   :replaces_section_title:

   A toolbox for improving population genomes.

   :homepage: http://pypi.python.org/pypi/refinem/
   :documentation: https://github.com/dparks1134/RefineM/blob/master/README.md
   
   :developer docs: https://github.com/dparks1134/RefineM
   :license: GPL3 / GPL3
   :recipe: /`refinem <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/refinem>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/refinem/meta.yaml>`_

   


.. conda:package:: refinem

   |downloads_refinem| |docker_refinem|

   :versions: 0.0.25-0, 0.0.24-3, 0.0.24-2
   
   :depends biolib: >=0.0.45
   :depends blast: >=2.6.0
   :depends dendropy: 
   :depends diamond: >=0.9.9
   :depends jinja2: >=2.7.3
   :depends krona: >=2.7
   :depends matplotlib: >=1.4.0
   :depends mpld3: >=0.2
   :depends numpy: >=1.9.0
   :depends prodigal: >=2.6.3
   :depends pysam: 
   :depends python: <3
   :depends scipy: >=1.0.0
   :depends weightedstats: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install refinem

   and update with::

      conda update refinem

   or use the docker container::

      docker pull quay.io/biocontainers/refinem:<tag>

   (see `refinem/tags`_ for valid values for ``<tag>``)


.. |downloads_refinem| image:: https://img.shields.io/conda/dn/bioconda/refinem.svg?style=flat
   :target: https://anaconda.org/bioconda/refinem
   :alt:   (downloads)
.. |docker_refinem| image:: https://quay.io/repository/biocontainers/refinem/status
   :target: https://quay.io/repository/biocontainers/refinem
.. _`refinem/tags`: https://quay.io/repository/biocontainers/refinem?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/refinem/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/refinem/README.html