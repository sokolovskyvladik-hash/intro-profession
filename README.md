# intro-profession

Практическая работа «Репозитории и интеграции».

## Установка

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
pip install notebook
jupyter notebook
```

Откройте `rest_api_demo.ipynb`. В ветке `master` ключ вводится при запуске ячейки через скрытый ввод.

## Ветка env-feature

Для локального запуска варианта с переменной окружения скопируйте шаблон и заполните его своим ключом:

```bash
cp .env.example .env
```

Замените значение `OMDB_API_KEY` в `.env`. Файл `.env` исключён из Git через `.gitignore` и не должен попадать в коммиты. Ветка `env-feature` является демонстрационной и не объединяется с `master`.
