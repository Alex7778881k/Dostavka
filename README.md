# Маршрут развозки (Android, Kotlin)

1. Откройте папку в Android Studio (Hedgehog или новее), дождитесь синхронизации Gradle.
2. Запустите на телефоне (Run). Нужен интернет.
3. В приложении вставьте ключ API 2ГИС (platform.2gis.ru), укажите город по умолчанию.
4. При первом распознавании скачается языковой пакет OCR (около 4 МБ).

Модули: Ocr.kt, AddressParser.kt, DgisGeocoder.kt, Navigator.kt (+RouteOptimizer), MainActivity.kt (камера и экран).

## Сборка без Android Studio
Загрузите содержимое папки в репозиторий GitHub. Вкладка Actions -> Build APK -> готовый файл app-debug.apk в Artifacts.
