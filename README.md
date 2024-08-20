sudo apt-get update && sudo apt-get upgrade

# install PgAdmin

sudo apt install curl

sudo curl https://www.pgadmin.org/static/packages_pgadmin_org.pub | sudo apt-key add

sudo sh -c 'echo "deb https://ftp.postgresql.org/pub/pgadmin/pgadmin4/apt/$(lsb_release -cs) pgadmin4 main" > /etc/apt/sources.list.d/pgadmin4.list && apt update'

sudo apt install pgadmin4

sudo apt install pgadmin4-web 

sudo apt upgrade pgadmin4

sudo /usr/pgadmin4/bin/setup-web.sh
