## MFRC522 Pin Layout for Arduino

This table shows the typical pin layout used when connecting an MFRC522 RFID Reader/PCD to various Arduino boards:

| Signal    | Pin (MFRC522) | Pin (Uno/101) | Pin (Mega) | Pin (Nano v3) | Pin (Leonardo/Micro) | Pin (Pro Micro) |
| --------- | ------------- | ------------- | ---------- | ------------- | -------------------- | --------------- |
| RST/Reset | RST           | 9             | 5          | D9            | RESET/ICSP-5         | RST             |
| SPI SS    | SDA(SS)       | 10            | 53         | D10           | 10                   | 10              |
| SPI MOSI  | MOSI          | 11 / ICSP-4   | 51         | D11           | ICSP-4               | 16              |
| SPI MISO  | MISO          | 12 / ICSP-1   | 50         | D12           | ICSP-1               | 14              |
| SPI SCK   | SCK           | 13 / ICSP-3   | 52         | D13           | ICSP-3               | 15              |

**Notes:**

- Some pins may have alternative names depending on the specific Arduino board model.
- This is a typical layout; consult your board's documentation for exact pin mappings.
