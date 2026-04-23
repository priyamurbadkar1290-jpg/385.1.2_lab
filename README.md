# Creating a virtual ENV (venv)
1. Create your project folder and make sure you terminal is at the root of the project
2. To create virtual env, run in terminal `python3 -m venv venvname`

# Using a virtual env
- If you dont activate your virtual env, when you install packages they wont be env specific
- To activate mac: `source venvname/bin/activate`
- To activate windows `venvname/bin/activate`
- To deactivate `deactivate`

# Github with venv
- NOT ALL FILES SHOULD BE PUSHED TO GITHUB
- create a `.gitignore`
- list all folders to be ignored by github (venv folder)
- ALWAYS ignore right away, once a directory is tracked its very hard to untrack

# To save the list of installed packages:
- Run command `pip freeze > requirements.txt`
- creates requirements.txt file with all required packages for this program