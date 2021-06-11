# M480BSP_DataFlashProgramming
 M480BSP_DataFlashProgramming


update @ 2021/06/11

1. test data flash , with page programming , to prevent data erased

write index : 0xF0 , then read out data , and add 2 then write in again

write index : 0x1A , then read out data , and add 1 then write in again

write index : 0x2A , then read out data , and add 1 then write in again

write index : 0x3A , then read out data , and add 1 then write in again , and continue add value in each index 


2. below is log message screen , 

![image](https://github.com/released/M480BSP_DataFlashProgramming/blob/main/log_message.jpg)




