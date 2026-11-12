# Политика конфиденциальности Winsland

Обновлено: 12 ноября 2026 года

Winsland — это «остров» вверху экрана Windows: музыка, уведомления, буфер обмена, запись экрана, ИИ и другие функции. Эта страница объясняет, какие данные Winsland использует и куда они уходят.

## Коротко

- У Winsland нет своего сервера и нет аналитики. Разработчик не получает ваших данных.
- Настройки, буфер обмена, напоминания, записи экрана и снимки хранятся только на вашем компьютере.
- В интернет Winsland обращается только ради функций, которые вы видите. Ниже перечислено, куда и что именно отправляется.

## Что хранится на компьютере

- **Настройки, свои темы, напоминания** лежат в файле `%APPDATA%\Winsland\settings.json`.
- **История буфера обмена и полка файлов** тоже хранятся локально и стираются, когда вы их очищаете.
- **Записи экрана и снимки** сохраняются в папку, которую вы выбираете сами.
- **Ключи API для своего ИИ** хранятся зашифрованными средствами Windows (DPAPI) и расшифровываются только под вашей учётной записью.

## Что уходит в интернет

| Функция | Куда | Что отправляется |
|---|---|---|
| Погода | open-meteo.com | Название города, которое вы указали |
| Текст песни | lrclib.net | Название трека, исполнитель и длительность |
| Вкладка Gemini | gemini.google.com | То, что вы вводите на сайте Gemini; действует политика Google |
| Свой ИИ по API (Премиум) | Выбранный вами сервис: Anthropic, OpenAI, xAI, Google, DeepSeek, OpenRouter или ваш адрес | Ваши сообщения, вложения и ваш ключ API |
| Веб-вкладки | Сайты, которые вы сами добавили | Как в обычном браузере |

Winsland не продаёт и не передаёт данные третьим лицам, кроме перечисленных выше сервисов, к которым вы обращаетесь сами.

## Доступ к устройствам

- **Микрофон и звук системы** используются только во время записи экрана, если вы их включили.
- **Камера** используется только для окошка камеры, если вы его открыли.
- **Клавиши громкости и Caps Lock** Winsland видит, чтобы показывать их на острове. Другие нажатия не записываются и никуда не отправляются.
- **Уведомления Windows** читаются, чтобы показать их на острове. Они никуда не отправляются.

## Дети

Winsland не предназначен для сбора данных о детях и не собирает их.

## Связь

Вопросы о конфиденциальности: https://github.com/delltrxxxx-hub/winsland/issues

---

# Winsland privacy policy

Updated: November 12, 2026

Winsland has no server of its own and no analytics; the developer receives none of your data. Settings, clipboard history, reminders, screen recordings and screenshots stay on your computer. API keys are encrypted with Windows DPAPI.

Winsland only goes online for the features you use: the weather (city name to open-meteo.com), lyrics (track title, artist and length to lrclib.net), the Gemini tab (gemini.google.com, under Google's policy), your own AI by API with Premium (your messages and key go to the provider you chose), and web tabs you add yourself.

The microphone and system sound are used only while recording the screen, the camera only for the camera window. Volume and Caps Lock keys are seen only to show them on the island; Windows notifications are read only to show them on the island. Nothing is sold or shared with third parties beyond the services listed above.

Contact: https://github.com/delltrxxxx-hub/winsland/issues
