Useful Bash Things
-

```#complete version which takes into account any bash source file location
DIR="${BASH_SOURCE%/*}"
if [[ ! -d "$DIR" ]]; then DIR="$PWD"; fi
. "$DIR/config.sh"```
