# Temperature-Sensor-
Implement a system that samples signal from the internal temperature sensor at 10 Hz sampling rate continuously. The averaged temperature value is calculated every 5 seconds



System Requirements 
 Use ADC0, SS0 to sample signals from the internal temperature sensor. 
 Use Timer0A to generate periodic interrupts every 100 ms and trigger ADC0, SS0. 
 The converted data in the ADC0 SS0 FIFO are transmitted to the RAM buffers using DMA, burst request, ping-pong mode. 
 Each RAM buffer needs to store 5 second ADC data. When a buffer is filled up, the average value of the data in the buffer is calculated. 


