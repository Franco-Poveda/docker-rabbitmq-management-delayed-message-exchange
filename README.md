docker-rabbitmq-management-delayed-message-exchange
==================

**Dockerfile FROM rabbitmq:3.6.6-management + delayed-message-exchange plugin instalation**

##Usage
```
git clone https://github.com/Franco-Poveda/docker-rabbitmq-management-delayed-message-exchange.git
cd docker-rabbitmq-management-delayed-message-exchange
docker build -t docker-rabbitmq-management-delayed-message-exchange .
docker run -d --hostname rabbitMQ06 --name rabbit06 -p 5672:5672 -p 15672:15672 <GENERATED_IMAGE_NUMBER>
```