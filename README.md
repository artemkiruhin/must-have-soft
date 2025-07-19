# Привет
Привет, в этом репозитории собраны приложения из различных сфер, которые я являются маст-хэвом как для обычных пользователей, так и для программистов.

# Маст-хэв

## Офисный пакет
- Microsoft Office (Office Deployment Tool) (см. ***applications***)
- [Microsoft Office](https://gravesoft.dev/office_c2r_links#russian-ru-ru)
- [OnlyOffice](https://www.onlyoffice.com/ru/download.aspx?from=default#docs-enterprise)
- [LibreOffice](https://www.libreoffice.org/download/download-libreoffice/)

## Браузеры
- [Mozilla Firefox](https://www.mozilla.org/ru/firefox/new/)
- [Яндекс браузер](https://browser.yandex.ru/)
- [Google Chrome](https://www.google.com/intl/ru/chrome/safety/)
- [Mozilla Zen Browser](https://zen-browser.app/download/)

## Утилиты
- Rufus (см. ***applications***)
- [AmneziaVPN](https://github.com/amnezia-vpn/amnezia-client)
- [Everything](https://www.voidtools.com/ru-ru/)
- Anydesk (см. ***applications***)
- Фикс Discord (см. ***applications/discord***)
- [Driver Booster](https://ru.iobit.com/driver-booster.php)
- [OBS Studio](https://obsproject.com/download)
- [WinRAR](https://www.win-rar.com/start.html?&L=4)
- [7Zip](https://www.7-zip.org/download.html)
- [Ventoy](https://www.ventoy.net/en/download.html)
  
## Менеджмент, организация пространства
- [Obsidian](https://obsidian.md/download)

## Мессенджеры и социальные ПО
- [Telegram](https://desktop.telegram.org/)
- [WhatsApp](https://www.whatsapp.com/download?lang=ru_RU)

## Прочее
### Курсоры
- [Курсор Windows 11](https://7themes.su/stuff/kursory_windows/windows_11_cursors_concept/7-1-0-1149)


## Дизайн, монтаж и графика
- [Figma](https://www.figma.com/downloads/)
- [Upscayl (*апскейлинг*)](https://upscayl.org/download)

## Системным администраторам
- NIUBI Partition Editor (см. **applications**)
- [Advanced IP Scanner](https://www.advanced-ip-scanner.com/ru/)
- [Advanced PORT Scanner](https://www.advanced-port-scanner.com/)
- [Crystal Disk Info](https://crystalmark.info/en/software/crystaldiskinfo/)

## Программистам
- [Visual Studio Code](https://code.visualstudio.com/download)
- [Node.js](https://nodejs.org/en/download)
- [.NET](https://dotnet.microsoft.com/ru-ru/download/dotnet)
- [Java](https://www.oracle.com/java/technologies/downloads/?er=221886#jdk24-windows)
- [Git](https://git-scm.com/downloads)
- [Postman](https://www.postman.com/downloads/)
- [WAMP.NET](https://wamp.net/)
- [PostgreSQL](https://www.postgresql.org/download/)
- [MongoDB](https://www.mongodb.com/try/download/community)
- [JetBrains Toolbox](https://www.jetbrains.com/ru-ru/toolbox-app/)
- [OpenSSH Server](https://github.com/powershell/win32-openssh/releases)
- [PuTTY](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html)

## Команды

### Massgrave
Активация Windows и Office.

В командной строке запустить:

```cmd
irm https://get.activated.win | iex

```

### Фикс RDP 
1. Находим процессы, связанные с rdp:
```cmd
tasklist /svc | findstr "TermService"

```

2. Завершаем все процессы:
```cmd
taskkill /F /PID <сам пид>

```

3. Запускаем rdp:
```cmd
net start TermService

```