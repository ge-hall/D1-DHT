PlatformIO project for Wemos DHT sensor.
Sensor is not working well and requires some resistor between 3.3v and D8. Human finger works well.
I need to investigate this further but for now I will move onto other sensors and setup a MQTT Library to publish and/or subscribe to topics.

End goal is to integrate with ge-hall/mqtt-service.
Much TODO there to work out an extensible interface between a Wemos D1 and mqtt-service.
Each require a common mqtt server to be running. I am using mosquitto locally.
