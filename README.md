# VelsWhisper — сборки

Диктовка голосом в любое приложение: зажали клавишу, сказали, отпустили — текст
появился там, где стоит курсор. Всё считается на вашем компьютере, без облака и
без подписки.

В этом репозитории лежат **только готовые установщики**. Исходный код закрыт.

## Скачать

**Windows 10/11 (64 бита):**
[VelsWhisper-setup.exe](https://github.com/zhidk0/VelsWhisper-releases/releases/latest/download/VelsWhisper-setup.exe) — 620 МБ

Ссылка всегда ведёт на свежую сборку: имя файла не меняется от версии к версии.
Номер версии и контрольная сумма — на [странице релизов](https://github.com/zhidk0/VelsWhisper-releases/releases).

**Mac (только Apple Silicon, M1 и новее):**
[VelsWhisper.dmg](https://github.com/zhidk0/VelsWhisper-releases/releases/latest/download/VelsWhisper.dmg) — 404 МБ

После перетаскивания в «Программы» **обязательно** снимите карантин, иначе macOS скажет
«приложение повреждено»:

```bash
xattr -dr com.apple.quarantine /Applications/VelsWhisper.app
```

## Установка

Пошаговая инструкция с картинками — на платформе AI.ЦЕХ:
https://platform.nickvels.ru/services/velswhisper

Коротко: запустить файл, в окне «Система Windows защитила ваш компьютер» нажать
«Подробнее» → «Выполнить в любом случае» (так Windows предупреждает обо всех
программах без платной подписи разработчика), дальше «Далее» → «Установить».
При первом запуске приложение скачает файлы распознавания речи — 3,7 ГБ, один
раз.
