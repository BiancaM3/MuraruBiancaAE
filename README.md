# MuraruBiancaAE
# Git Clone
git clone https://github.com/BiancaM3/MuraruBiancaAE.git 
<br>
cd MuraruBiancaAE -> change directory
<br>
npm install -> install node package manager
# Install mysql
sudo service mysql status -> testare functionalitate serviciu
<br>
<br>
Configurare utilizator nou:
<br>
sudo mysql -u root -> conectare cu utilizatorul "root"
<br>
<br>
CREATE USER 'username'@'localhost' IDENTIFIED BY 'password';
<br>
GRANT ALL PRIVILEGES ON *.* TO 'username'@'localhost' WITH GRANT OPTION;
<br>
Exit
<br>
<br>
Conectare Server MySql:
<br>
mysql -u username -p
<br>
<br>
Creare baza de date:
<br>
CREATE DATABASE database_name;
<br>
Listare baze de date disponibile:
<br>
SHOW DATABASES;
<br>
<br>
[ Informatie preluata: https://tutoriale.webtech-superheroes.net/configurare-mediu-de-lucru/mysql ]
# Import baza de date
source ~/environment/MuraruBiancaAE/sql/catalog.sql
<br>
# Run Server.js
node server.jr
