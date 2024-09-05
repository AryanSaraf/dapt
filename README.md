### dapt
- This script is a simple frontend to Debian's apt. It performs chains of commands that I personally tend to use in conjunction with each other.
- Place this script somewhere in your PATH and make it executable: `chmod +x dapt`.
- Change the shell as needed in the shebang line. Default: `bash`.
- The default executor is "doas". Change it in the script by replacing it with your desired tool, e.g. `executor="sudo -i -u user2"`.
- Run `dapt` with no arguments to view the version and help menu.
