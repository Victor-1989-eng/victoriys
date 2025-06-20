# Telegram Бот "Погода"

Этот бот показывает текущую погоду по команде `/weather <город>` с помощью API OpenWeatherMap.

## 📦 Установка

1. Клонируй репозиторий или распакуй ZIP:
```
pip install -r requirements.txt
```

2. Создай файл `.env` или передай переменные окружения:

- `BOT_TOKEN` — токен от @BotFather
- `WEATHER_API_KEY` — ключ с https://openweathermap.org

3. Запусти бота:
```
python bot.py
```

## 🚀 Деплой на Render

1. Зайди на [Render.com](https://render.com)
2. Подключи GitHub-репозиторий или загрузи ZIP
3. Укажи:
- Build Command: `pip install -r requirements.txt`
- Start Command: `python bot.py`
- Переменные окружения: `BOT_TOKEN`, `WEATHER_API_KEY`
