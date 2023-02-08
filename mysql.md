
-- create Задача №2: создать БД, состоящую из одной таблицы
--(информация об одногруппниках) с четырьмя полями (добавить поле «Адрес»):
--id, name, age, address.

CREATE TABLE groupmates (
  empId INTEGER PRIMARY KEY,
  name TEXT NOT NULL,
  age TEXT NOT NULL,
  address TEXT NOT NULL
);

-- insert
INSERT INTO groupmates VALUES (0001, 'Clark', '25', 'Asia');
INSERT INTO groupmates VALUES (0002, 'Dave', '35', 'USA');
INSERT INTO groupmates VALUES (0003, 'Ava', '70', 'Russia');

-- fetch 
SELECT * FROM groupmates WHERE age = '35';
