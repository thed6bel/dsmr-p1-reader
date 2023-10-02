LAST VERSION OF DSMR WORK PERFECTLY WITH ALL BELGIUM DIGITAL METER 

# dsmr-p1-reader
dsmr p1 for sibelga digital meter

FR :

j'ai compilé avec l'aide de Pvlerick (https://github.com/Pvlerick/esphome) un binaire pour rendre compatible les compteurs bruxellois avec ESPHOME

il vous suffit de flasher le .bin avec esphome-flasher (https://github.com/esphome/esphome-flasher/releases) ou depuis votre navigateur https://web.esphome.io/.
il vous faudra copier exactement le code qui se trouve dans p1reader.yaml, enregistrez-le.
votre esp8266 va créer un réseau wifi "Dsmr P1 Reader Fallback Hotspot", connectez-vous dessus avec le mot de passe : dsmrp1reader
une page devrais s'ouvrir pour vous demander le nom de votre réseau wifi et son mot de passe, renseignez ces informations et enregistrez.

au démarage il devrais se connecter à esphome et remonter après une trentaine de secondes les inforamations de votre compteurs si celui-ci y est connecté


NE SURTOUT PAS FAIRE D'UPDATE du module en tous cas pas tant que le BUG n'est pas corriger dans la version officiel de ESPHOME
https://github.com/esphome/issues/issues/2954


NL : 

Ik heb met de hulp van Pvlerick (https://github.com/Pvlerick/esphome) een binair bestand samengesteld om de Brusselse tellers compatibel te maken met ESPHOME

je hoeft alleen maar de .bin te flashen met esphome-flasher (https://github.com/esphome/esphome-flasher/releases) of vanuit je browser https://web.esphome.io/.
u moet exact de code kopiëren die u vindt in p1reader.yaml, opslaan.
uw esp8266 zal een "Dsmr P1 Reader Fallback Hotspot" wifi-netwerk creëren, maak er verbinding mee met het wachtwoord: dsmrp1reader
er zou een pagina moeten openen om u te vragen naar de naam van uw wifi-netwerk en het bijbehorende wachtwoord, vul deze informatie in en sla op.

bij het opstarten zou het verbinding moeten maken met esphome en na ongeveer dertig seconden de informatie van uw tellers moeten retourneren als het ermee is verbonden


UPDATE de module in ieder geval NIET totdat de BUG is gecorrigeerd in de officiële versie van ESPHOME
https://github.com/esphome/issues/issues/2954
