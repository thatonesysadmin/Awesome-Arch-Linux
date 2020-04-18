### Essential Pacman Usage

| Command | Function |
|---|---|
| -Syu | Update remote package database and install updates | 
| -Ss | Query remote repository for packages containing specific package |
| -R | Remove a specified package from the local system |
| -Rs | Same as `-R`, but removes dependencies |
| -Rns | Same as `-Rs`, but removes system config files | 
| -Q | List currently installed packages on the local system |
| -Qe | Same as `-Q` only shows packages that you explicitly installed |
| -Qeq | Same as `-Qe`, but only outputs the program name |
| -Qn | Lists all installed packages from the main repository |
| -Qm | Lists all installed packages from AUR |
| -Qdt | List dependencies that are no longer needed (orphans) |
| -Qs | Query the local system to see if a specific package is installed |
| -Qi | Query the local database for detailed info on a specific package |
| -Si | Query the remote database for detailed info on a specific package |
| -Sc | Removed cached versions of packages that are no longer needed |

---

### Configuration Options

These options can be added to your `pacman.conf`

| Option | Function |
|---|---|
| Color | Colorize and format text output |
| CheckSpace | Check disk space before installing packages or updates |
| VerbosePkgLists | More verbosity when installing and updating packages |
| ILoveCandy | Easter egg that changes look of progress bar |

