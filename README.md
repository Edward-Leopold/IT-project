## Запуск проекта
### Запуска сервера backend
Запуск проекта осуществляется после того, как вы клонировали репозиторий себе на локальную машину. 
Для запуска backend используется сервер Flask

Установите виртуальную среду python - venv в корень проекта
```
python -m venv venv
```

Затем запустите venv с помощью команды (windows):
```
.\venv\Scripts\activate
```
для mac/linux
```
source .venv/bin/activate
```

Выполните установку зависимостей
```
pip install -r requirements.txt
```

Затем запуститет локальный сервер
```
python main.py
```

### Запуск vite для сборки frontend'а
Из корня проекта перейдите в папку фронтенда
```
cd frontend
```

Установите зависимости через npm:
```
npm install
```

Запустите сервер фронтенда
```
npm run dev
```
