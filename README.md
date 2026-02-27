### Парсер данных ORCID

Извлекает из публичного профиля ORCID массив работ с полями:
- год издания
- название работы
- DOI
- EID

#### Файлы
- `parse_orcid.ipynb` – скрипт на Python.
- `parsed_works.json` – результат в формате JSON.
- `parsed_works.csv` – результат в формате CSV (для Excel).

#### Запуск
1. Установить зависимости: `pip install requests pandas tqdm`
2. Запустить скрипт: `parse_orcid.ipynb`

Скрипт загружает актуальные данные напрямую с ORCID.
