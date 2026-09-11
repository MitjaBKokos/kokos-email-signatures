KOKOS GMAIL SIGNATURES – GITHUB PAGES

KAJ JE V PAKETU
- index.html: stran za vse zaposlene z gumbom »Kopiraj podpis«
- assets/: KOKOS logo, portreti in badgei
- signatures/: posamezni HTML podpisi
- .nojekyll: GitHub Pages naj datoteke servira neposredno

POSTAVITEV NA GITHUB PAGES
1. Na službenem GitHub računu/repozitoriju ustvari PUBLIC repository, npr. kokos-email-signatures.
2. Razpakiraj ta ZIP.
3. V ROOT repozitorija naloži VSE iz te mape: index.html, .nojekyll, assets, signatures, README_GITHUB_PAGES.txt. Ne nalagaj samo ZIP-a.
4. GitHub: Settings > Pages.
5. Build and deployment > Source: Deploy from a branch.
6. Branch: main, folder: / (root), Save.
7. Počakaj, da GitHub pokaže naslov, npr. https://KOKOS-USERNAME.github.io/kokos-email-signatures/
8. Odpri ta github.io naslov. Zgoraj mora pisati »Pripravljeno za Gmail.«
9. Klikni »Kopiraj podpis« pri svojem imenu.
10. Gmail > Settings > See all settings > General > Signature > Create new.
11. Klikni v prazno polje podpisa in Ctrl+V.
12. Ne spreminjaj fonta z Gmail toolbarom in ne uporabi Remove formatting.
13. Save Changes.

POMEMBNO O FONTU
HTML vsebuje Hanken Grotesk kot primarni font in GitHub stran ga za predogled naloži iz Google Fonts.
Gmail sam ne podpira vdelave @font-face v podpis. Zato prejemnik brez Hanken Grotesk lahko vidi fallback font. To je omejitev HTML e-mail klientov, ne tega paketa.

POSTAVITEV
- 656 px osnovna širina
- KOKOS logo 201 × 149 px
- portret 103 × 120 px
- badge 85 × 57 px
- razmiki med badgei: 18 px, 18 px, 21 px, povzeto po mreži originalnega DOCX-a
- ime: Hanken Grotesk 23 pt / 700
- funkcija: Hanken Grotesk 9 pt / 600
- telefon/e-mail: Hanken Grotesk 11 pt
