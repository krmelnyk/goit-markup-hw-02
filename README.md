# WebStudio

Навчальний односторінковий сайт, створений у межах домашнього завдання GoIT з
HTML і CSS.

## Реалізовані секції

- Header із навігацією та контактами
- Hero
- Our Features
- Our Team
- Our Portfolio
- Footer

## Технології

- HTML5
- CSS3
- Modern Normalize
- Google Fonts: Roboto та Raleway

## Структура проєкту

```text
.
├── css/
│   ├── common.css
│   ├── features.css
│   ├── footer.css
│   ├── header.css
│   ├── hero.css
│   ├── main.css
│   ├── portfolio.css
│   └── team.css
├── images/
│   ├── portfolio-1.jpg
│   ├── ...
│   └── team-4.jpg
├── index.html
└── README.md
```

У `index.html` підключений лише файл `css/main.css`. Він містить імпорти
стилів окремих блоків сторінки.

## Запуск

Відкрийте файл `index.html` у браузері. Встановлення залежностей і збірка
проєкту не потрібні.

## Перевірка

- HTML перевірено через [W3C Nu Validator](https://validator.w3.org/nu/).
- HTML і CSS відформатовано за допомогою Prettier.
- Усі зображення зберігаються локально у форматі JPG.
