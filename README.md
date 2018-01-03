-------------------------------
io.adafruit example to use PWM
-------------------------------

This code(mqtt_slider_pwm.ino) explores the slider utility provided on io.adafruit.com.

This example assumes you are familiar with io.adafruit id and AIO key usage, feeds and dashboard creation.

1. Create a feed on io.adafruit.com, name it whatever you want.
2. Create a dashboard, give it some name and in the next dialog box link it with the feed you created in the first step.
3. When the dashboard is created, add a slider using the "+" option, and again link it with the feed you created in the first step. You may leave the options to default or change it according to your convenience and save the changes by clicking on "done editing".
4. Use the code code mentioned above. Add ssid name, password adafruit user id, token in required spaces.
5. In the subscription field enter the feed url accordingly, for ex.
"Adafruit_MQTT_Subscribe slider = Adafruit_MQTT_Subscribe(&mqtt, MQTT_NAME "/feeds/slider");"

