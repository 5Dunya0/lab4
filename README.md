## Описание проекта
Проект строит CI/CD-пайплайн для простого ***Spring Boot*** приложения. Пайплайн состоит из трех джобов:
1. Проверка сборки и прохождения тестов с заданным порогом покрытия тестами (ниже которого джоба упадет).
2. Анализ исходного кода средствами SonarQube.
3. Деплой приложения в виде jar-файла со скомпилированным кодом (внутри workflow).


Соответственно запущенные джобы отображаются во вкладке ***Actions*** и запускаются при пуше или PR в ветку *main*. 