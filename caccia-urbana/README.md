# Caccia urbana

Videogioco multiplayer 3D per browser, senza armi né violenza: le **prede** si nascondono in una città e si confondono fra i passanti, i **cacciatori** devono riconoscerle tenendole nel mirino per tre secondi.

Tutto il gioco sta in un unico file `index.html` (Three.js da CDN, nessuna fase di compilazione).

- Gioca online: https://costalonga.org/giacomo/caccia-urbana/
- Modalità dimostrativa con utenti virtuali (bot) sempre disponibile.
- Multiplayer reale via WebRTC (PeerJS): chi crea la stanza condivide il codice di 5 caratteri, gli altri entrano con «Entra in una stanza». Il creatore fa da host e arbitro.
- Squadre: 3–5 cacciatori, 5–10 prede, 8–15 partecipanti; i posti liberi sono coperti da bot dichiarati.
- Funziona da computer (WASD + mouse) e da telefono (levetta virtuale, in orizzontale).

Per usare un proprio server (PeerServer, Firebase Realtime Database o Supabase) modifica la sezione «CONFIGURAZIONE MULTIPLAYER» all'inizio dello script in `index.html`. Nel file vanno solo chiavi pubbliche.

Realizzato da [@ginopizza](https://github.com/ginopizza).
