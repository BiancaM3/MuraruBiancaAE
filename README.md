# MuraruBiancaAE
# Git Clone
git clone https://github.com/BiancaM3/MuraruBiancaAE.git
cd MuraruBiancaAE -> change directory
npm install -> install node package manager
# Install mysql
sudo service mysql status -> testare functionalitate serviciu

Configurare utilizator nou:
sudo mysql -u root -> conectare cu utilizatorul "root"
CREATE USER 'username'@'localhost' IDENTIFIED BY 'password';
GRANT ALL PRIVILEGES ON *.* TO 'username'@'localhost' WITH GRANT OPTION;
Exit

Conectare Server MySql:
mysql -u username -p

Creare baza de date:
CREATE DATABASE database_name;

Listare baze de date disponibile:
SHOW DATABASES;

[ Informatie preluata: https://tutoriale.webtech-superheroes.net/configurare-mediu-de-lucru/mysql ]
