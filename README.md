# sun2000-modbus-nodered
Node-RED code to ream Modbus registers from a Huawei Inverter like SUN-2000 xyz

The idea is to do this in Node-RED instead of using some sort of other service to read these registers.
It is very easy to creaet and send MQTT messages from these reads, calculate stuff before sending it and so on.

I have used this manual as a reference:
"Solar Inverter Modbus Interface Definitions" rev 4, from Huawei.
Google it to find it, as there are alot of people distributing it. 
As you need to be logged in on the Huawei site to get access to it. 

So this is a start for your Node-RED automation project.
1. Import the code into Node-Red.
2. Configure the Modbus read node to use your MODBUS ip address. ( Google this if you need help configuring your inverter to use MODBUS over IP)
3. Begin to read.
   
