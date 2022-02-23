# AIS-Seminar


## Terminal:

<br/>

| Action | Command for MacOS |
| --- | --- |
| Open Jupyter | ```sudo jupyter notebook --allow-root ```|
| Change browser | **Create a notebook configuration file:**<br/>```jupyter notebook --generate-config``` <br/><br/> **Open jupyter_notebook_config.py:**<br/>```open /Users/angelwang/.jupyter/jupyter_notebook_config.py``` <br/><br/> **Add:**<br/>```c.NotebookApp.browser='open -a /Applications/Google\ Chrome.app %s'```|

<br/>

Source:
>https://jupyter-notebook.readthedocs.io/en/stable/public_server.html
