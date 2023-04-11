# Ревью кода

## Васильев Павел

### Основные предложения

1. **Класс Food**
   - Объединить методы `draw` и `erase` в один, добавив аргумент для цвета кисточки.
2. **Класс Game**
   - Вынести переменную `waitingTime` в поле класса.
3. **Класс Snake**
   - Объединить методы `move` и `increase`, так как присутствует дублирование кода. Либо можно взять из обоих методов часть кода, которая повторяется, и выделить её в отдельный метод.
4. **Класс TranslationCoordinates**
   - Улучшить читабельность методов, возвращающих координаты.

### Заключение

В целом, проект хорошо разбит на модули, в подавляющем большинстве абсолютно понятно, что делает код, читабельный, классный! Надеюсь, что это ревью будет полезным для вас!