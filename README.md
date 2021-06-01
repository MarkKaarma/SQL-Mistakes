**Внимание! В запросах есть ошибки - исправьте их и будет счатье!**

[1.Создайте новую таблицу  с таким запросом:]

CREATE TABLE test(
id int auto_insert PRIMARY KEY,
nimi varchar(50),
aasta int,
raha decimal(3,2)
);



[2. Добавьте запись в таблицу.]

INSERT INTO tect (nimi, aasta, raha)
VALUES (‘Test’, 15, ‘12.2’)



[3. Назначьте права новому пользователю с определенными правами (пользователя создаем любым способом, но без прав).]

Задание таково: дать ему права на просмотр, добавление и удаление в таблице test, но он не может удалять запросы.

CREATE GRANT SELECT, UPDATE, INSERT ON tect to логин@localhost;




