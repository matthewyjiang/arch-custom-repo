# arch-custom-repo

Add this repo to your system:
```bash
echo -e '\n[arch-custom-repo]\nSigLevel = Never\nServer = https://repo.matthewyjiang.com/$arch\n' | sudo tee -a /etc/pacman.conf && sudo pacman -Syy
```

## List of packages and versions:
- git-credential-1password-git r37.3c31135-1
- git-credential-1password-git-debug r37.3c31135-1
