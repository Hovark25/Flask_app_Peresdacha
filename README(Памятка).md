
виртуальное окружение:
   ```bash
   python -m venv .venv

   .venv\Scripts\activate

   ```
зависимости
   ```bash
   pip install -r requirements.txt
   ```

Запуск 
   ```bash
   python app.py
   ```
   


 http://127.0.0.1:5000




- **Фреймворк:** Flask
- **Шаблоны:** Jinja2 (файлы в `templates/` и базовый `base.html`)
- **База данных:** SQLite через SQLAlchemy (файл `app.db`)
- **Аутентификация:** Flask-Login, регистрация/вход/выход
- **Хеширование паролей:** `werkzeug.security.generate_password_hash`
- **Проверка пользователя (существующего):** в маршруте `/register`


- `app.py` — приложение, модели, маршруты
- `templates/` — HTML-шаблоны Jinja2
- `static/style.css` — стили
