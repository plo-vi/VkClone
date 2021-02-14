## Почему в описании объектов в Vk оказались поля, которых не было в v1?

Версия 1 (v1) была создана с минимально необходимым набором объектов. 
В то время как после анализа [документации](https://vk.com/dev/objects/post) было принято решение дополнить программу следующими объектами:
* **createdBy** - отображает ID администратора, опубликовавшего запись в сообществе (большая часть записей публикуется именно в сообществах, поэтому данный объект необходим);
* **replyOwnerId** - отображает ID владельца записи, в ответ на которую была оставлена текущая;
* **replyPostId** - отображает ID записи, в ответ на которую была оставлена текущая;
* **friendsOnly** - позволяет побликовать запись с опцией «Только для друзей»;
* **Geo** (также содержит вложенные объекты) - отображает информацию о местоположении.