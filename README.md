# Сайт куратора образовательной платформы

Статический лендинг: `index.html`, стили `styles.css`, картинки тарифов в папке `images/`.

## Картинки тарифов

Положите в `images/` файлы с теми же именами, что были раньше в корне проекта:

`1.jpg`, `2.jpg`, `3.jpg`, `4.jpg`, `6.jpg`, `7.jpg`, `8.jpg`, `99.jpg`.

## Первый экран и иллюстрации секций

- `images/hero-lifestyle.png` — главное фото в hero (можно заменить своим в том же стиле).
- `section-thoughts.jpg`, `section-platform.jpg`, `section-community.jpg`, `section-time.jpg` — атмосферные фото для отдельных блоков (источник: [Unsplash](https://unsplash.com)); при желании замените на свои снимки с теми же именами файлов.

## Подключение к GitHub

1. Создайте пустой репозиторий на [GitHub](https://github.com/new) (без README, если уже есть файлы локально).

2. В папке проекта выполните:

```bash
git init
git add .
git commit -m "Первый коммит: лендинг"
git branch -M main
git remote add origin https://github.com/ВАШ_ЛОГИН/ВАШ_РЕПОЗИТОРИЙ.git
git push -u origin main
```

3. **GitHub Pages** (бесплатный хостинг): в репозитории откройте **Settings → Pages**, в разделе **Build and deployment** выберите источник **Deploy from a branch**, ветка **main**, папка **/ (root)**. Через минуту сайт будет по адресу вида `https://ВАШ_ЛОГИН.github.io/ИМЯ_РЕПО/`.

## Локальный просмотр

Откройте `index.html` в браузере или запустите простой сервер, например:

```bash
python3 -m http.server 8080
```

и зайдите на `http://localhost:8080`.
