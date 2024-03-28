## Nginx installing and settings 
[ustanovka i nastroyka nginx](https://firstvds.ru/technology/ustanovka-i-nastroyka-nginx)

[simple-start-next-js-app-with-pm2-on-nginx](https://consultapp.ru/simple-start-next-js-app-with-pm2-on-nginx/)


После стандартной установки nginx запуск службы (service) можно выполнить командой:

    sudo systemctl start nginx

Автозапуск nginx после перезагрузки системы включается так:

    sudo systemctl enable nginx

Статус службы можно проверить этой командой:

    sudo systemctl status nginx


Посмотреть подробный отчёт о работе nginx в журналах (логах) службы (об этом чуть позже), в терминале или с помощью команды

    sudo journalctl -u nginx

    sudo systemctl restart nginx