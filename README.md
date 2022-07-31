1° Comando
pkg upgrade -y && pkg update -y && pkg install python -y && pkg install nodejs-lts -y && pkg install nodejs -y && pkg install git -y && pkg install ffmpeg -y && pkg install wget -y

#########################

Se você pretende utilizar o Heroku, já pode utilizar o comando abaixo, para agilizar o processo futuramente 

npm i -g npm@6 && npm i heroku -g

#########################

2° Comando
termux-setup-storage

3° Comando
cd /sdcard/

4° Comando
git clone https://github.com/rafael-ofc/bot-fox.git

5° Comando
cd bot-fox

6° Comando
sh start.sh