# Домашнее задание к занятию «Система сборки Maven, управление зависимостями, автотесты на JUnit5»

# Задание 2. Читаем логи (необязательная задача повышенной сложности)

Ваш коллега — очень любознательный товарищ. Узнав про то, что Maven может использовать плагины, он сразу начал искать, какие плагины есть.

И нашёл один, с его точки зрения, достаточно замечательный плагин, который ищет ошибки в коде.

Представляете? Сам ищет ошибки в коде!

Естественно, он не преминул этим воспользоваться, загуглил, как подключить этот плагин и даже смог его запустить на одном из наших проектов.

Но поскольку он не совсем разобрался, как работать с логами, он не совсем понимает, что и где не так и куда смотреть.

Поэтому он обратился к вам.

Ваша задача:
1. Взять проект, который прикреплён в архиве [`bonus-service.zip`](https://github.com/netology-code/javaqa2-homeworks/blob/main/files/bonus-service.zip?raw=true).
1. Открыть его как Maven проект в IDEA.
1. Запустить следующую команду Maven*: `mvn clean compile spotbugs:check`. Ваш коллега не может объяснить, что это значит, но говорит, что запускать нужно именно так.
1. Проанализировать логи, выяснить в чём ошибка. Воспользуйтесь гуглом по типу ошибки и чтением документации.
1. Исправить ошибку так, чтобы повторный вызов `mvn clean compile spotbugs:check` завершался успешно, менять `pom.xml` нельзя.

Как выкладывать проект на GitHub:
1. Заливаете исходную версию.
1. Создаёте issue* с описанием того, что не так, и прикладываете кусок лога, из которого это видно, плюс ссылку на проблемный участок кода.
1. Фиксите всё с сообщением коммита `fixed #1`, где 1 — это id issue.
1. Заливаете на GitHub, удостоверяетесь, что после пуша issue автоматически закроется.

Примечание*: как работать с issue, описано в третьей лекции курса по Git и в первом домашнем задании блока по Java.
