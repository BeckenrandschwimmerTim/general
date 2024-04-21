Download a file from github
```
cd /DIR
curl https://raw.githubusercontent.com/BeckenrandschwimmerTim/REPOSITORY/main/FILENAME -o FILENAME
```
Execute a file from github without downloading it
```
bash -c "$(wget -qLO - https://raw.githubusercontent.com/BeckenrandschwimmerTim/REPOSITORY/main/FILENAME)"
```
