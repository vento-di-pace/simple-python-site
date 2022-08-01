# simple-python-site
Простой сайт на Python (Flask+Jinja2)

Инструкция по запуску в ОС Windows:
1) Скачать git по ссылке:
https://github.com/git-for-windows/git/releases/download/v2.37.1.windows.1/Git-2.37.1-64-bit.exe
И установить.

2) Скачать интерпретатор Python по ссылке:
https://www.python.org/ftp/python/3.10.5/python-3.10.5-amd64.exe
И установить.

3) Создать в проводнике каталог, где будет храниться приложение

4) Открыть терминал (приложение Комнадная строка) и в нем выполнить команду:
cd C:\Каталог, созданный на шаге 3.

5) Склонировать (читай скачать) приложение командой в терминале:
git clone https://github.com/vento-di-pace/simple-python-site.git

6) Перейти в каталог с приложением, выполнив команду в терминале:
cd C:\Каталог, созданный на шаге 3\simple-python-site

7) Создать виртуальное окружение для приложения командой (в терминале):
python -m venv venv

8) Активировать виртуальное окружение командой в терминале:
source venv\bin\activate.bat

9) Обновить программу установки пакетов PIP командой в терминале:
pip install --upgrade pip

10) Установить пакеты, необходимые для работы приложения командой в терминале:
pip install -r requirements.txt

11) Запустить приложение комнадой в терминале:
python wsgi.py
Пока работает терминал - работает программа и сайт.
Для остановки программы нажать Ctrl+C (латинская C)

Теперь можно ковырять код))
