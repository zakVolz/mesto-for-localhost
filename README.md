https://zakvolz.github.io/mesto-for-localhost/
# 'Mesto for localhost'
Одностраничный сайт, который подгружает/изменяет профиль пользователя с сервера и загружает с сервера и показывает карточки с фото и названием.
[Посмотреть на GitHub Pages](https://zakvolz.github.io/mesto-for-localhost/)

Чтобы развернуть проект у себя на ПК необходимо установить [Git](https://git-scm.com/) и [Node.js с NPM](https://nodejs.org/en/)

В терминале Git Bush нужно выполнить следующие команды:
```
git clone https://github.com/zakVolz/mesto-for-localhost.git # клонирует данный репозиторий
cd mesto # переходим в папку репозитория
npm install # установит все зависимости из package.json
```

Далее выполняем сборку:
```
npm run dev # режим разработки, запускает локальный сервер и в реальном времени следит за файлами, обновляя страницу при изменениях.

# ИЛИ

npm run build # сборка проекта на продакшн
