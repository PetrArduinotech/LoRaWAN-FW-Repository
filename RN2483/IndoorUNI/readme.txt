FW pro Indoor UNI

End point Indoor UNI je univerz�ln�m senzorem pro pou�it� indoor a obsahuje tento HW:
- LoRaWAN transceiver na �ipu RN2483
- MCU ATmega328p s Arduino UNO bootloaderem
- senzor DHT22
- svorku p�ivedenou na interupt 1 (INT3)
- USB konektor pro extern� nap�jen� a hl�d�n� stavu nap�jen� USB/baterie

FW m� n�kolik modifikac�:
1. DTH - m��� pouze teplotu a vlhkost
2. DTHpower - m��� teplotu/vlhkost a sleduje stav nap�jen� USB/baterie
3. S0 ��ta�
4. Kontakt - mo�no pou��t pro sledov�n� stavu kontaktu nebo jako ot�esov� �idlo

