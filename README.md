# Trading_Bot
Bot &amp; Script for Online Trading

Vai direttamente con la STRATEGIA 2, se qualche problema ripercorri la 1

STRATEGIA 1
oppure invece di usare yarn usi npm che e’ meglio perche yarn non lo installa bene, poi non si trova

install CURL
install NODE

install YARN
 			mettere nel file 
sudo nano ~/.bashrc
alias nodejs=’node’

yarn add gdax-trading-toolkit

STRATEGIA 2
sudo apt install curl
curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash - sudo apt-get install -y nodejs
sudo apt-get install -y build-essential

npm install --save gdax-trading-toolkit
npm install --save node-telegram-bot-api
export NODE_PATH=/usr/local/node_modules (include i moduli che ho installato nell’ambiente di Node)

node fill2.js


GitHub Whatsapp Bot e Trading Bot
npm install -g gdax tradingtoolkit --> non usare -g perche fa global, installa invece con -s per salvarlo nel proprio in the local node_modules folder
npm init crea un nuovo package