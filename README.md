# Скрипт для работы с датчиком mpu6050

- На вход COM порта подается строка вида:

;;;Acel_x;Acel_y;Acel_z;Gyro_x;Gyro_y;Gyro_z;Temperature\n

Скрипт производит парсинг строки для выделения полезных данных
и дальнейшего их отображения

- Выводится таблица, в которой 7 строк для каждого значения параметра, статус работы

![image](https://github.com/VladislavSts/UImpu6050/assets/110287357/835b2bb3-74fb-4a64-bf6d-1f7609a3a1ed)
