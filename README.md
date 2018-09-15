# MARAGI RabbitMQ Container

Broker definitions and Docker launch script. 

# Instructions

1. Install Docker
2. Run rabbit.sh
3. Log into RabbitMQ instance and apply JSON definitions file
4. Start other [MARAGI services](https://github.com/topics/maragi)
5. Get more [images from Docker](https://hub.docker.com/u/daveshap/)

# Exchanges

Name | Type
--- | ---
sensor_audio | fanout
sensor_video | fanout
model_speech | fanout
model_face | fanout
model_object | fanout
model_ocr | fanout
