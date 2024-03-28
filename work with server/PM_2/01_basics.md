### Before you have to build project
    npm run build

### Run app in prod mode
    pm2 start dist/main.js --name [application_name]

### Run app in dev mode
    pm2 start "npm run dev" --name [myAppName]

### In the code above, You can specify the application_name as you want. To make your application autostart after system reboot, use this command :
    pm2 startup systemd
    pm2 save