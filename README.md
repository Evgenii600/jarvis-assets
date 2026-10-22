# jarvis-assets

Файлы для Джарвиса, которые слишком велики для основного сайта:

- `vosk-model-small-ru.tar.gz` — русская модель Vosk (~45 МБ): слово «Джарвис» распознаётся прямо на устройстве, без интернета;
- `vosk.js` — библиотека vosk-browser 0.0.8.

Оба файла скачивает автоматическая задача `.github/workflows/vosk.yml` (вкладка Actions → «Модель Vosk для Джарвиса» → Run workflow).
Джарвис ищет их на GitHub Pages (`evgenii600.github.io/jarvis-assets/`), а если Pages не включены — напрямую из репозитория.
