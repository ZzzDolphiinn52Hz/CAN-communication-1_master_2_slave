# CAN-communication-1_master_2_slave

## Master 1

- button PA0 EXTI to send 2 byte data at Standard ID = 0x103
- receive data from another to Rx[0], Rx[1]

```C
TxData[0] = 100; // delay for led blinking in ms
TxData[1] = 10;   // number of times to blink the led
```

## Slave 1

## Slave 2
