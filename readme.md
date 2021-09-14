
# Installation guide

1. cd to current dir
2. run `pip install --use-feature=in-tree-build -I -e .`  

* -I flag - will reinstall packages even with same version number
* -e flag - will create a link to directory - every change will be reflacted in package
* notice the *MANIFEST.in* file as it contains directories to exclude

# Usage
1. Open a python shell
2. run `from textinsights_actual import textinsights_actual`.  
   There should be a line saying - *"im from the textinsights_common.py inside the textinsights_common package"*