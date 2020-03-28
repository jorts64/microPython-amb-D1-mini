# microPython-amb-D1-mini
##Programant amb microPython amb el D1 mini

El curs 2018-2019 vam introduir la programació amb microPython a 3r d'ESO al meu institut, amb l'ajut dels profesors Borja Diaz i Jose Toro. Vam utilitzar el programari uPyCraft amb Ubuntu 16.04 i maquinari Wemos (Lolin) D1 mini (ESP8266).

Vam preparar uns kits pels alumnes amb
- D1 mini
- base triple
- Buzzer shield
- DHT shield
- OLED display shield
- RGB shield
- Button shield

Voliem facilitar l'accés al maquinari per part dels alumnes, i jo vaig preparar un codi base amb unes funcions bàsiques que es carreguen al boot.py i uns exemples d'utilització per a cada shield
En Borja va preparar les activitats pels alumnes
L'experiència va ser tot un èxit, i el curs 2019-2020 en vam fer una revisió amb l'ajut del Alejandro Pérez.

##Important!
Si bé el uPyCraft funciona molt bé amb Windows, Mac i Ubuntu 16.04, amb versions posteriors d'Ubuntu hem tingut problemes per un tema de llibreries, malgrat hi ha una versió modificada per Qt5 que no vam poder fer funcionar. Per aizò vaig buscar una alternativa per a les noves version d'Ubuntu. Després de provar altres entorns, vaig crear el meu propi entorn de programació que utilitza l'editor Geany, ampy i nanocom.
