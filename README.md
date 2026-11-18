# Oma treenipäiväkirja

Mobiiliystävällinen, paikallisesti tallentava treenipäiväkirja (PWA).

## Julkaisu GitHub Pagesilla
1. Luo GitHubissa uusi **Public** repository nimellä `oma-treenipaivakirja`.
2. Pura tämän ZIP-paketin sisältö tietokoneellesi.
3. Avaa repository → **Add file → Upload files**.
4. Lataa kaikki tämän kansion tiedostot (index.html, manifest.json, sw.js, ikonit).
5. Valitse **Commit changes**.
6. Avaa repositoryn **Settings → Pages**.
7. Valitse **Deploy from a branch**, branch `main`, folder `/ (root)`, ja paina Save.
8. Odota julkaisu valmiiksi. GitHub näyttää Pages-osoitteen asetussivulla.

## iPhone
Avaa julkaistu Pages-osoite Safarissa → Jaa → Lisää Koti-valikkoon.

## Tallennus
Treenit tallentuvat selaimen localStorageen tällä laitteella. Ne eivät synkronoidu muihin laitteisiin. Selaimen tietojen poistaminen voi poistaa myös treenihistorian. Pidä varmuuskopio manuaalisesti, jos tiedot ovat tärkeitä.

## Päivitys
Kun lataat myöhemmin uuden `index.html`-version repositoryyn, service workerin CACHE-tunniste kannattaa päivittää tiedostossa `sw.js`, jotta vanha versio ei jää välimuistiin.
