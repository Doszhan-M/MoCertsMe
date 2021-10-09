# MoCerts

## Инструкции по настройке сервера

### Настройка почтового сервера!
```
Перейти в папку MoCerts/secret. Создать 5 текстовых файла с названием

ADMINS.txt -- Здесь нужно записать почту администратора в виде кортежа: ('John', 'john@example.com')

EMAIL_HOST.txt -- записать smtp сервер почты

EMAIL_HOST_USER.txt -- записать логин от почтового ящика

EMAIL_HOST_PASSWORD.txt -- записать пароль от почтового ящика

SECRET_KEY.txt -- секретный ключ джанго, можно сгенерировать на любом генераторе

```

### Настройка службы оплаты
```
На сайте https://p2p.qiwi.com/ нужно сгенерировать секрет и паблик key. Потребуется только секрет key

Зайти в админ панель -> QiwiToken, заполнить поле secret_key значением секрет key полученным на сайте

```