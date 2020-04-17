# Frontend Testwork

## Задание
Приложение мероприятий (events):
- Home page - домашняя страница с events
- Add Events page - страница для добавления event

## Прототип
Дизайн и цвет на свой вкус, структура из Figma https://www.figma.com/file/L6FANUGVjmQ8wX0Yjj5dpv/Test-work?node-id=0%3A1

## Требования
- [**Angular Style Guide**](https://angular.io/guide/styleguide)
- Данные сущностей хранятся в NgRx Store (events) в отдельном модуле (Feature module)
- Каждый компонент создан изолированно от других (добавить в Storybook), кнопочки, инпуты, страницы и т.д. и т.п.
- События между компонентами передаются асинхронно
- Для формы - Reactive Forms
- Unit tests, ng test --codeCoverage > ~75-90
- Cypress - опционально(приветствуется)
- Стили, используем SCSS
- На карте используем Google API - маркеры через Google Markers добавляем контент (можно пропустить)
- Анимации - опционально (приветствуется)
- Компонент Input делаем через интерфейс ControlValueAccessor
- Получаем events через InMemoryWebApi - пример в документации tour of heroes (angular.io),
для Get метода - отдельный EventsService,
для связки с NgRx Store используем NgRx Effects

## Finish
Добавить приложение на CI/CD сервис - по выбору, главное чтобы было опубликовано демо
