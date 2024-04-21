# Download a file from github
```
cd /DIR
curl https://raw.githubusercontent.com/BeckenrandschwimmerTim/REPOSITORY/main/FILENAME -o FILENAME
```
## Examples
### misc.func
```
https://raw.githubusercontent.com/BeckenrandschwimmerTim/proxmox/main/misc/main.func -o misc.func
```
# Execute a file from github without downloading it
```
bash -c "$(wget -qLO - https://raw.githubusercontent.com/BeckenrandschwimmerTim/REPOSITORY/main/FILENAME)"
```
or
```
wget -O - https://github.com/OpenMediaVault-Plugin-Developers/packages/raw/master/install | bash
```
