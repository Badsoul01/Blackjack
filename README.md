# 🃏 Terminálový blackjack v Pythonu

Klasická karetní hra blackjack

## ✨ Funkce
* **Sázkový systém:** Hra začíná s 10 zlaťáky na účtě. Během hry se sází na výsledek.
* **Dynamické Eso:**  Eso se může počítat jako hodnota 1 nebo 11.
* **Akce v tahu:**  Během tahu jsou možnosti tahat další kartu, ukončit tah nebo zdojnásobit sázku
* **Chytrý krupiér (AI):**  Počítač hraje podle kasinových standardů- automaticky tahá další karty, pokud nedosáhl součtu minimálně 17.

##  💰 Výplaty a vyhodnocení

| Situace                          | Vyhodnocení akce               |
|:---------------------------------|:-------------------------------|
| **Překročení 21 (hráč)**         | Okamžitá prohra sázky (-100%)  |
| **Překročení 21 (krupiér)**      | Hráč vyhrává částku (+100%)    |
| **Blackjack (21 ze dvou karet)** | Speciální výplata 3:2 (+150%)  |
| **Běžná výhra (bližší k 21)**    | Hráč vyhrává částku (+100%)    |
| **Remíza (stejný součet)**       | Vrací se polovina sázky (+50%) |


## 🎮 Ovládání

Veškeré akce (sázky, volba hodnoty Esa, tahy) se zadávají pomocí **čísel** a potvrzením klávesou `Enter`.

## 🚀 Instalace

Projekt nevyžaduje instalaci žádných externích knihoven přes `pip`. Vše běží čistě na standardních knihovnách Pythonu (využívá pouze modul `random`).

1. Naklonuj repozitář [Blackjack](https://github.com/Badsoul01/Blackjack):
    ```bash
    git clone https://github.com/Badsoul01/Blackjack.git
    ```
2. Přejdi do složky s projektem:
    ```bash
   cd blackjack
    ```
3. Spusť hru přes hlavní soubor:
    ```bash
   python3 blackjack.py
    ```
## 🛠️ Použité technologie 
* **Python 3**
* **Procedurální programování**

