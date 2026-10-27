# lanafreitag.ru

Сайт автора Ланы Фрейтаг. Код сайта живёт в основном хранилище
[erichthoxx-sketch/mine](https://github.com/erichthoxx-sketch/mine) — папка `site/`
(инструкция для нейросетей — `AGENTS.md` там же). Тексты, книги и картинки — в админке
https://lanafreitag.ru/admin/ (данные в Firebase), их правят без кода.

Здесь только публикация: `.github/workflows/publish.yml` берёт `site/` из mine и выкладывает
в ветку `gh-pages` (адрес — файл `CNAME`). После правок кода сайта в mine — запустить
этот workflow вручную (Actions → «Публикация lanafreitag.ru» → Run workflow); раз в 6 часов он запускается сам.
