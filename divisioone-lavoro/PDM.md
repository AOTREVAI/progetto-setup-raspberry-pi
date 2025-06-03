# PDM

| ID | Attività                          | Durata (ore) | Predecessori | Risorsa   |
|----|-----------------------------------|--------------|--------------|-----------|
| A  | Analisi infrastruttura di rete    | 4            | -            | componente1|
| B  | Definizione requisiti tecnici     | 2            | A            | componente2   |
| C  | Selezione hardware                | 3            | B            | componente2   |
| D  | Procurement componenti            | 24           | C            | componente2   |
| E  | Download e preparazione OS        | 2            | C            | componente2   |
| F  | Installazione sistema operativo    | 3            | D, E         | componente1|
| G  | Configurazione base sistema       | 4            | F            | componente1|
| H  | Configurazione rete statica       | 2            | G            | componente1|
| I  | Installazione Pi-hole             | 3            | H            | componente2   |
| J  | Configurazione avanzata Pi-hole   | 4            | I            | componente1|
| K  | Ottimizzazione prestazioni        | 3            | J            | componente2   |
| L  | Configurazioni sicurezza          | 4            | J            | componente1|
| M  | Backup configurazione router       | 1            | A            | componente2   |
| N  | Configurazione DNS router         | 2            | K, L, M      | componente2   |
| O  | Test funzionali                  | 4            | N            | componente1|
| P  | Test robustezza                  | 6            | O            | componente1|
| Q  | Documentazione tecnica            | 6            | P            | componente1|
| R  | Formazione utenti                 | 3            | Q            | componente2   |
| S  | Setup monitoraggio                | 4            | P            | componente2   |
