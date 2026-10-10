# Regola globale — immagini generate da ChatGPT verso GitHub

**Stato: APPROVATA / DICHIARATA dall'autore il 10/10/2026.** Ambito: tutti i progetti e i repository in cui si generano nuove illustrazioni, copertine o asset grafici.

## Flusso obbligatorio (Drive NON intermedio)
1. **Crea** l'immagine in **PNG** come originale di lavorazione.
2. **Prepara** il file destinato al repository in **JPEG/JPG di alta qualità** (di norma qualità 90–95%, profilo sRGB, dimensioni richieste dal progetto), senza cambiare composizione, rapporto o contenuto approvato. Mantieni il PNG originale durante la conversione; se serve trasparenza o qualità senza perdita (loghi, UI, diagrammi), usa un PNG/WebP appropriato come eccezione motivata, non un JPEG con sfondo inatteso.
3. **Identifica** il repository autorevole, la branch e il percorso di destinazione secondo la struttura del progetto. Controlla duplicati e convenzioni di nomenclatura.
4. **Tenta PRIMA il trasferimento diretto a GitHub**, con metodo adatto ai file binari (Git blob/base64 oppure altro metodo realmente disponibile). **Non caricare su Google Drive come passaggio intermedio**. Conserva il rapporto qualità/peso adatto all'asset.
5. **Verifica** commit GitHub, percorso, file reale e formato risultante (possibilmente byte/dimensioni o checksum). Solo dopo conferma `DOCUMENTATO / COMPLETATO` e comunica commit e percorso.
6. **Se il caricamento diretto non riesce**, non dichiarare successo e non passare silenziosamente a Drive. Comunica il limite; consegna il JPG qui in chat se possibile oppure proponi un fallback esplicito, richiedendo consenso prima di usare Drive.
7. **Non duplicare** file su Drive per abitudine e non cancellare originali, file esistenti o backup senza richiesta esplicita.
8. **Privacy e pubblicazione:** non inviare immagini personali/sensibili a repository pubblici; verifica l'autorizzazione alla pubblicazione. Nei progetti con repository privato canonico e Reader/pubblico, salva prima nel privato e pubblica una copia solo secondo le regole del progetto.
9. **Precedenza:** le regole specifiche di impaginazione, dimensioni, trasparenza, formato di stampa e riservatezza del singolo progetto prevalgono quando più restrittive. Questo flusso si applica a **immagini generate**, non a scansioni/documenti personali acquisiti, i cui originali vanno preservati.

**Sintesi:** PNG sorgente → JPEG di qualità → GitHub diretto → verifica commit. Google Drive solo su richiesta esplicita.
