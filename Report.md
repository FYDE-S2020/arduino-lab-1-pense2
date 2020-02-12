Name: Jackson Schilling

EID: jks3355

Team Number: We have a team number?

## Questions

1. Why does your program need a setup and a loop?

    Setup is to initialize once, loop is to constantly run commands.

2. What is the downside to putting all your code in a loop?

    It will repeat infinitely.

3. Why does your code need to be compiled?

    It needs to be converted to machine code.

4. When lowering the frequency in procedure A, step 4, what is going wrong? Brainstorm some solutions. Dimmers exist in the real world. What is their solution?

    It cannot work at that frequency. I lowered the frequency to 12MHz and the logic analyzer was able to record data.

5. Why do you need to connect the logic analyzer ground to the ESP32 ground?

    So it can be part of the same circuit, and therefore the same relative 0V that is the ESP32 ground.

6. What is the difference between synchronous and asynchronous communication?

    Synchronous requires a clock to be set on both side and a constant stream of data. Asynchronous can be sent in different waves or with different timing.

7. Profile of UART: Sent X bytes in Y time 

    Sent 6 bytes in 0.51ms

8. Profile of SPI: Sent X bytes in Y time

    Sent 5 bytes in 0.12ms

9. Why is SPI so much faster than UART?

    SPI can send data as fast as it needs to, while UART has to depend on the input speed

10. list one pro and one con of UART

    Pro: Can send data at any point
    Con: Slower than SPI

11. list one pro and one con of SPI

    Pro: Faster than UART
    Con: Can only send data in a constant stream

12. list one pro and one con of I2C

    Pro: Can use multiple slave devices
    Con: Requires pull up resistors

13. Why does I2C need external resistors to work?

    Their lines are open-drain

## Screenshots

Procedure A, step 1:
![C:\Users\jacks\Documents\GitHub\arduino-lab-1-pense2\img](img/placeholder.png)

Procedure A, step 4:
![C:\Users\jacks\Documents\GitHub\arduino-lab-1-pense2\img](img/placeholder.png)

Procedure B, UART:
![C:\Users\jacks\Documents\GitHub\arduino-lab-1-pense2\img](img/placeholder.png)

Procedure B, SPI:
![C:\Users\jacks\Documents\GitHub\arduino-lab-1-pense2\img](img/placeholder.png)
