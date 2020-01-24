# NMIMS in Space Documentation
<a href="https://nis.readthedocs.io/en/latest/" alt="readthedocs build status">
<img src="https://readthedocs.org/projects/nis/badge/?version=latest&style=plastic" />
</a>

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
