# atmrpackage
**R** package implementing a workflow with GitHub Actions using [r-lib/actions](https://github.com/r-lib/actions).


## Build and Installation


### Linux
```sh
Rscript.exe -e 'devtools::install_github("EngineerDanny/atmrpackage")'
```

## GitHub Actions Workflow
- Checks for a successful build on Linux. </br>
  **Using:**
    - r-lib/actions/setup
    - r-lib/actions/setup-r-dependencies
    - r-lib/actions/check-r-package
    
- Announces Completion </br>
  **Using:**
    - run: echo "All checks are completed"
