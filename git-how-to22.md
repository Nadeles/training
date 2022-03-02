# **Как создать ssh-ключ**

Команды в терминале:
* *ssh-keygen -t ed25519 -C "email"*
* *eval "$(ssh-agent -s)"*
* *ssh-add /directory/**File***

# **Как добавить ключ в аккаунт на ГитХаб**

Перейти [сюда](https://github.com/settings/keys)
Кликнуть на **New SSH key**, затем **Add SSH key**
Вставить публичный ключ

# **Как склонировать репозиторий**

Скопировать ссылку по SSH на GitHub
*git clone **ссылка** *
