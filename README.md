# Coaster
We never work alone

pkg update && pkg upgrade -y
pkg install nodejs git ffmpeg imagemagick wget -y
git clone <your-repo-url> ultimate-bot
cd ultimate-bot
npm install @whiskeysockets/baileys express mongoose qrcode-terminal dotenv
node bot.js
