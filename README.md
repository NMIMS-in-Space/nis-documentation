# NMIMS in Space Documentation
[![readthedocs build status](https://readthedocs.org/projects/nis/badge/?version=latest)](https://nis.readthedocs.io/en/latest/)
[![Website nis.readthedocs.io](https://img.shields.io/website-up-down-green-red/http/nis.readthedocs.io.svg)](https://nis.readthedocs.io/)
[![made-with-sphinx-doc](https://img.shields.io/badge/Made%20with-Sphinx-1f425f.svg)](https://www.sphinx-doc.org/)
[![GitHub license](https://img.shields.io/github/license/NMIMS-in-Space/documentation.svg)](https://github.com/NMIMS-in-Space/documentation/LICENSE)

## Building it
  * pip install sphinx (for build)
  * pip install sphinx_rtd_theme (theme)
  * (cd to project dir)
  * sphinx-quickstart
  * change in conf.py => html_theme = 'sphinx_rtd_theme'
  * make html 
  
  
## Dependencies
  * pip install recommonmark
  * change in conf.py => extensions = ['recommonmark']
