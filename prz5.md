Создвл две ВМ(адля агента и сервера с дашбордом)
![image](https://github.com/user-attachments/assets/e5b36af3-02df-4ffe-ad0a-e1b291033698)

Настроил между ними сетевую связанность
![image](https://github.com/user-attachments/assets/5f68476e-edc7-4cd8-bcfe-d5cde8a13b51)

Устанавливаю сервер и дашборд
![image](https://github.com/user-attachments/assets/0e49eef1-dbe5-4b13-9b68-e3c56f6b1b64)

User: admin
Password: 2Bl6su1y*W+f6UTt55zQeIF8VE.g4boh
Осталось установить агента на другой вм
![image](https://github.com/user-attachments/assets/21c939bf-1700-4e88-8943-a4467a7e22cb)


Агент установлен,работает(статус активный) и наш сервер его видит
![image](https://github.com/user-attachments/assets/fa29a79c-277a-4074-8642-cb7e6526a2da)
![image](https://github.com/user-attachments/assets/fa5f096d-7464-4ed2-aeb6-c0ecdaa3fd10)

Устанавливаю Suricata
![image](https://github.com/user-attachments/assets/a623038c-187e-4465-862b-a2202ea0c8ca)

Добавляю путь событий из сурикаты чтобы агент и туда лез за событиями
![image](https://github.com/user-attachments/assets/144596e2-ee59-40c3-8c48-792a4bed55a9)

События с сурикатой 
![image](https://github.com/user-attachments/assets/0ace9651-31dd-4fb7-8dbc-10f13e52587e)

Поднял апаче на который буду имитировать активность чтобы проверить работу сурикаты
![image](https://github.com/user-attachments/assets/047efbc0-fc1c-4c27-8646-bb2e0bfd23dc)

Указываю сурикате нужный интерфейс
![image](https://github.com/user-attachments/assets/5763879c-954a-4715-86ce-10763973080a)

Через кали проведу проверку 
![image](https://github.com/user-attachments/assets/56f3c3c8-b512-4667-88ca-9b6c0adc70f9)

Аллерт пришёл
![image](https://github.com/user-attachments/assets/f11c0a19-7dd7-4b5e-8613-b0a8a38df356)


Скачал yara 
![image](https://github.com/user-attachments/assets/daebd024-9bdc-4ac2-ab03-c91368e19905)

Создал правило с измением рабочего стола (удаление создание файла)
![image](https://github.com/user-attachments/assets/5c137552-bc13-48bf-9c2a-fca9b2455c58)

Указал логи yara в конфиге агента
![image](https://github.com/user-attachments/assets/52e2f725-5c86-4f1b-9039-c28bf1aa122f)

Проверяю правило
![image](https://github.com/user-attachments/assets/8ec567e6-6275-4a72-87ee-58832bf9496e)
![image](https://github.com/user-attachments/assets/8847c1a8-b623-45ea-8b35-5e5e6aa3f856)


