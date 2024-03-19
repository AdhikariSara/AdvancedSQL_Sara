# AdvancedSQL
A template repo for Python, Flask, Postgres, and Jupyter Notebook

Notes: 
- **requirements.txt** should stay where it is. If you move it, you need to update file location in the **Dockerfile**
- _ipython_ for the jupyter notebook is installed via postcreate command in **devcontainer.json**
- **practice.sql** is a sample database. To automatically load a different database, edit the **devcontainer.json** _postcreate_ command. Or simply remove psql-related bash commands
