# Markdown — это облегченный язык разметки, созданный в 2004 году Джоном Грубером и Аароном Шварцем. 
## Он позволяет оформлять простой текст с помощью интуитивно понятных символов (решеток, звездочек, дефисов), 
## который затем легко конвертируется в чистый HTML или PDF. 
## Файлы в этом формате сохраняются с расширением .md или .markdown

# Порядок написания

# Заголовок
## Подзаголовок
**текст** или __текст__
*текст* или _текст_
~~текст~~
- пункт или * пункт
1. пункт
2. второй пункт

Встроенная ссылка - [Название](https://example.com)

![Описание](https://example.com/img.png)

> Текст цитаты
 
(Разделительная черта)
---
(Разделительная черта)


| Слева | По центру | Справа |
| :--- | :---: | ---: |
| Текст | Еще текст | 1200 ₽ |

Чек-листы (Списки задач)
- [x] Изучить базовый синтаксис Markdown
- [ ] Написать README.md для проекта

```text
├── README.md
├── slovo.py
├── docs/
│   ├── installation.md
│   └── images/
│       └── screenshot.png
└── src/
└── main.py
```
## Файл находится в той же папке
Пожалуйста, ознакомьтесь с [первый код на Python](slovo.py).

## Ссылка на конкретный заголовок (якорь)
[Вклад](readme.md##Contributing)
index.html
Document


# Foobar

Foobar is a Python library for dealing with word pluralization.
Foobar — это библиотека на Python для работы с множественным числом слов.

## Installation  Установка

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install foobar
```

## Usage  Использование

```python
import foobar

# returns 'words'
foobar.pluralize('word')

# returns 'geese'
foobar.pluralize('goose')

# returns 'phenomenon'
foobar.singularize('phenomena')
```

## Contributing  Вклад

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
