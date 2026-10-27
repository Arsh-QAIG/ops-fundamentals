## 2026-10-27
- `wsl -l -v`: lists installed Linux distros and their state.
- `cd ~`: moves to the Linux home folder, off the Windows drive.
- `docker run --rm hello-world`: runs a container, deletes it on exit.
- Permission denied on docker.sock: my user wasn't in the docker group until WSL restarted.
- `$$` vs `&&`: `$$` is the shell's PID, `&&` chains commands. I typed the wrong one.