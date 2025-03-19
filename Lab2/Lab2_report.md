University: [ITMO University](https://itmo.ru/ru/)

Faculty: [FICT](https://fict.itmo.ru)

Course: [IP Telephony](https://itmo-ict-faculty.github.io/ip-telephony)

Year: 2024/2025

Group: K34212

Author: Lebedeva Tatiana Alexandrovna

Lab: Lab2

Date of create: 14.03.2025

Date of finished: 20.03.2025

# Лабораторная работа №2 "Конфигурация voip в среде Сisco packet tracer"

## Описание
Для выполнения данной лабораторной работы собирается схема соединения. Необходимо проверить, правильно ли подключены все узлы устройств. Предварительно удалить все преды- дущие конфигурационные файлы на маршрутизаторах Cisco 2811, на коммутаторе Cisco catalyst 3560.

## Цель работы
Иизучить построение сети IP-телефонии с помощью маршрутизатора Cisco 2811, коммутатора Cisco catalyst 3560 и IP телефонов Cisco 7960.

## Ход работы
### Часть 1
1. В конфигурационном режиме измените название маршру- тизатора на CMERouter.
   
   ![image](https://github.com/user-attachments/assets/e87fecf9-3aad-49f0-92a9-a58a26ec59d3)    
   
   ![image](https://github.com/user-attachments/assets/e2ca0e11-ac31-4e50-ae58-692c117139b1)     
3. Отключите синтаксис ввода слов от DNS серверов.    
4. Задайте пароли для защиты маршрутизатора как в удаленном режиме, так и в режиме консоли.
   
   ![image](https://github.com/user-attachments/assets/0aae9dd7-4781-43a0-a119-21241eb99449)    
6. Настройте интерфейс fa0/0 на маршрутизаторе Cisco 2811 (CMERouter).
7. 
   ![image](https://github.com/user-attachments/assets/dccc0ef9-5c9a-4b6d-bef0-df44453aad34)     

8. Настроить DHCP сервера для передачи голоса и данных на маршрутизаторе Cisco 2811.
   
   ![image](https://github.com/user-attachments/assets/d6e1afe2-c185-4e9c-9a15-f309ddec04f0)     

10. Настроить услуги телефонии Cisco CallManager Express на маршрутизаторе 2811.
    
    ![image](https://github.com/user-attachments/assets/ff62447f-ab87-4625-920e-be0025d9fc12)     
12. Создать VLAN порты на коммутаторе Cisco Catalyst 3560 для взаимодействия коммутатора с маршрутизатором и подключить IP телефоны.
    
    ![image](https://github.com/user-attachments/assets/f9d64635-d11b-4236-af66-84e29387d6d4)    
    
    ![image](https://github.com/user-attachments/assets/ae3a5232-d393-4050-8135-c2bcb16de541)     
14. Настроить IP-телефоны и соединить с коммутатором Cisco Catalyst 3560.
    ![image](https://github.com/user-attachments/assets/5fec7777-a5c2-4494-a36a-592982d3dee1)     

16. Проверить звонки между телефонами и проверить остальные сервисы (перевод звонков, конференц-связь, перехват звонка).
    
    ![image](https://github.com/user-attachments/assets/04b07c89-ea17-4e33-99f9-74ef9d463039)
    
    ![image](https://github.com/user-attachments/assets/c892976d-52ab-4652-abde-8787c7b818bd)
    
    ![image](https://github.com/user-attachments/assets/778c64b6-ec93-40f2-bc5d-be53eebffdee)
    
    ![image](https://github.com/user-attachments/assets/b9345a81-27a6-4644-be19-b550aa6ea6b9)    

### Часть 2    
1. Создать VLAN порты на коммутаторе для взаимо- действия коммутатора с маршрутизатором и подключить IP телефоны.
    
   ![image](https://github.com/user-attachments/assets/ef4f6541-f1f5-4c27-90bb-614da90a15fc)
   
   ![image](https://github.com/user-attachments/assets/3c3b3511-795a-4f1c-a700-6ec9ee50d1da)    


3. Задайте маршрут по умолчанию командой ip default-gateway.
   
   ![image](https://github.com/user-attachments/assets/00116613-e1a6-4ea1-a824-b9273c683801)    

5. Настройте порт как канал типа trunk.
   
   ![image](https://github.com/user-attachments/assets/277136d9-520a-41d1-aa80-434dda367d51)     

7. Настроить DHCP сервера для передачи голоса и данных на маршрутизаторе Cisco 2811.
   
   ![image](https://github.com/user-attachments/assets/2fada768-ab0f-461d-b807-ef1aec6efde0)      

9. Настроить услуги телефонии Cisco CallManager Express на маршрутизаторе.
    
    ![image](https://github.com/user-attachments/assets/5d544829-e262-4e3a-af24-08b12c5becbe)    
    
11. Настроить IP-телефоны и соединить с коммутатором.
    
    ![image](https://github.com/user-attachments/assets/a3f6f006-365a-4e43-825f-b3d3377ee503)
    
    ![image](https://github.com/user-attachments/assets/56c0ae0e-6930-4828-a17d-75555e549797)    
    
    ![image](https://github.com/user-attachments/assets/391f501e-ff8a-4494-a75f-893204f3032d)     
    
13. Подключить конечные узлы устройств.
    ![image](https://github.com/user-attachments/assets/ed04bc1d-e7ea-4b41-af30-51da64923d84)    
    
    ![image](https://github.com/user-attachments/assets/68fc35ec-540a-4786-920f-7f9a599bdb36)    
    
    ![image](https://github.com/user-attachments/assets/bdcd83d2-2782-4fb9-b4b4-5368706017f7)    
    
15. Проверить звонки между телефонами и проверить остальные сервисы (перевод звонков, конференц-связь, перехват звонка).    
    ![image](https://github.com/user-attachments/assets/61b7702b-2cf9-4f89-8759-dee1b1887655)    
    
    ![image](https://github.com/user-attachments/assets/60cb5c2e-6fe0-47ea-a40a-d3e366a86790)    
    
    ![image](https://github.com/user-attachments/assets/558b0452-932c-40e9-80de-866732cd143e)    
    
    ![image](https://github.com/user-attachments/assets/6f5905bb-ac5b-4c6c-ab67-d0d6fea536a0)    
    
    ![image](https://github.com/user-attachments/assets/66d12449-3e2e-47ed-9b6e-395821fc3bb7)    
    
## Выводы
### В ходе выполнения лабораторной работы были выполнены следующие шаги:
Изучена базовая конфигурация маршрутизатора (Cisco 2811) и коммутатора (Cisco Catalyst 3560) для создания сети VoIP.
Настроены VLAN (Data/Voice), DHCP-серверы для каждой VLAN, CallManager Express на маршрутизаторе.
Успешно протестированы звонки между IP-телефонами Cisco 7960, а также дополнительные сервисы (при необходимости).
Получены навыки по сегментации сети (VLAN), транковым соединениям и подключению устройств IP-телефонии.

