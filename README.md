# ntnu-projects
Collection of repos created during various NTNU courses.

#### Quick setup
Run the following commands:
```sh
git clone --recurse-submodules https://www.github.com/patrikkj/ntnu-projects.git 
git -C ntnu-projects submodule foreach 'git checkout master'
```
All submodules which you have read access to will now be in their respective `master` branches.

##### Note:
If the `--recurse-submodules` flag is omitted, submodules will not be cloned.
To fix this, navigate to `ntnu-projects` and run:
```
git submodule update --init --remote
```

