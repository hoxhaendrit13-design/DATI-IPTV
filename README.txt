IPTV-DATI — METËSIA UNLIMITED

PËRMBAJTJA
- index.html: website/player
- manifest.webmanifest: instalim si PWA
- sw.js: cache bazë për hapjen e website-it
- icon.svg, icon-192.png, icon-512.png: ikona

ÇFARË BËN
- Ngarkon M3U/M3U8 nga pajisja dhe liston URL-të http/https.
- Kërkim në kanale.
- Player HTML5 për stream-e që mbështeten nga shfletuesi.
- Nuk furnizon kanale dhe nuk dërgon playlistën e ngarkuar në server.

INSTALIM NË IPHONE
1. Publiko skedarët në një host HTTPS.
2. Hape adresën e website-it në Safari.
3. Prek Share (katrori me shigjetë lart).
4. Zgjidh Add to Home Screen / Shto në ekranin kryesor.
5. Aktivizo Open as Web App nëse shfaqet, pastaj Add.

SAMSUNG / ANDROID
1. Hape website-in në Chrome.
2. Prek menynë ⋮.
3. Zgjidh Install app ose Add to Home screen.

SHËNIM PËR APK
Ky projekt është PWA (website i instalueshëm), jo skedar APK. Për APK të vërtetë duhet paketim/build Android dhe nënshkrim; kjo nuk krijohet thjesht duke riemërtuar HTML në .apk. Mund të përdoret fillimisht PWA falas.

PUBLIKIM FALAS ME GITHUB PAGES
1. Hape github.com dhe krijo llogari falas.
2. Krijo repository të ri, p.sh. iptv-dati, me Public.
3. Ngarko të gjithë skedarët e kësaj dosjeje në root të repository.
4. Shko te Settings → Pages.
5. Te Build and deployment zgjidh Deploy from a branch, branch main, folder /(root), Save.
6. Prit derisa GitHub të japë adresën Pages. Hape atë adresë në Safari/Chrome.
