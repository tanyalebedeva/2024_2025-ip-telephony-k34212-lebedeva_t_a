University: [ITMO University](https://itmo.ru/ru/)

Faculty: [FICT](https://fict.itmo.ru)

Course: [IP Telephony](https://itmo-ict-faculty.github.io/ip-telephony)

Year: 2024/2025

Group: K34212

Author: Lebedeva Tatiana Alexandrovna

Lab: Lab1

Date of create: 01.03.2025

Date of finished: 20.03.2025

# Лабораторная работа №1 "Базовая настройка ip-телефонов в среде Сisco packet tracer"

## Описание
Для выполнения данной лабораторной работы собирается схема соединения. Необходимо проверить, правильно ли подключены и настроены все узлы устройств.

## Цель работы
Изучить рабочую среду Cisco Packet Tracer, ознакомить- ся с интерфейсами основных устройств, типами кабелей, научиться собирать топологию. Изучить построение сети IP-телефонии с помощью маршрутизатора, коммутатора и IP телефонов Cisco 7960 в среде Packet tracer.

## Ход работы
### Часть 1
1. Изучить теоретическую и практическую части лабораторной работы.    
2. Собрать схему соединения.
   ![image](https://github.com/user-attachments/assets/07e30528-a017-4759-bc86-d22f63a7ffe3)    
4. Научиться настраивать коммутаторы и компьютеры для полноценной работы сети.
   ![image](https://github.com/user-attachments/assets/7be42440-115e-49cf-8500-51ceef76b0b0)    
6. Научиться применять основной список команд для конфигурирования устройств сети.
7. После выполнения необходимых настроек необходимо убедиться в том, что любой компьютер одной сети посредством пинга передает пакеты любому компьютеру другой сети.
   ![image](https://github.com/user-attachments/assets/e8343883-f78f-4ed8-81d5-6ec02adde36b)
   ![image](https://github.com/user-attachments/assets/4c417161-52de-4449-9b9e-2ef2fb6356cd)    

### Часть 2    
1. Собрать схему соединения, указанную на рисунке
   ![image](https://github.com/user-attachments/assets/5c9c2541-53e0-4fef-9229-d61cea2cb5a1)    
3. Изменить имя маршрутизатора на CMERouter.
5. Настроить интерфейс fa0/0 на маршрутизаторе Cisco 2811 (CMERouter).
   ![image](https://github.com/user-attachments/assets/bbf871e0-9321-4f6c-b1d9-da0a8642f7a9)

7. Настроить DHCP сервера для передачи голоса и данных на маршрутизаторе - Cisco 2811.
   ![image](https://github.com/user-attachments/assets/2060600f-aee3-4d1e-b259-5ed5ac16351b)    

9. Настроить услуги телефонии Cisco CallManager Express на маршрутизаторе 2811.
   ![image](https://github.com/user-attachments/assets/8635cba1-86ad-4f87-a083-097851f87356)
   ![image](https://github.com/user-attachments/assets/37b14cad-8b3a-418f-964b-2bb7afe39d6b)      

11. Настроить маршрутизацию сети.     
12. Создать VLAN порты на коммутаторе для взаимодействия коммутатора с маршрутизатором и подключить IP телефоны.
    ![image](https://github.com/user-attachments/assets/628f4c5d-83e2-4b1b-aa3b-65ffd2f47955)     
    ![image](https://github.com/user-attachments/assets/633e2eef-091f-4a78-96da-7bf01dc7a50b)     

14. Настроить IP-телефоны, присвоить им номера и соединить с коммутатором.
    ![image](https://github.com/user-attachments/assets/2aab6f64-ffce-44a0-a61b-9454fdb4ba41)     
    ![image](https://github.com/user-attachments/assets/1b661eb0-55a5-4bb1-9eeb-9826bae8b33c)    

16. Проверить звонки между телефонами и проверить остальные сервисы (перевод звонков, конференц-связь, перехват звонка).
    ![image](https://github.com/user-attachments/assets/935cdbfc-2fc7-4dfd-bb88-dccb8afbc7f4)
    ![image](https://github.com/user-attachments/assets/39099f83-f58d-416f-ae5c-082b2f7f87cc)
    ![image](https://github.com/user-attachments/assets/411978ae-ab52-4c13-b02c-66c9cae8b49b)    

### Тестирование результатов
![image](https://github.com/user-attachments/assets/7e13349b-e901-402c-83fd-b4119d926db0)    
![image](https://github.com/user-attachments/assets/0501a6bd-9aa7-4cda-b063-fecc7a235f39)    
![image](https://github.com/user-attachments/assets/adec2436-30f3-4885-9e11-3ef9a2f0a35e)    
![image](https://github.com/user-attachments/assets/8e853a66-0cfc-4ddf-8023-b93e4a273f41)     


## Выводы
### В ходе выполнения лабораторной работы были выполнены следующие шаги:
В ходе выполнения лабораторной работы изучен базовый функционал Cisco Packet Tracer, основные команды настройки маршрутизатора и коммутатора.
Реализована сеть с несколькими VLAN (Data и Voice), а также соответствующая конфигурация DHCP на маршрутизаторе для автоматической выдачи адресов как для ПК, так и для IP-телефонов.
Настроен сервис Cisco CallManager Express (CME), позволяющий регистрировать и обслуживать IP-телефоны (Cisco 7960).
Успешно выполнены звонки между IP-телефонами, что подтверждает корректность настройки сети IP-телефонии.
