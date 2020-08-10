# Travis CI test repo

### Steps for a successful build
1) Create a ```.travis.yml``` file in the root directory of the project
2) Configure the .travis file with the relevant language, language, version and hooks
    - Hooks include things like ```before_install```, ```install```, ```before_script```,```script``` etc.
3) I added my firstjob file into the script hook because that was the only file i wanted to test during the build 