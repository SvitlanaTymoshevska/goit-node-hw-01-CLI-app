# Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)

node index.js --action="list"
https://monosnap.com/file/to4RKPmqpygRcVvYWHUjlzQJ5XJDE2

# Отримуємо контакт по id

node index.js --action="get" --id=5
https://monosnap.com/file/GD0sqWNYyeGkB0GRQJlsZqkiSLnbtO

# Додаємо контакт

node index.js --action="add" --name="Mango" --email="mango@gmail.com" --phone="322-22-22"
https://monosnap.com/file/pQr90EUDRxpUztHEjMeBFJIL3sUVwX

# Видаляємо контакт

node index.js --action="remove" --id=3
https://monosnap.com/file/B3QqyjMAi3N1JtMJpvBKvtS6TjGFck
