A bash helper script to append all necessary files to the `App/Db` Makefile.

### Usage:
- Edit the `exclude` array to define which substitution files should be copied to `$(TOP)/db` verbatim instead of munged by MSI. 
- Run the script in `App/Db`.

### Future:
- Add excluded files as stdin
