# modbus-tcp


Testing <https://github.com/espressif/esp-idf/tree/master/examples/protocols/modbus/tcp>

on 2 Devices: 

<https://shop.m5stack.com/products/m5stack-cores3-se-iot-controller-w-o-battery-bottom>

with 

<https://shop.m5stack.com/products/lan-module-with-w5500-v12>




Important: Power the Base, e.g. with 24V. 
the M5 Core does not power ist, unless you configure special things. 
this is not in this Sample. 


DHCP: 
the Sample is using DHCP. 
so you need some Router or other DHCP Server. 
Pay Attention: when using a Fritz Box, "espressif" for both Host-Names is bad. 
the 2 devices are not shown different in the Fritz Box. 

Pay also big attention, to not have duplicated MAC address. 

see

<https://github.com/espressif/esp-idf/issues/14364>

in this Example 
 * the Master is set to `02:00:00:AB:CD:EF`
 * the Sclave is set to `02:00:00:12:34:56`



![5325828300116974424](https://github.com/user-attachments/assets/dfba679b-0352-4cb2-b3ab-8cd1e5cafd95)



Power the Base: 


![5325828300116974520](https://github.com/user-attachments/assets/39e7f4da-211f-462c-909d-c35503e3d04e)
