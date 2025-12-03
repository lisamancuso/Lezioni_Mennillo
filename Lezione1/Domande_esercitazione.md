# Risposte a domande esercitazione
Domanda 1 Qual è la differenza tra cd progetti e cd ~/progetti?
Domanda 2 Come torni alla home directory con il comando più breve?
Domanda 3 Come crei cartelle annidate in un solo comando?
Domanda 4 Qual è la differenza tra cp e mv?
Domanda 5 Come copi un'intera cartella con tutti i contenuti?
Domanda 6 È possibile rinominare con mv? Come?

1. `cd progetti` porta alla directory progetti se è presente, `cd ~/progetti` parte dalla home dell'utente.
2. Si torna alla home directory con `cd`.
3. `mkdir -p Cartella`
4. `cp` copia il file, `mv` muove il file. Entrambi possono essere usati per rinominare file e cartelle.
5. Per copiare una cartella e i suoi contenuti il comando è `cp -r Cartella`
6. Per rinominare con `mv` si deve mettere il percorso con il nome nuovo del file o cartella.
Esempio `mv mioFile1 File1`
