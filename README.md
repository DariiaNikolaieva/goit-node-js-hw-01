# Получаем и выводим весь список контактов в виде таблицы (console.table)

node index.js --action list
![](./screenshots/2021-09-22-20-26-47.png)

# Получаем контакт по id

node index.js --action get --id 5
![](./screenshots/2021-09-22-20-28-56.png)

# Добавялем контакт

node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22
![](./screenshots/2021-09-22-20-37-58.png)

# Удаляем контакт

node index.js --action remove --id=3
![](./screenshots/2021-09-22-20-39-36.png)
