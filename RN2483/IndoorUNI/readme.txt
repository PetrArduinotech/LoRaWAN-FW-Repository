FW pro Indoor UNI

End point Indoor UNI je univerzálním senzorem pro použití indoor a obsahuje tento HW:
- LoRaWAN transceiver na èipu RN2483
- MCU ATmega328p s Arduino UNO bootloaderem
- senzor DHT22
- svorku pøivedenou na interupt 1 (INT3)
- USB konektor pro externí napájení a hlídání stavu napájení USB/baterie

FW má nìkolik modifikací:
1. DTH - mìøí pouze teplotu a vlhkost
2. DTHpower - mìøí teplotu/vlhkost a sleduje stav napájení USB/baterie
3. S0 èítaè
4. Kontakt - možno použít pro sledování stavu kontaktu nebo jako otøesové èidlo

