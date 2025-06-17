# `serial delay-crlf <0000>`

---

## Function

Sets the transmit delay, which can range from 0 to 86,400,000 milliseconds (up to 24 hours).

## Example
```
[admin@ssh-to-serial]>serial delay-crlf 300
UART Config - Base: 0x4000D000
 Clock: 120000000 Hz
 Baud: 115200
 Data Size: 8
 Parity: N
 Stop Bits: 1
 Flow Control: N
 Transmit Delay: 300 ms
Transmit delay set to 300 milliseconds.
```