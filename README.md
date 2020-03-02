# ntnu-projects
Collection of repos created during various NTNU courses.

#### Setup
Clone the repository using:  
```
git clone --recurse-submodules https://www.github.com/patrikkj/ntnu-projects.git
```

If the `--recurse-submodules` flag is omitted, submodules will not be cloned.
To fix this, run:
```
git submodule update --init --remote
```

If you lack read access to any submodule, all submodules will initially be empty.
Data will be fetched for public repos, but git will automatically stage all submodule files for deletion.
In order for files to appear, navigate to `ntnu-projects` and check out each submodules tracked branch using:
```
git submodule foreach "git checkout --no-guess"
```
