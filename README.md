# Autonomous-solar-powered-wireless-sensor-node
I am trying to make solar powered thermometer (or another type) sensor with wireless capabilities

For this moment I don't have much to say. It will be use NRF24L01+ RF module to transmit data and receive commands. Node itself will be based on STM32F or STM32L with M0 core. Solar cell or solar panel is a source of energy for operating. MPPT system is also can be implemented using ST SPV1050 high efficient energy harvester. I prefer to use supercaps as energy storage. 

This project would be a long story...

Update 1:
Now I have energy harvester schematic configured in boost mode. The main purpose - energy harvester testing. Stil I don't sure is SPV1050 right choise. So need to create test board and figure it out. Only problem - very fine pitch (0.4mm) so I need to use 0.15\0.15mm traces PBC (can't be done DIY). And shipping from china would take a lot of time. 
Fast shipping costs 3 times more than boards itself ;(

In schematic there are possible to use one of four different inductors, four 10uF ceramic 0805 or one 47uF polarised cap, one of two different litium rechargable batteries or up to six 5.5V 0.22F supercaps. Some kind of flexibility.

Next step: measure max power point to evaluate resistor values for harvester. Not complex but require time to measure VACs.
