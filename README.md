# Telegram Бот "Погода" (Render Deployment)

Этот бот показывает текущую погоду по команде `/weather <город>` с помощью API OpenWeatherMap.

## 🚀 Деплой на Render

1. Создай репозиторий `victoriys` на GitHub и закинь туда файлы.
2. Перейди на [Render.com](https://render.com) и нажми **New Web Service**.
3. Выбери свой репозиторий `victoriys`.
4. В настройках укажи:
   - **Build Command:** `pip install -r requirements.txt`
   - **Start Command:** `bash start.sh`
5. Добавь переменные окружения:
   - `BOT_TOKEN` — токен от @BotFather
   - `WEATHER_API_KEY` — ключ с https://openweathermap.org
6. Нажми **Create Web Service**.

Бот будет автоматически запускаться в облаке.
