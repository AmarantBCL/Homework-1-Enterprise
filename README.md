# ДЗ 1. Cоздание каркаса Spring-приложения

**Цель задания:**

- Научиться создавать приложение с помощью Spring IoC.

**Результат:**

- Простое приложение, сконфигурированное XML-контекстом.

**Описание задания:**

В ресурсах хранятся вопросы и различные ответы к ним в виде CSV файла (5 вопросов). Программа должна спросить у пользователя фамилию и имя, спросить 5 вопросов из CSV-файла и вывести результат тестирования (можно использовать любые способы для отображения).
Вопросы могут быть с выбором из нескольких вариантов или со свободным ответом - на Ваше желание и усмотрение.
Все сервисы в программе должны решать строго определённую задачу. Контекст описывается XML-файлом. Все зависимости должны быть настроены в IoC контейнере. Имя ресурса с вопросами (CSV-файла) необходимо захардкодить в XML-файле с контекстом. CSV с вопросами читается именно как ресурс, а не как файл. Scanner и стандартные типы в контекст класть не нужно!

* Опционально: сервисы, по возможности, покрыть Unit-тестами. Вам подарок - тесты не обязательны.