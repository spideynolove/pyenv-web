# pyenv-web
Contain py-version, test file, some considerations, requirement libs (FOR MY WEB DEVELOPMENT)

# Notes:
- Easiest way to install pyenv: https://github.com/pyenv-win/pyenv-win#power-shell
- Starting tutorials https://www.youtube.com/watch?v=HTx18uyyHw8
- pyenv install 3.9.13
- pyenv install 3.7.9 (use this version to create venv)

- pyenv shell 3.9.13 (use this version to install pipenv, because encountering bug when installing pipenv in 3.7.9)

- pip install pipenv pipenv docs:

    + https://realpython.com/pipenv-guide/
    + https://pipenv-fork.readthedocs.io/en/latest/basics.html#specifying-versions-of-python

- pipenv --python 3.7.9
- active venv then:
    + using "pip install lib-name"
    + or "pip install -r requirements.txt"
