### How to send message to user
### POST method:
    https://api.telegram.org/bot<token>/sendMessage?chat_id=<chat_id>

    {
        "text": "<b>112312</b> sdf sdf ",
        "parse_mode": "html", // MarkdownV2 | html | Markdown
        "disable_notification": false, //without notification sound
        "url": "http://www.google.com",
        "protect_content": true,
        "reply_markup": { // InlineKeyboardMarkup | ReplyKeyboardMarkup | ReplyKeyboardRemove | ForceReply
            "inline_keyboard": 
                [
                    [
                        {
                            "text": "Выбрать",
                            "callback_data": "yes"
                        }
                    ],
                    [
                        {
                            "text": "Не выбирать",
                            "callback_data": "no"
                        }
                    ]
                ]
        }
    }

