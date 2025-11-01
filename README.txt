NOTEVAULT ARG — PACKAGE
========================

Files included:
- index.html           : The main "Notebook" page with trial -> subscribe cinematic.
- thecontract.html     : The Contract page (the ritual flow). If user completes the ritual, localStorage 'nv_subscribed' is set to '1'.
- pro.html             : The expanded Pro Realm (NoteVault Pro) with recovered fragments, seals, codex, and ambient audio. Local-only; stores fragments and seals in localStorage keys with prefix 'nv_pro_'.
- vault/thirteen/index.html : The secret final Vault (direct URL). This page is self-contained and ends the ARG (final closure).
- sigil.svg            : Decorative sigil used by Pro and Vault pages. Contains harmless metadata (a tiny base64 clue).
- README.txt           : This file.

How to use:
1. Extract the ZIP into a folder and open index.html in your browser (no server required for basic local testing).
2. To unlock Pro Realm in the normal flow:
   - From index.html: when the trial ends, clicking 'SUBSCRIBE' opens thecontract.html.
   - On thecontract.html: fill the symbolic fields (name backwards, 16 zeros, accept) and click 'SURRENDER' to set the localStorage flag and reveal a link to pro.html.
   - pro.html reads localStorage flags and behaves as the Pro Realm UI.
3. The secret climactic page is at: /vault/thirteen/index.html (open it directly in the browser by navigating to the file path).
   - It is deliberately a direct secret URL; do not link it publicly unless you want players to find it.
4. All data is stored in browser localStorage. No network calls are made. No files are modified on disk by the pages.

ARG notes & safety:
- The content is fictional ARG material. It contains references to bargains and cultic themes for storytelling only.
- No code in this package deletes files or performs harmful operations. All "destruction" is simulated in the browser using visuals and localStorage flags.
- If you want to reset the experience locally, open dev tools -> Application -> Local Storage and remove keys starting with 'nv_'.

Attribution:
- This package was built per your instructions to create a nostalgic notes app that hides a theatrical ARG and a secret final vault.
- The narrative (Cult of Scriptura, Red Quills, Lost Server) is original to this package.

Enjoy — and tell your players to tread carefully in the margins.
