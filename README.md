# GRPAdmin

Игровой скрипт, призванный облегчить повседневные задачи администратора Gambit Role Play. 

## Установка

Сам скрипт и папку lib перенести в папку moonloader.

### Требования

Moonloader v.025
lib: SAMP.events, sha1, basexx 

## Функции

v.1

- Ряд полезных команд, их список будет описан ниже.
- Скрытие активности хелперов [S] (выход на дежурство, ответы, кроме чата).
- Вынос некоторого системного чата в отдельную область [A] (Жалобы, наказания администрации, античит) 
[пока что корректное отображение только с разрешением 1920x1080]
- Архивация всего скрытого\вынесенного чата в чатлоге, ничто не пропадет бесследно. 

v.2

- Полный автологин в игру(пароль, Google Auth., админ-пароль)
- Уведомление в чате при передаче денег с одинаковыми IP адресами.

## Команды

```
/acmd - список команд
/pk id - установить игроку Player Kill. (/jail ID 60 PK`ed)
/gh id - телепортация игрока к себе с поднятием из стадии (/aheal + /gethere)
/as id - спавн игрока с поднятием из стадии (/aspawn + /aheal)
/ah id - быстрый /aheal
/hp id - установить игроку 100 HP (/sethp ID 100)
/ak id - кик игрока за афк без паузы (/kick ID AFK without ESC)
```

# В планах

- Добавить в скрипт Wallhack\Nametag и\или увеличить прорисовку никнеймов.
- Создать меню внутреигровых настроек с возможностью активации\деактивации некоторых функций.
- Переписать корректное отображение чата под все разрешения (важно!)
- Переписать весь основной код скрипта, оптимизировав его работу



