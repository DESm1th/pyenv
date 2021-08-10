Here are the steps to create a new pyenv module:

1. Clone my copy of pyenv in the destination folder:
      git clone git@github.com:DESm1th/pyenv.git

2. Create the shims and versions folder inside the pyenv folder and set correct
   permissions to allow multiple users to work from the directories.
      - mkdir {shims,versions}
      - chown localadmin:kimel {shims,versions}
      - chmod 3775 {shims,versions}

3. Clone my copy of pyenv-virtualenv to the 'plugins' folder inside pyenv
      git clone git@github.com:DESm1th/pyenv-virtualenv.git

4.
