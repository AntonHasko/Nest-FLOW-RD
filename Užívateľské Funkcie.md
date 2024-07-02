# Užívateľské funkcie  

## 1.0 Stav (IR/APP)
ON/OFF

## 2.0 Režim vetrania 
### 2.1 Privádzanie vzduchu (IR/APP)
### 2.2 Odvádzanie vzduchu (IR/APP)
### 2.3 Rekuperácia tepla  (IR/APP)
   Rekuperácia sa dosiahne striedaním smeru otáčanie ventilátora podľa časovanie na základe zvolenej tabuľky a parametrov

## 3.0 Objem vetrania (otáčky ventilátora)  
### 3.1 Nočný režim  (IR/APP/Lux senzor)
Táto funkcia blokuje ochranné systémové funkcie
Ak bola táto funkcia aktivovaná užívateľom, sama sa vypne po 10 hodinách, aby bolo možné v prípade potreby vykonať ochranné systémové funkcie. 
### 3.2 Nízke (IR/APP)
### 3.3 Sterdné (IR/APP)
### 3.4 Vysoké (IR/APP)
### 3.5 BOOST (IR/APP)
### 3.6 *Odvlhčovanie* (APP)
nevie užívateľ spustiť priamo, aktivuje ju funkcia "6.0 Odvlhčovanie"

## 4.0 Zlúčenie jednotiek (APP)
Ak sa v jednej miestnosti nachádza viac jednotiek je potrené ich zlúčiť pod spoločné ovládanie.  
Maximálny počet zlúčených jednotiek je 8. 

Množina zlúčených jednotie si v režime "2.3 Rekuperácia tepla" strieda poradie privádzaného a odvádzaného vzduchu.
Ak 1 jednotka aktuálne privádza vzduch tak 2 odvádza 3 privádza 4 odvádza atd...

Prvá jednotka sa nastaví ako MASTER, ostatné sú SLAVE
Všetky ostatné systémové ochranné funkcie a užívateľské parametre sa z jendotky MASTER aplikujú aj na jednotky SLAVE

### Prevádzkové zmeny zlúčených jednotiek  
Režim vetranie - 3. rekuperácia tepla sa v prípade zlúčených jednotiek riadi na základe tabuľky B

## 5.0 Automatický nočný režim (APP)
Ak nameraná hodnota zo svetelného senzora klesne pod systémovú hodnotu, aktivuje sa **Nočný režim**
Ak je aktivovaný nočný režim cez túto funkciu (nebol zvolení užívateľom), zotrvá v nej 10 hodín alebo pokiaľ hodnota svetelného senzora nestúpne nad hodnotu ...
Funkcia nebráni užívateľovi zmeniť režim

## 6.0 Odvlhčovanie (APP)
blokovanie funkcie: 1 aktívny nočný režim  
Ak hodnota relatívnej vlhkosti stupne nad ... aktivuje sa Objem vetrania 6. Odvlhčovanie  
Ak užívateľ zmení Objem vetrania funkcia sa vypne do najbližšieho reštartu.  
V jarnej a letnej prevádzke je táto funkcia vypnutá.  
Ročné obdobie možno zistiť na základe teploty privádzaného vzduchu alebo prostredníctvom internetu a polohy zaregistrovanej jednotky.  Teplota sa ustáli najskôr po x sekundách privádzaného vzduchu. 

## 7.0 Riadenie kvality vzduchu (APP)
...
## 8.0 Prevádzkový kalendár (APP)
