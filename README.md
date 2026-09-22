# 💻 Digital Systems Architecture - VHDL Projects

[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-blue?logo=github)](https://github.com/simonefuorto/Architettura-di-Sistemi-Digitali/tree/main)

Questo repository contiene i progetti sviluppati per il corso di **Architettura dei Sistemi Digitali**, realizzati in linguaggio **VHDL** e testati/sintetizzati su board FPGA **Nexys A7-100T**. 

Il progetto esplora la progettazione hardware a vari livelli di astrazione, partendo dai componenti elementari fino ad arrivare alla microprogrammazione.

## 🛠 Argomenti e Architetture Implementate

1. **Reti Combinatorie Elementari:**
   - Progettazione strutturale di Multiplexer (16:1 e 16:4) e sistemi di interconnessione.
   - Sviluppo di sistemi integrati ROM + Macchina combinatoria.
   
2. **Reti Sequenziali Elementari:**
   - Riconoscitori di sequenze (Automi a stati finiti di Moore).
   - Shift Register parametrici (N-bit) con approccio comportamentale e strutturale.
   - Progettazione di un cronometro digitale completo.

3. **Macchine Aritmetiche:**
   - **Moltiplicatore di Booth:** Implementazione e simulazione dell'algoritmo di Booth per la moltiplicazione di numeri relativi.
   - **Divisore Non-Restoring:** Architettura per la divisione intera hardware.

4. **Protocolli di Comunicazione Hardware:**
   - Sviluppo di un sistema a due nodi comunicanti tramite protocollo di **Handshaking**.

5. **Microprogrammazione (Mic-1):**
   - Analisi e modifica del microcodice su architettura Mic-1.
   - Creazione di nuove microistruzioni agendo direttamente sui segnali di controllo dell'ALU e sul Control Store.

## ⚙️ Tecnologie Utilizzate
- **Linguaggio:** VHDL, Microcodice (assembler)
- **Software di Simulazione/Sintesi:** Xilinx Vivado
- **Hardware:** FPGA Nexys A7-100T

## 👥 Autori
- Simone Fuorto
- Federica Iervolino
- Roberta Acampora

---
*Per maggiori dettagli sull'implementazione, gli schemi a blocchi e gli Automi a Stati Finiti (FSM) progettati, si rimanda ai file PDF (Prima e Seconda Parte) allegati nella repository.*
