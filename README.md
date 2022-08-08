# -internet-controlled-conveyor-belt

Projekt w założeniu ma przedstawiać taśmociąg sterowany zdalnie przez sieć. Program będzie miał możliwość sterowania prędkością oraz kierunkami silników każdego z osobna oraz czujnik sortowania w zależności od koloru przedmiotu który będzie się znajdować na taśmociągu , będzie go wypychać prasom lub też przepuszczać dalej. Urządzenie również będzie posiadać zabezpieczenie w postaci czytnika kart dostępu 

Do Wykonania całości zostały wykorzystane :
- Arduino 
- Moduł sterowania silnikami DC L298N 
- 2 silniki DC 12V 
- Zasilanie 12 V
- Moduł Ethernet ENC28j60 
- Rj45 
- Przewody połączeniowe ź ź 
- przewody połączeniowe m m 
- 2 baterie 9 V 
- czytnik kart dostępu RFID-RC522
- karte uwierzytelnianie dostępu 



1. W pierwszym punkcie zostały wykonane testy na module Ethernet czy jest posiadany dostęp do sieci oraz do spisania danych dotyczących sieci które będą potrzebne w dalszej części projektu do stworzenia Server-Weba który umożliwi nam sterowanie całym projektem 
2. Został stworzony program który tworzy nam serwer-Web w którym będziemy konfigurować ustawienia taśmociągu takie jak prędkość oraz kierunek obrotów 
