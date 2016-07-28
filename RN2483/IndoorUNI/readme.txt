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
3. UNIContact - mo�no pou��t pro sledov�n� stavu kontaktu nebo jako ot�esov� �idlo, detekuje p��tomnost nap�t� z adapt�ru na USB. Pos�l� v payloadu rovn� teplotu a nap�t�. Tento FW je nejkomplexn�j��m FW pro INdoor UNI a vyu��v� v�echny jeho dostupn� HW prost�edky


V p��prav�:
FW pro analogov� m��en� na USB portu - mo�no vyu��t nejen ro detekci p��tomnosti/nep��tomnosti nap�jen� ale tak� pro zm��en� nap�t� v rozmez�ch 0 a� 3V. 

