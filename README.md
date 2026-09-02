# SacketChatty — sito pubblico

Sito statico servito da GitHub Pages su <https://sacketchatty.github.io/>.

Esiste per due ragioni pratiche: i canali di distribuzione (Apple, Aptoide)
richiedono un sito dell'applicazione e un'informativa sulla privacy
raggiungibile a un URL pubblico.

| File | URL | A cosa serve |
|---|---|---|
| `index.html` | `/` | Presentazione dell'app e contatto di supporto |
| `privacy.html` | `/privacy.html` | Informativa sulla privacy, italiano e inglese |

## Modifiche all'informativa

L'informativa descrive **ciò che il codice fa davvero**, non un modello generico:
assenza di telemetria, crash reporting disattivato, natura del `deviceId`,
distinzione fra chi sviluppa l'app (che non tratta dati) e chi gestisce il
server (che è il titolare del trattamento).

Cambiando quei comportamenti nell'applicazione, l'informativa va aggiornata
**prima** del rilascio, con una nuova data di entrata in vigore.
