
## Commands learned
- git config --global       → set identity
- git init                  → initialize repo
- git status                → check working tree
- git add                   → stage changes
- git diff --staged         → preview commit
- git commit -m             → save snapshot
- git log --oneline --graph → view history
- git show HEAD             → inspect last commit
- git branch -m main        → rename branch
- git remote add origin     → connect to GitHub
- git push -u origin main   → push + set upstream
- ssh-keygen -t ed25519     → generate SSH key pair
- ssh -T git@github.com     → test SSH connection

## Key concepts
- Working directory → Staging Area → Local Repo → GitHub
- .gitignore prevents build artifacts from being tracked
- SSH key pair: private key stays local, public key goes to GitHub
- origin is just an alias for the remote URL
- Dotfiles (like .gitignore) are hidden by default in Linux

## Linux facts learned
- ls -la shows hidden files
- rm -f force deletes without prompt
- ./ runs executables from current directory
- authorized_keys is for incoming SSH, id_ed25519 is for outgoing
- Git used 12 CPU threads to compress objects on push
