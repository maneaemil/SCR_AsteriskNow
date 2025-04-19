# SCR_AsteriskNow
Acest repo conține 3 fisiere: `sip.conf`, `extensions.conf` și `iax.conf`

Acestea declară anumite funcții cerute de specificațiile proiectului.

Valori XYZ primite: X=3; Y=7; Z=3.

# Specificații
* Minim 2 abonați SIP (cu nr. telefon 1XYZ, 2XYZ) [1373, 2373]
* Minim 2 abonați IAX2 (cu nr. telefon 3XYZ, 4XYZ) [3373, 4373]
* Funcții exclusive pt SIP (variabila Y) [Funcții din categoria SAY]
* Funcții exclusive pt IAX2 (variabila Z) [Funcții din categoria RECORD]

## Funcții 
SIP => SayAlpha(), SayDigits(), SayNumber(), SayPhonetic(), SayUnixTime()
IAX2 => Dictate(), Monitor(), Record()
