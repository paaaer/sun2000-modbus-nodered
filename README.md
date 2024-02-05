# sun2000-modbus-nodered
Node-RED code to ream Modbus registers from a Huawei Inverter like SUN-2000 xyz

The idea is to do this in Node-RED instead of using some sort of other service to read these registers.
It is very easy to creat and send MQTT messages from these reads, calculate stuff before sending it and so on.

I have used this manual as a reference:
"Solar Inverter Modbus Interface Definitions" rev 4, from Huawei.
Google it to find it, as there are alot of people distributing it. 
As you need to be logged in on the Huawei site to get access to it. 

So this is a start for your Node-RED automation project.
1. Import the code into Node-Red.
   - For each of the imported json files, there will be dependecies to other Node-RED nodes that you haven't downloaded.
   Note down what you need when importing it as Node-RED will tell you what is missing. I have also written down what you probably need below.
3. Configure the Modbus read node to use your MODBUS ip address(default set to 192.168.0.94) ( Google this if you need help configuring your inverter to use MODBUS over IP)
4. Begin to read.
   

Dependencies:

- https://flows.nodered.org/node/node-red-contrib-modbus
- https://flows.nodered.org/node/node-red-contrib-cron-plus
