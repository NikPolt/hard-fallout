# Nuclear 14 / Corvax Forge Nuclear / Omega Fallout

**Omega fallout** - Сервер-форк corvax forge с добавкой своего контента.

Omega Fallout может похвастаться своей стойкой структурой либерально-демократической идеологии. А именно свободой критики к администрации и серверу. А так же наличие эротического контента.

Сборка включает в себя весь контент Corvax Forge и изменения, добавленные кодерами Omega Fallout. К примеру, перки, китайский контент и свои карты.

## Ссылки
- [Discord](https://discord.gg/9b3HgraBrH) (официальное сообщество)

## Сборка

### Требования
- Git
- .NET SDK 9.0.101

### Windows
1. Клонируйте репозиторий:
   ```sh
   git clone https://github.com/Forge-Station/nuclear-14.git
   ```
2. Инициализируйте подмодули:
   ```sh
   git submodule update --init --recursive
   ```
3. Соберите проект:
   ```sh
   Scripts/bat/buildAllDebug.bat
   ```
4. Запустите клиент и сервер:
   ```sh
   Scripts/bat/runQuickAll.bat
   ```
5. Подключитесь к localhost через клиент

### Linux
Аналогично Windows, но используйте скрипты `.sh`:
```sh
Scripts/sh/buildAllDebug.sh
Scripts/sh/runQuickAll.sh
```

### MacOS
Теоретически аналогично Linux, но не тестировалось

## Лицензия
Подробная информация о лицензировании кода и ассетов доступна в [LEGAL.md](./LEGAL.md). Основные положения:
- Код: AGPLv3
- Ассеты: индивидуальные лицензии (проверяйте meta.json)
- Обязательно соблюдение авторских прав
