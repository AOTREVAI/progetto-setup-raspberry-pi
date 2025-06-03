# Work Breakdown Structure (WBS)
***
## Setup Pi-hole DNS Sinkhole su Hardware Generico
1. PIANIFICAZIONE E ANALISI REQUISITI

	1.1 Analisi dell'infrastruttura di rete esistente

		1.1.1 Mappatura della rete domestica/aziendale

		1.1.2 Identificazione del router e configurazione DNS attuale

		1.1.3 Verifica della disponibilità di indirizzi IP statici

		1.1.4 Documentazione della configurazione di rete corrente

	1.2 Definizione dei requisiti tecnici

		1.2.1 Stima del traffico DNS previsto

		1.2.2 Definizione dei requisiti di uptime e ridondanza

		1.2.3 Identificazione delle liste di blocco necessarie

		1.2.4 Pianificazione dei backup e disaster recovery
2. SELEZIONE E PROCUREMENT HARDWARE

	2.1 Analisi e selezione hardware

		2.1.1 Definizione delle specifiche minime (CPU, RAM, storage)

		2.1.2 Valutazione opzioni hardware (Raspberry Pi, Mini PC, server)

		2.1.3 Considerazioni su consumo energetico e dimensioni

		2.1.4 Analisi costo-beneficio delle opzioni

	2.2 Acquisizione componenti

		2.2.1 Acquisto hardware principale

		2.2.2 Procurement scheda microSD/SSD (se necessario)

		2.2.3 Acquisizione alimentatore e cavi di rete

		2.2.4 Verifica accessori aggiuntivi (case, dissipatori)

3. PREPARAZIONE SISTEMA OPERATIVO

	3.1 Selezione e download OS

		3.1.1 Scelta della distribuzione Linux (Raspberry Pi OS, Ubuntu, Debian)

		3.1.2 Download dell'immagine del sistema operativo

		3.1.3 Verifica dell'integrità del file scaricato (checksum)3.1.4 Preparazione degli strumenti di flashing

	3.2 Installazione sistema operativo

		3.2.1 Flashing dell'immagine su microSD/SSD

		3.2.2 Configurazione iniziale (SSH, utenti, password)

		3.2.3 Configurazione della connessione di rete

		3.2.4 Test di boot e connettività iniziale

4. CONFIGURAZIONE BASE DEL SISTEMA

	4.1 Setup iniziale del sistema

		4.1.1 Aggiornamento del sistema operativo

		4.1.2 Configurazione timezone e localizzazione

		4.1.3 Setup dell'accesso SSH e sicurezza

		4.1.4 Configurazione firewall di base

	4.2 Configurazione di rete

		4.2.1 Assegnazione IP statico al dispositivo

		4.2.2 Configurazione DNS temporanei per l'installazione

		4.2.3 Test di connettività Internet

		4.2.4 Configurazione hostname e identificazione di rete

5. INSTALLAZIONE E CONFIGURAZIONE PI-HOLE

	5.1 Installazione Pi-hole

		5.1.1 Download e esecuzione dello script di installazione

		5.1.2 Configurazione delle opzioni durante l'installazione

		5.1.3 Selezione dell'interfaccia di rete

		5.1.4 Configurazione della password di amministrazione

	5.2 Configurazione avanzata Pi-hole

		5.2.1 Configurazione delle liste di blocco personalizzate

		5.2.2 Setup delle whitelist e blacklist

		5.2.3 Configurazione dei DNS upstream

		5.2.4 Personalizzazione delle impostazioni di privacy

6. CONFIGURAZIONE AVANZATA E OTTIMIZZAZIONE

	6.1 Ottimizzazione delle prestazioni

		6.1.1 Configurazione della cache DNS

		6.1.2 Ottimizzazione dei log e rotazione

		6.1.3 Configurazione delle metriche di monitoraggio6.1.4 Setup della compressione dei log

	6.2 Configurazioni di sicurezza

		6.2.1 Hardening del sistema operativo

		6.2.2 Configurazione HTTPS per l'interfaccia web

		6.2.3 Setup di backup automatici

		6.2.4 Configurazione del monitoraggio system health

7. INTEGRAZIONE CON LA RETE

	7.1 Configurazione router

		7.1.1 Accesso all'interfaccia di amministrazione del router

		7.1.2 Backup della configurazione attuale del router

		7.1.3 Modifica delle impostazioni DNS primarie

		7.1.4 Configurazione DNS secondario (opzionale)

	7.2 Implementazione e reindirizzamento DNS

		7.2.1 Impostazione del Pi-hole come DNS primario

		7.2.2 Configurazione DHCP per distribuire nuovo DNS

		7.2.3 Verifica della propagazione delle impostazioni

		7.2.4 Test di risoluzione DNS da dispositivi client

8. TESTING E VALIDAZIONE

	8.1 Test funzionali

		8.1.1 Verifica del blocco degli annunci

		8.1.2 Test di risoluzione DNS su diversi dispositivi

		8.1.3 Controllo delle prestazioni di risoluzione

		8.1.4 Verifica del logging e delle statistiche

	8.2 Test di robustezza

		8.2.1 Test di failover in caso di downtime

		8.2.2 Verifica del comportamento sotto carico

		8.2.3 Test di recupero da backup

		8.2.4 Controllo della stabilità a lungo termine

9. DOCUMENTAZIONE E DEPLOYMENT

	9.1 Documentazione tecnica

		9.1.1 Creazione della documentazione di installazione

		9.1.2 Documentazione delle configurazioni personalizzate

		9.1.3 Guida per la manutenzione ordinaria9.1.4 Procedure di troubleshooting

	9.2 Formazione e handover

		9.2.1 Training per l'utilizzo dell'interfaccia web

		9.2.2 Istruzioni per la gestione delle liste di blocco

		9.2.3 Guida per il monitoraggio e la manutenzione

		9.2.4 Contatti e risorse per il supporto

10. MANUTENZIONE E MONITORAGGIO

	10.1 Setup monitoraggio

		10.1.1 Configurazione degli alert automatici

		10.1.2 Setup del monitoraggio delle prestazioni

		10.1.3 Configurazione backup automatici

		10.1.4 Pianificazione degli aggiornamenti

	10.2 Procedure di manutenzione

		10.2.1 Definizione della pianificazione degli aggiornamenti

		10.2.2 Procedure di pulizia log e manutenzione storage

		10.2.3 Aggiornamento periodico delle liste di blocco

		10.2.4 Revisione periodica delle configurazioni
