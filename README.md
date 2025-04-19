1. create folder structure
2. initialize git
    `git init .`
3. create .gitignore file
    write this
        venv/
2. create virtual environment
    `python -m venv venv`
    `.\venv\Scripts\Activate.ps1`
3. create requirements.txt
    write all the packages needed e.g.
        pandas
        numpy
        requests
4. install packages under venv
    `pip install -r .\requirements.txt`


Extras:
    Git Operations
        git add . --> (all)
        git add requirements.txt --> (specific file)
        git add -u --> (only modified and deleted, not new files)

        git commit -m "<comment>"