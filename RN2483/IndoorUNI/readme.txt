FW pro Indoor UNI

End point Indoor UNI je univerz�ln�m senzorem pro pou�it� indoor a obsahuje tento HW:
- LoRaWAN transceiver na �ipu RN2483
- MCU ATmega328p s Arduino UNO bootloaderem
- senzor DHT22
- svorku p�ivedenou na sd�len� interupt
- USB konektor pro extern� nap�jen� a hl�d�n� stavu nap�jen� USB/baterie
- S0 ��ta� impuls�

FW m� n�kolik modifikac�:
1. DTH - m��� pouze teplotu a vlhkost a sleduje stav nap�jen� USB/baterie
2. S0counter - ��ta� impuls�
3. Contact - mo�no pou��t pro sledov�n� stavu kontaktu nebo jako ot�esov� �idlo

