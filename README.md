# Devcontainer

- [ ] Authenticate with GitHub via ssh.

## Troubleshooting

```sh
# what user is running the script
id -un

# Git settigns
cat ~/.gitconfig

# verify ssh connection to GitHub
ssh -vT git@github.com

# See if kernel is registered
ls /home/codespace/.local/share/jupyter/kernels/
```
