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
3. UNIContact - možno použít pro sledování stavu kontaktu nebo jako otøesové èidlo, detekuje pøítomnost napìtí z adaptéru na USB. Posílá v payloadu rovnìž teplotu a napìtí. Tento FW je nejkomplexnìjším FW pro INdoor UNI a využívá všechny jeho dostupné HW prostøedky


V pøípravì:
FW pro analogové mìøení na USB portu - možno využít nejen ro detekci pøítomnosti/nepøítomnosti napájení ale také pro zmìøení napìtí v rozmezích 0 až 3V. 

