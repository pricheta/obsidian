### Install package
sudo pacman -S {package_name}

### Remove package
sudo pacman -Rs {package_name}

### Get list of orphaned packages
sudo pacman -Qdtq

### Remove orphaned packages
sudo pacman -Rns $(pacman -Qdtq)
