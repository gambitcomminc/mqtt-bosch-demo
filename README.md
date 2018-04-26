# mqtt-bosch-demo

This simple subscriber client displays the number of Bosch sensors it detects publishing to a broker. It goes by the serial number published in the telemetry by the sensor simulation detailed in the
Bosch XDK post at https://xdk.bosch-connectivity.com/community/-/message_boards/message/93503

This is a sample display for all the topics on the public IOT.ECLIPSE.ORG broker: 

http://mirror2.gambitcommunications.com/update/doc/mqtt-bosch-demo1.png



To run this tool, you need Python installed on your system. It also depends on the Eclipse Paho MQTT client API, as well as other Python packages (GTK, JSON, etc).

mqtt-bosch-demo.py --host iot.eclipse.org --thresh 70000

generated the above display.

If you use File->New it zeros out the collected topics, and will display the received messages from now on. 

To see it in action see this Youtube video

https://www.youtube.com/watch?v=cttbEh16MOI&hd=1&t=97
