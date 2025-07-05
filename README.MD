# Data Explorer

This app exposes different parts of the Seaborn/Matplotlib/Pandas APIs via a GUI aiming to make interacting with and exploring data more intuitive and natural for the average user. The app primarily targets users new to python and its data science/visualisation packages.

The app aims to be extensible by plugins - see plugins/basic_plugin.py - however, the API may evolve over time. The app is currently in very early stages, but most essential functionality has been implemented.

## Quick Setup
```
git clone --depth=1 https://github.com/karrablaster123/dataexplorer.git
pip install -e . OR pip install .
dataexplorer

OR 

pip install data-explorer-qt
dataexplorer
```
