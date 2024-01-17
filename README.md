# xero-arch-repo

The Arch repository with all the tools and stuff needed for XeroLinux.



# How To Add Manually:

1. Add this to `/etc/pacman.conf`:
```
[xero-arch-repo]
SigLevel = Optional DatabaseOptional
Server = https://raw.githubusercontent.com/XeroLinuxDev/$repo/main/$arch
```

2. Run: `sudo pacman -Syy`
