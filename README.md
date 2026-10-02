# 📊 Testin — Django Analytics Web App

[🇷🇺 Инструкция на русском](#-инструкция-по-запуску) | [🇬🇧 Instructions in English](#-getting-started)

---

## 🇷🇺 Инструкция по запуску

### Предварительные требования
Перед началом убедитесь, что на вашем компьютере установлен:
* **Python 3.10+** (не забудьте поставить галочку *«Add Python to PATH»* при установке на Windows).
* **Git**

---

### Пошаговый запуск

#### 1. Клонирование репозитория
Откройте терминал и перейдите в нужную папку:
```bash
git clone https://github.com/trefelova-dev/Testin.git
cd testin
```

#### 2. Создание и активация виртуального окружения
Создайте изолированное окружение:
```bash
python -m venv venv
```

Активируйте его:

##### Windows (PowerShell)
```powershell
.\venv\Scripts\Activate.ps1
```

##### Windows (Git Bash / Command Prompt)
```bash
source venv/Scripts/activate
```

##### macOS / Linux
```bash
source venv/bin/activate
```

#### 3. Установка зависимостей
Обновите менеджер пакетов и установите необходимые библиотеки:
```bash
pip install --upgrade pip
pip install -r requirements.txt
```
*(Если `requirements.txt` отсутствует, установите базовые пакеты: `pip install django requests prettytable`)*.

#### 4. Подготовка базы данных
Примените миграции для инициализации SQLite базы данных:
```bash
python manage.py migrate
```

#### 5. Запуск сервера разработки
Запустите локальный веб-сервер Django:
```bash
python manage.py runserver
```

Готово! Откройте браузер и перейдите по адресу:  
**[http://127.0.0.1:8000/](http://127.0.0.1:8000/)**

---

## 🇬🇧 Getting Started

### Prerequisites
Before running the application, ensure you have:
* **Python 3.10+** installed (check *“Add Python to PATH”* during installation on Windows).
* **Git**

---

### Installation & Setup

#### 1. Clone the repository
Open your terminal and clone the project:
```bash
git clone https://github.com/trefelova-dev/Testin.git
cd testin
```

#### 2. Create and activate a virtual environment
Create a virtual environment:
```bash
python -m venv venv
```

Activate it:

##### Windows (PowerShell)
```powershell
.\venv\Scripts\Activate.ps1
```

##### Windows (Git Bash / Command Prompt)
```bash
source venv/Scripts/activate
```

##### macOS / Linux
```bash
source venv/bin/activate
```

#### 3. Install dependencies
Upgrade pip and install all required packages:
```bash
pip install --upgrade pip
pip install -r requirements.txt
```
*(If `requirements.txt` is missing, run: `pip install django requests prettytable`)*.

#### 4. Apply migrations
Run migrations to set up the local SQLite database:
```bash
python manage.py migrate
```

#### 5. Run the development server
Start the Django development server:
```bash
python manage.py runserver
```

Open your browser and navigate to:  
**[http://127.0.0.1:8000/](http://127.0.0.1:8000/)**
