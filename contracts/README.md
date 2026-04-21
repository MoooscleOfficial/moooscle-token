# 🐮 Moooscle (MSCL) — Smart Contract Source Code

Questa cartella contiene **tutti i file sorgente** del contratto Moooscle (MSCL)
così come verificati su PolygonScan.  
Il contratto è stato suddiviso in **7 file**, esattamente come riportato nella
verifica on‑chain, per mantenere una struttura chiara, trasparente e fedele
alla versione pubblicata sulla blockchain.

---

## 📁 Struttura dei file (1–7)

I file sono riportati nello stesso ordine della verifica ufficiale:

1. **ERC20Asset.sol** — File principale del token MSCL  
2. **Ownable.sol** — Gestione proprietà (necessaria per la struttura originale)  
3. **ERC20.sol** — Implementazione standard ERC‑20  
4. **Initializable.sol** — Modulo di inizializzazione  
5. **ERC20Base.sol** — Logica base del token (file più esteso)  
6. **IERC165.sol** — Interfaccia ERC‑165  
7. **IERC7572.sol** — Interfaccia per metadata standardization  

Questi file ricostruiscono **al 100%** il contratto verificato su Polygon PoS.

---

## 🔗 Contratto ufficiale

**Address (Polygon PoS):**  
`0xB7D7AFcfFbb32B619e32597f2DeBaBF4F783F13A`

Verifica completa su PolygonScan:  
https://polygonscan.com/address/0xB7D7AFcfFbb32B619e32597f2DeBaBF4F783F13A

---

## 🧩 Perché il contratto è diviso in 7 file

PolygonScan mostra il codice sorgente in più file quando il contratto originale
è stato compilato con una struttura modulare.  
Per garantire trasparenza e coerenza:

- ogni file è stato ricreato **identico** alla versione verificata  
- nessuna modifica è stata introdotta  
- la struttura rispecchia esattamente quella on‑chain  

Questo permette a chiunque di:

- verificare il codice  
- ricompilare il contratto  
- confrontarlo con la versione on‑chain  
- studiare la struttura modulare originale  

---

## 🔒 Sicurezza & Trasparenza

- Nessuna funzione di mint  
- Nessuna funzione di burn  
- Nessuna blacklist  
- Nessun owner con privilegi speciali  
- Contratto completamente **immutabile**  
- Codice verificato pubblicamente  

---

## 📘 Licenza

Il codice segue la licenza originale riportata nei file sorgente (Apache‑2.0).

---

🐮 **Stay strong. Stay odd. Stay Mooobull.**
