## Working through CS231n assignments in progress
This repo is for studying the [CS231n course](http://cs231n.stanford.edu/) (spring 2019 version) in self-paced manner. All assignments in one repo. Some imports cleaning was done. Add pipenv environment files.

To recreate virtual environment:
- assuming you have installed pipenv
- pull the repo, cd into it and run `pipenv install`
- at this point should recreate the env needed for the work

To add virtual env kernel to Jupyter:
- Jupyter should be installed for user
- run `pipenv run python -m ipykernel install -- user --name CS231n`
- If use `CS231n`, no need to change kernel inside the notebooks

How to use:
- just work through official course syllabus and have fun!