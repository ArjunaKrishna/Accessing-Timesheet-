# Timesheet access 

Communication Contract 

How to request data using RabbitMQ 

binding_socket.send("A message from CS361") 

How to receive data using RabbitMQ 

channel.basic_consume(queue="message", on_message_callback=callback, auto_ack=True) 

An example: 

A message from CS 361 
