git clone https://github.com/anefzaoui/rocketchat-emoji-bulk-upload.git - установка скрипта  
cd rocketchat-emoji-bulk-upload - переход в папку со скриптом
npm install - установка зависимости
ROCKETCHAT_SERVER_URL=https://your-rocketchat-server-url 
ADMIN_USERNAME=your-admin-username
ADMIN_PASSWORD=your-admin-password
в папку .env
node import-custom-emojis.js - запуск скрипта
