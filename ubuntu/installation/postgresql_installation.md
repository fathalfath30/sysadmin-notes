### PostgreSQL Installation

```shell script
# add postgre repository
sudo sh -c 'echo "deb http://apt.postgresql.org/pub/repos/apt $(lsb_release -cs)-pgdg main" > /etc/apt/sources.list.d/pgdg.list'

# Import postgre repo *signing key*
sudo wget --quiet -O - https://www.postgresql.org/media/keys/ACCC4CF8.asc | sudo apt-key add -

# update repository cache :
sudo apt-get update

# install latest version of postgresql
sudo apt-get install postgresql
```
