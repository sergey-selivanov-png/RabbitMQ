# Домашнее задание к занятию  «Очереди RabbitMQ» - Selivanov Sergey

### Задание 1. Установка RabbitMQ

![rabbitmq](https://github.com/sergey-selivanov-png/RabbitMQ/blob/main/image/g1.png)

---

### Задание 2. Отправка и получение сообщений

![rabbitmq](https://github.com/sergey-selivanov-png/RabbitMQ/blob/main/image/g2.png)

![rabbitmq](https://github.com/sergey-selivanov-png/RabbitMQ/blob/main/image/g3.png)

---

### Задание 3. Подготовка HA кластера

![rabbitmq](https://github.com/sergey-selivanov-png/RabbitMQ/blob/main/image/g4.png)

![rabbitmq](https://github.com/sergey-selivanov-png/RabbitMQ/blob/main/image/g5.png)

Также вывод команды с двух нод:

```shell script
$ rabbitmqctl cluster_status
```

![rabbitmq](https://github.com/sergey-selivanov-png/RabbitMQ/blob/main/image/g6.png)

![rabbitmq](https://github.com/sergey-selivanov-png/RabbitMQ/blob/main/image/g6-1.png)

![rabbitmq](https://github.com/sergey-selivanov-png/RabbitMQ/blob/main/image/g6-2.png)

![rabbitmq](https://github.com/sergey-selivanov-png/RabbitMQ/blob/main/image/g6-3.png)

![rabbitmq](https://github.com/sergey-selivanov-png/RabbitMQ/blob/main/image/g7.png)

![rabbitmq](https://github.com/sergey-selivanov-png/RabbitMQ/blob/main/image/g7-1.png)

![rabbitmq](https://github.com/sergey-selivanov-png/RabbitMQ/blob/main/image/g7-2.png)

![rabbitmq](https://github.com/sergey-selivanov-png/RabbitMQ/blob/main/image/g7-3.png)


Cкрипт producer.py на каждой из нод:

```shell script
$ rabbitmqadmin get queue='hello'
```

![rabbitmq](https://github.com/sergey-selivanov-png/RabbitMQ/blob/main/image/g8.png)

![rabbitmq](https://github.com/sergey-selivanov-png/RabbitMQ/blob/main/image/g9.png)

Cкрипт consumer.py

![rabbitmq](https://github.com/sergey-selivanov-png/RabbitMQ/blob/main/image/g10.png)


