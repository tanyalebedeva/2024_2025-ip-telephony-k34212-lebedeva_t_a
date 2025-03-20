University: [ITMO University](https://itmo.ru/ru/)

Faculty: [FICT](https://fict.itmo.ru)

Course: [IP Telephony](https://itmo-ict-faculty.github.io/ip-telephony)

Year: 2024/2025

Group: K34212

Author: Lebedeva Tatiana Alexandrovna

Lab: Lab3

Date of create: 19.03.2025

Date of finished: 20.03.2025

# Лабораторная работа №3 "Использование Asterisk в качестве SIP proxy"

## Описание
Для выполнения данной лабораторной работы необходимо выполнить настройку Asterisk.

## Цель работы
Изучить программный комплекс Asterisk. Настройка Asterisk для локальных звонков.

## Ход работы
1. Установить систему server.
2. Установить Asterisk.
   ![image](https://github.com/user-attachments/assets/e4044a0c-1c59-4c4b-be27-4f6b6ff4832e)
   ![image](https://github.com/user-attachments/assets/69749668-c731-4648-a39b-763ae790a749)  

3. Установить soft телефон на рабочую станцию.
   ![image](https://github.com/user-attachments/assets/eb19c5d5-b013-45d7-90f4-fdae666bf21e)   

5. Настроить SIP каналы.   
   ![image](https://github.com/user-attachments/assets/66700355-ba7b-43bf-8a7c-a95fca10987a)
   ![image](https://github.com/user-attachments/assets/c6280da4-5bbc-416b-823e-9e7176dd91a5)   

6. Подключиться к SIP каналам soft телефона. Настройки для двух "телефонов"
   Файл /etc/asterisk/sip.conf отредактирован следующим образом   
   ![image](https://github.com/user-attachments/assets/0fb0f2f9-9f2a-4bae-a582-fb89d0208f61)
   ![image](https://github.com/user-attachments/assets/d531806f-b45a-4d82-822f-a1fae2d6d090)
   ![image](https://github.com/user-attachments/assets/0748fd0c-99e1-4419-b54a-1cf75d4d76fc)
   Перезапуск Asterisk для применения изменений:
   ```
      sudo systemctl restart asterisk
      systemctl status asterisk
   ```   
   ![image](https://github.com/user-attachments/assets/378eea9f-e2eb-4668-baf2-5db5dabf8b60)   

8. Сделать тестовый звонок на номер 1000
   ![image](https://github.com/user-attachments/assets/79dad2e1-3c68-48fa-bf98-6e7c58c1eb28)
   ![image](https://github.com/user-attachments/assets/ec8d021a-81ef-42e5-98bb-75c6029fbd6a)   



## Выводы
В результате лабораторной работы была выполнена базовая настройка Asterisk в качестве SIP‑proxy. Были созданы SIP‑учётные записи для двух номеров (1000 и 1001) и настроен диалплан, позволяющий совершать локальные звонки. Клиент Twinkle был успешно настроен для регистрации в системе, и тестовый звонок между двумя SIP‑телефонами подтвердил корректную работу настроенного решения.
