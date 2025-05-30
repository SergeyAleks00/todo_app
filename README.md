# Todo App

Простое Flutter-приложение для управления задачами, созданное в рамках домашнего задания. Приложение позволяет добавлять, просматривать, редактировать и удалять задачи с использованием `ListView.builder`, `TextField` и `StatefulWidget`.

## Функциональность
- **Добавление задач**: Ввод задачи через текстовое поле с поддержкой русской кодировки и нажатие кнопки "Добавить" или клавиши Enter.
- **Просмотр**: Список задач отображается динамически с помощью `ListView.builder` в карточках (`Card`).
- **Редактирование**: Изменение задач через диалоговое окно с проверкой на пустой ввод.
- **Удаление**: Удаление задач с уведомлением через `SnackBar`.
- **Интерфейс**: Адаптивный дизайн с поддержкой тёмного и светлого режимов, локализацией для русского языка и информативными уведомлениями.

## Структура проекта
- `lib/main.dart`: Основной код приложения, содержащий логику интерфейса и CRUD-операции.
- `android/`, `ios/`: Платформо-зависимые конфигурации.
- `pubspec.yaml`: Зависимости проекта, включая `flutter_localizations` и `cupertino_icons`.
- `assets/`: Папка для ресурсов (не используется в текущей версии).

## Технические особенности
- Кроссплатформенность (Android, iOS).
- Поддержка русской локализации.
- Адаптивный дизайн с тёмным режимом.
- Обработка ошибок ввода через `SnackBar`.

