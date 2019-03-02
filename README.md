# Fefu Bureau ("Бюро ДВФУ")
Бюро ДВФУ - это сервис который даёт каждому легкий доступ к информации о сотрудниках и преподавателях ДВФУ.
# Цели нашего проекта:
  * Основной целью нашего проекта является создание автообновляемой и самоподдерживаемой системы внутренних контактов ДВФУ и полного справочника сотрудников с информацией о том где их можно найти и как с ними можно связаться.
  * Мы хотим дать возможность легко находить любого сотрудника ДВФУ, упростить поиски преподавателей с мобильных устройств. 
    Это облегчит жизнь как первокурсникам, так и преподавателям со студентами, которые учатся в ДВФУ не первый год.
  * Мы собираемся дать каждому пользователю нашего приложения возможность добавлять и изменять сведения о людях. Таким образом актуальная информация всё время будет добавляться и обновляться без участия разработчиков и администраторов.
## Структура нашего сервиса:
  1. [**Мобильное приложение**](https://github.com/demidko/FefuBureauAndroid):
      - Содержит сведения об имени, должности, почты, номера, местоположения, интересующего вас человека
      - Умный поиск по каждому из этих параметров.
      - Возможность предлагать и изменять сведения о людях.
      - Работа на мобильных Android устройствах.
      - Может работать и без мобильного интернета
      - Написано на Java
  2. [**Веб-приложение**](https://github.com/demidko/ContactsViewer):
      - Повторяет все возможности мобильного приложения
      - Работает онлайн
      - Не требует установки
      - Адаптивный интерфейс для любого устройства
      - Написано на TypeScript, JavaScript
  3. **Программа** для администрирования сервиса "Бюро ДВФУ":
      - Управляет общедоступными сведениями
      - Возможность принимать и отклонять сведения от клиентских приложений
      - Поддержка Windows 10
      - Написана на C#, XAML, C++
  4. [**Парсер**](https://github.com/demidko/FefuParser) сайта ДВФУ:
      - Перебирает все доступные страницы сайта
      - Находит контакты оформленные в виде текста или html
      - Конвертирует найденные контакты в [ContactScript](https://github.com/demidko/ContactScript)-файл 
      - Поддержка школ ШЕН, ИШ, и прочих.
      - Написан на Python
### Текущие задачи проекта:
  1. Выявить как можно больше контактов с помощью парсера.
  2. Сделать управляющее десктопное приложение (C#, XAML) с возможностью принимать и не принимать предложенния с мобильных устройств.
  3. Добавить поддержку нашего DSL в управляющее приложение.
  4. Необходимо реализовать клиентское приложение для мобильных с помощью Android Studio, используя язык программирования Java.
  5. Работа с дизайном мобильного приложения. Расположение иконок/кнопок/текста.
  6. Добавить поддержку нашего DSL в клиентское приложение.
  7. Возможность предлагать новые контакты, изменения контактов, удаление контактов из мобильного приложения.
  8. Механизм обновления списка контактов по сети.
  9. Разместить мобильное приложение в Play Market (25$)
### Уже решенные задачи:
  1. Разработать своей DSL для хранения контактов.
  2. Скачать первоначальный датасет (все страницы сайта двфу без изображений, без css и js скриптов), 8гб
  3. Написать парсер (Python) находящий контакты.
#### Участники проекта:
  * Стас Ивановский - Программист
  * Даниил Демидко  - Программист
  * Андрей Сергеев  - Разработчик
  * Елизавета Лось  - Разработчик
  * Антон Аланаев   - Разработчик
  
