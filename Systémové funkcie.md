# Systémové funkcie
Užívateľ ich nevidí a nevie meniť ich parametre. 

## 1. Ochrana pred kondenzáciou
Aktivuje sa ak:
aktuálna vlhkosť > _savehumiON

Deaktivuje sa ak:
aktuálna vlhkosť < _savehumiOFF

Ak je aktívna tak mení riadenie ventiátora z tabuľky A na tabuľku B


## 2. Ochrana ventilátora
Nevedia sa aktivovať aj je jednotka v režime "3.1 Nočný režim"

### 2.1 Nízke otáčky
aktivuje sa ak:
stav "3.2 Nízke" trvá nepretržite viac ako 10 dní

zmení stav z "3.2 Nízke" na "3.4 Vysoké" na dobu 1 minúty


### 2.2 Vysoké otáčky
aktivuje sa ak:
stav "3.4 Vysoké" alebo "3.5 BOOST" trvá nepretržite viac ako 10 dní

zmení stav z "3.4 Vysoké" alebo "3.5 BOOST" na "3.4 Vysoké" na dobu 1 minúty


### 2.3 Upchatý filter
Nasadenie tejto funkcie zatiaľ odložíme. Príde až po vytvorení APP...
## 3. Servo klapka
Ak je stav "1.0 Stav" v režime OFF hodnota klapky 0%, else 100%