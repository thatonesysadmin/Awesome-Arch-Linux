### Essential Pacman Usage

| Command | Function |
|---|---|
| -Syu | Update the remote package database and install updates for installed
packages |
| -Ss | Query the remote repository for packages containing specific search
criteria |
| -R | Remove a specified package from the local system |
| -Rs | Remove a specified package and its dependencies from the local system |
| -Rns | Remove a specified package, dependencies, and system config files from
the local system |
| -Q | List currently installed packages on the local system |
| -Qe | List currently installed packages on local system that you explicitly
installed |
| -Qeq | Same as `-Qe`, but only outputs the program name |
| -Qn | Lists all installed packages from the main repository |
| -Qm | Lists all installed packages from AUR |
| -Qdt | List dependencies that are no longer needed (orphans) |
| -Qs | Query the local system to see if a specific package is installed |
| -Qi | Query the local database for detailed info on a specific package |
| -Si | Query the remote database for detailed info on a specific package |
| -Sc | Removed cached versions of packages that are no longer needed |

### Configuration Options

These options can be added to your `pacman.conf`

| Option | Function |
|---|---|
| Color | Colorize and format text output |
| CheckSpace | Verify there is enough disk space to install a specific package
or update |
| VerbosePkgLists | More verbosity when installing and updating packages |
| ILoveCandy | Easter egg that changes look of progress bar |

