:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'irida-uploader'
.. highlight: bash

irida-uploader
==============

.. conda:recipe:: irida-uploader
   :replaces_section_title:

   Sequence file uploader for IRIDA

   :homepage: https://github.com/phac-nml/irida-uploader
   :documentation: https://irida-uploader.readthedocs.io/en/latest
   
   :license: APACHE / Apache Software License
   :recipe: /`irida-uploader <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/irida-uploader>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/irida-uploader/meta.yaml>`_

   


.. conda:package:: irida-uploader

   |downloads_irida-uploader| |docker_irida-uploader|

   :versions: 0.3.0-0, 0.2.1-0, 0.1-0
   
   :depends appdirs: >=1.4.3
   :depends cerberus: 
   :depends python: >=3.5.*
   :depends rauth: >=0.7.3
   :depends requests: >=2.21.0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install irida-uploader

   and update with::

      conda update irida-uploader

   or use the docker container::

      docker pull quay.io/biocontainers/irida-uploader:<tag>

   (see `irida-uploader/tags`_ for valid values for ``<tag>``)


.. |downloads_irida-uploader| image:: https://img.shields.io/conda/dn/bioconda/irida-uploader.svg?style=flat
   :target: https://anaconda.org/bioconda/irida-uploader
   :alt:   (downloads)
.. |docker_irida-uploader| image:: https://quay.io/repository/biocontainers/irida-uploader/status
   :target: https://quay.io/repository/biocontainers/irida-uploader
.. _`irida-uploader/tags`: https://quay.io/repository/biocontainers/irida-uploader?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/irida-uploader/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/irida-uploader/README.html