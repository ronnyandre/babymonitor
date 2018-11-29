# Open Source Baby Monitor
Let's make the best and cheapest possible open source baby monitor.

## Objective
This year I got my first child. He is now seven months, and is currently sleeping in his own room. Every night when we put him to bed, we place our baby monitor so we can hear if he wakes up during the night. The monitor also reads the temperature, and will warn us when the temperature is too high or low, or even when battery runs low.

However, I want to know my baby's activity during the night. Is he moving much? What times is he awake without making a sound? How is the humidity in the room? I also want to connect a light and heat source to the monitor as well. If temperature too high, turn down heat. If baby is asleep, turn off light.

In January 2019 I will start my paternity leave which could be a good time to start this project.

## Features
- Detect audio
- Detect movement by vibrations of bed
- Temperature and humidity readings
- Add LED strip and control lights based on time or events
- Turn on/off external heat source with Wi-Fi based power plug, like Sonoff
- Push events using MQTT for integration with home automation systems

## Hardware
- Controller: Wemos D1 Mini
- Audio detection: GY-MAX4466
- Vibration detection: SW-420
- Temperature and humidity reading: DHT22
- Motion sensor: HC-SR501
