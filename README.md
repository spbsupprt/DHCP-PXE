# DHCP,PXE


- Настроить загрузку по сети дистрибутива Ubuntu 24

- Установка должна проходить из HTTP-репозитория.

- Настроить автоматическую установку c помощью файла user-data

---

Дано: 

![image](https://github.com/user-attachments/assets/6310db71-b55d-4fff-a3be-00244a297beb)



Проверка, установки:


- Настроить загрузку по сети дистрибутива Ubuntu 24

- Установка должна проходить из HTTP-репозитория.

![image](https://github.com/user-attachments/assets/63cda5d9-d088-43fa-998b-376604cd5717)


![image](https://github.com/user-attachments/assets/afca18f4-f6de-487f-9988-f77344d80413)



В нашем случае плейбук сразу подготовлен для автоматической загрузки через user-data

```
#cloud-config
    realname: otus
    username: otus

```

Применяем плейбук https://github.com/spbsupprt/DHCP-PXE/blob/main/pxe.yml

![image](https://github.com/user-attachments/assets/8455ef96-d3dc-450a-9673-d5db635a653a)


Результат:

![image](https://github.com/user-attachments/assets/d321ab91-a912-4cfd-ba40-463045ea0c6f)
