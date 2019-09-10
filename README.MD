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

Some notes to consider:
- Probably, the best way to go will be to fork the repo and add my original repo as upstream remote. So you can fetch the changes from my repo and do whatever you want inside your fork. [This link](https://help.github.com/en/articles/configuring-a-remote-for-a-fork) should help
- also while working through assignment, it is better to copy original file, rename it with something like solution added to filename and work inside your own copy. So, there will be no conflicts while pulling new changes from original repo