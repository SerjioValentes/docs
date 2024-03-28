await ctx.reply('Зарегестрироваться', {
        reply_markup: {
          keyboard: [
            [
              {
                text: 'Не выбирать',
                web_app: {
                   url: '',
                },
              },
            ],
          ],
        },
      });
