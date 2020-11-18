## Интерфейс

![Требуемый интерфейс](https://i.imgur.com/8xA0Yfl.jpeg)

## Логика

Необходимо сделать приложение на React, работающее по следующей логике:

1. Наверху расположены 3 кнопки. По нажатию на каждую должен запускаться таймер с задержкой в секундах, равной номеру кнопки (начиная с 1).
2. Таймер следующей нажатой кнопки должен запускаться только после завершения предыдущего (при этом кнопки не должны блокироваться, должна образовываться очередь)
3. По завершению отсчета таймера, в лог добавляется запись в следующем формате: “${время вывода строки в лог}: ${номер кнопки} / ${время нажатия кнопки)
4. Записи в логе должны следовать в порядке нажатия кнопок.
5. Рядом с основными кнопками расположена кнопка "Сбросить". По нажатию кнопки "Сбросить" состояние приложения должно возвращаться к исходному.

## Требования

1. TypeScript
2. React (CRA)
3. Компоненты должны быть функциональными
4. Должна быть возможность переиспользования функциональных частей приложения
