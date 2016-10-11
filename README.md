== Repo to demonstrate queues not being created in RabbitMQ using the rabbitmq plugin

This video (https://youtu.be/pVDRA38QQss) demonstrates the queues not being created:

1. start a local instance of rabbitmq. On mac it can be rabbitmq-server. Install rabbitmq with brew install rabbitmq
2. Clone this app
3. Go to http://localhost:15672  guest/guest
4. Notice no queues
5. grails run-app
6. Notice still no queues -- Expected, the queues should have been created. 

