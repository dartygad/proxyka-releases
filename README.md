# Proxyka

**Proxyka** — прокси для нужных программ Windows: выбранные программы идут через ваш прокси (SOCKS5 / HTTP), остальное работает напрямую, как обычно.

## ⬇️ Скачать

**[Proxyka-Setup.exe — последняя версия](https://github.com/dartygad/proxyka-releases/releases/latest/download/Proxyka-Setup.exe)**
Windows 10 и 11, 64-бит · бесплатно · русский и английский

## Установка за 1 минуту

1. Запустите скачанный файл **Proxyka-Setup.exe**.
2. Если Windows покажет «Система Windows защитила ваш компьютер», нажмите **«Подробнее» → «Выполнить в любом случае»**. Так бывает с новыми программами без платной цифровой подписи.
3. В окне «Разрешить этому приложению вносить изменения?» нажмите **«Да»** — права администратора нужны, чтобы установить сетевой компонент.
4. Нажмите **«Установить»**. В конце Proxyka откроется сама и пошагово покажет: где взять прокси, куда вставить строку прокси и что пускать через него.

## Безопасно для компьютера

- Proxyka **не меняет** сетевые настройки Windows: системный прокси, DNS, маршруты и адаптеры остаются как были.
- Перехват работает, **только пока Proxyka запущена** (открыто окно или значок у часов). Выход из программы — правой кнопкой по значку → «Выход» — и компьютер сразу работает как обычно, без прокси.
- **Удаление:** Параметры → Приложения → Proxyka → Удалить. Убираются служба, сетевой драйвер, правило брандмауэра и автозапуск. Отметьте «Удалить данные приложения», чтобы удалить и настройки.
- Обновления приходят сами и подписаны цифровым ключом: подделку программа не установит.
- Пароли от прокси хранятся зашифрованными средствами Windows и не попадают в журналы.

## Нужны прокси?

Индивидуальные прокси на [px6.net](https://px6.net/?r=1061962) — скидка 5% по промокоду **PROSTO5**. Proxyka умеет импортировать купленные там прокси по API-ключу. *Реклама.*

---

# Proxyka (English)

**Proxyka** sends chosen Windows programs through your proxy (SOCKS5 / HTTP) and leaves everything else direct.

**[⬇️ Download Proxyka-Setup.exe (latest)](https://github.com/dartygad/proxyka-releases/releases/latest/download/Proxyka-Setup.exe)** — Windows 10/11, 64-bit.

1. Run **Proxyka-Setup.exe**.
2. If Windows shows "Windows protected your PC", click **More info → Run anyway** (the app is not yet signed with a paid certificate).
3. In "Do you want to allow this app to make changes?" click **Yes** (admin rights are needed for the network component).
4. Click **Install**. Proxyka opens at the end and walks you through the setup.

Safe by design: Proxyka does not change Windows network settings; interception works only while Proxyka runs (quit from the tray icon and everything is back to normal); uninstall (Settings → Apps → Proxyka) removes the service, network driver, firewall rule and autostart. Updates are signed.

This repository contains only signed installers, the update manifest and the website. Installed apps update themselves from here.
