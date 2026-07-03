# IT-Ausfall-Zähler

Zeigt die Tage seit dem letzten IT-bedingten Systemausfall der Praxis.
Eingebettet im Notion Praxis-Intranet (Block: /embed).

- **Anzeige:** https://shnsn.github.io/it-ausfall-zaehler/
- **Stand:** `status.json` (`lastOutage`, Format JJJJ-MM-TT)
- **Reset:** roter Knopf im Widget (braucht `#k=<Token>` in der Embed-Adresse)
  oder Claude sagen: "IT-Ausfall — Zähler zurücksetzen"

## Token erneuern (läuft nach 1 Jahr ab)

1. github.com/settings/personal-access-tokens → neues Fine-grained Token,
   nur dieses Repo, Contents: Read and write
2. Embed-Adresse in Notion aktualisieren: `https://shnsn.github.io/it-ausfall-zaehler/#k=<neues Token>`
3. Claude das neue Token geben (für Resets per Zuruf)
