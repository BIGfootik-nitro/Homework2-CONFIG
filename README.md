# О проекте

Консольное приложение, позволяющее визуализировать транзитивные зависимости коммитов с сообщениями, связанных с хешем
определенного файла.

# 1. Клонирование репозитория

Склонируйте репозиторий с исходным кодом и тестами:

```bash
git clone <URL репозитория>
cd <директория проекта>
```

# 2. Виртуальное окружение

```shell
python -m venv venv
venv\Scripts\activate
```

# 3. Установка зависимостей

```shell
pip install -r requirements.txt
```

# 4. Запуск программы

```shell
py main.py dot.exe <path_to_your_repo> <hash_of_your_file>
```

```
python main.py dot.exe C:\Users\user\Desktop\confeg2test 895caaf3d5d15820068861f5f03dd6fe596dbc7d
```

**path_to_your_repo** - Путь к анализируемому локальному репозиторию

**hash_of_your_file** - Первые 4 или более символа хеша анализируемого файла в репозитории.

### Важно:

Для работы необходим установленный Graphviz.
