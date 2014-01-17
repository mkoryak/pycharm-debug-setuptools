pycharm-debug-setuptools
========================

a repo for setuptools to grab the pycharm-debug.egg for debugging python apps from IntelliJ / PyCharm

add to setup.py: 

```
dependency_links=[
  'https://github.com/mkoryak/pycharm-debug-setuptools/raw/master/pycharm-debug.egg'
]
```
