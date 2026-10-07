RUNAWAY – INTERAKTIV UNDERVISNINGSMODELL

Innehåll
index.html – hela modellen i en enda fil, utan externa programbibliotek.
README.txt – denna instruktion.

Prova på din dator
Dubbelklicka på index.html. Modellen öppnas i webbläsaren och fungerar
även utan internet. Eleverna behöver inget ChatGPT-konto.

Publicera på GitHub Pages
1. Packa upp ZIP-filen på din dator.
2. Skapa ett nytt repository, till exempel runaway-modell, på GitHub.
3. Välj Add file > Upload files och ladda upp index.html.
   Filen ska ligga direkt i repositoryts rot, inte i en undermapp.
   README.txt kan också laddas upp men behövs inte för modellen.
4. Välj Settings > Pages.
5. Under Build and deployment väljer du Source: Deploy from a branch.
6. Välj branch main och mappen / (root). Klicka Save.
7. När sidan har publicerats visas adressen under Settings > Pages.
   Dela den länken med eleverna, exempelvis via Itslearning.

Om du använder ett befintligt repository som publiceras från /docs:
lägg index.html i docs i stället. Undvik att skriva över en befintlig
startsida om du vill behålla den. Ett separat repository är enkelt.

Officiell instruktion:
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

Användning
Två reglage: temperatur och kylförmåga. Grafen visar värmeeffekt i kW
mot reaktortemperatur i °C. Jämviktspunkter och nettovärme visas.
Förklarande text, fem elevuppgifter och ett utfällbart facit ingår.
Facit är synligt för alla som använder sidan; det är inte lösenordsskyddat.

Modellval
Kylkurvan utgår från ett kylmedium på 20 °C och Q = UA*(T-Tkyl).
Reaktionskurvan är en schematisk exponentiell approximation.
Detta ger möjlighet att visa både stabil och instabil värmebalans.
Temperaturreglaget väljer ett läge; ingen tidssimulering utförs.
Värden och gränser är illustrativa, inte data för en verklig reaktion.

Faktabakgrund
https://www.hse.gov.uk/pubns/indg254.htm
https://www.hse.gov.uk/comah/sragtech/techmeasreaction.htm
