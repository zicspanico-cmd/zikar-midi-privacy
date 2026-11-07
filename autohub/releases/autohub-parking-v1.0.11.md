# AutoHub Connect Parking 1.0.11

Aggiornamento installabile sopra Parking 1.0.10: package `it.autohub.ec3.hostprobe`, versionCode 111 e certificato originale. Conserva dati e attivazione.

Nuovo pulsante nella home del telefono: **Installa AutoHub Connect 2.0**.

- Prepara KingInstaller 2.5 scaricandolo dal progetto ufficiale, quando il componente necessario non è già disponibile.
- Accompagna l'utente al permesso Android per installare KingInstaller; l'installazione richiede conferma.
- Scarica AutoHub Connect 2.0.1, verifica SHA-256 e package e lo passa direttamente alla schermata KingInstaller tramite URI temporaneo con accesso in sola lettura.
- L'utente preme Installa in KingInstaller e conferma le richieste del sistema.
- Supporta la reinstallazione della stessa Connect 2.0.1; blocca il tentativo di sostituire una versione Connect più recente.
- Interfaccia in italiano, inglese, francese, spagnolo e tedesco.
- KingInstaller resta un progetto e un'app separati: il suo codice non viene incorporato o modificato. Le eventuali richieste aggiuntive di KingInstaller restano visibili.

Verifiche: compilazione locale con SDK API 37 e Build Tools 36.0.0, firma e allineamento APK, compatibilità statica Android 11, traduzioni e controlli di integrità sui due APK ufficiali. Verificato il codice dell'handler APK nel tag KingInstaller 2.5.

La prova completa su telefono e Android Auto resta da eseguire. L'invio a KingInstaller non garantisce da solo il riconoscimento dell'app o funzioni aggiuntive su tutte le configurazioni.

Sorgenti KingInstaller 2.5 (GPL-3.0): https://github.com/fcaronte/KingInstaller/tree/2.5
