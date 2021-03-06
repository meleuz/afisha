## Задача №1 - "Менеджер Афиши"

### Легенда

На основе проекта с лекции необходимо реализовать менеджер Афиши.

Какие методы должны быть у менеджера?
1. Добавить фильм в ленту.
1. Выдать последние 10 добавленных фильмов* (фильмы выдаются в обратном порядке, т.е. первым в массиве результатов будет тот, который был добавлен последним).

Примечание*: если фильмов меньше 10, то выдаёте столько, сколько есть.

Сделайте так, чтобы по умолчанию выводилось последние 10 добавленных фильмов, но при создании менеджера можно было указать другое число, чтобы, например, выдавать 5 (а не 10).

Напишите необходимые, с вашей точки зрения, автотесты на различные состояния менеджера (можно их делать не в одном файле).

Требования к проекту:
1. Подключите плагин Surefire так, чтобы сборка падала в случае отсутствия тестов.
1. Подключите плагин JaCoCo в режиме генерации отчётов (обрушать сборку по покрытию не нужно).
1. Реализуйте нужные классы и методы.
1. Напишите автотесты на методы, содержащие логику, добившись 100% покрытия по branch'ам.
1. Подключите CI на базе Github Actions и выложите всё на Github.

Как делать:
1. Берёте код с лекции
1. Заливаете в свой репозиторий
1. Делаете новую ветку
1. В новой ветке делаете все изменения (Surefire, JaCoCo, методы, автотесты, CI)
1. Делаете Pull Request из этой ветки к своему же репозиторию

Итого: у вас должен быть репозиторий на GitHub, в котором расположен ваш Java-код и Pull Request.