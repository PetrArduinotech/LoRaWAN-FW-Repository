FW pro Indoor UNI

End point Indoor UNI je univerzálním senzorem pro použití indoor a obsahuje tento HW:
- LoRaWAN transceiver na èipu RN2483
- MCU ATmega328p s Arduino UNO bootloaderem
- senzor DHT22
- svorku pøivedenou na sdílený interupt
- USB konektor pro externí napájení a hlídání stavu napájení USB/baterie
- S0 èítaè impulsù

FW má nìkolik modifikací:
1. DTH - mìøí pouze teplotu a vlhkost a sleduje stav napájení USB/baterie
2. S0counter - èítaè impulsù
3. Contact - možno použít pro sledování stavu kontaktu nebo jako otøesové èidlo

