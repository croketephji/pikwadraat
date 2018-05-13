---
title: Een lokale kopie van de site downloaden
layout: documentatie
---

Git is een versiebeheersysteem. Het houdt bij welke documenten je aangepast hebt. Dankzij Git lopen we geen risico om informatie van de site kwijt te raken. In een paar stappen zet je de aanpassingen online met het programma GitHub Desktop.

1. Ga naar [desktop.github.com](https://desktop.github.com) en klik op de paarse knop om GitHub Desktop te downloaden.<a href="https://desktop.github.com"><img src="/assets/documentatie/github-desktop-dl.png" alt="GitHub downloaden" class="cover"></a>
2. Installeer het programma en open het.<br>Het programma geeft de boodschap *No repositories found*. Geen probleem! Een *repository* is een bestandsmap die wordt opgevolgd door GitHub Desktop. Onze *repository* zal een lokale kopie van de website zijn. We maken al onze toevoegingen en aanpassingen eerst op de lokale kopie, en uploaden die dan naar het internet.<br>Laten we een lokale kopie maken, of *clonen*. Klik op *Clone a repository*.<img src="/assets/documentatie/github-desktop-first-launch.png" alt="GitHub Desktop First Launch" class="cover">
3. Er opent zich een nieuw scherm. Klik bovenin op *URL* en voer in het eerste tekstvakje het volgende in: *croketephji/pikwadraat*<br>Bevestig door op de blauwe knop met *Clone* te klikken. Het programma downloadt nu een lokale kopie van de website. Dat kan een paar minuten duren.<img src="/assets/documentatie/github-desktop-clone-repo.png" alt="GitHub Desktop First Launch" class="cover">
4. Je hebt al heel wat stappen doorlopen. Gelukkig moet de installatie maar één keer!<br>Wanneer het downloaden voltooid is, krijg je het volgende scherm te zien. Klik op de blauwe link *Open this repository* om de lokale kopie van de website te gaan verkennen.<img src="/assets/documentatie/github-desktop-open-repo.png" alt="GitHub Desktop First Launch" class="cover">
5. Er opent zich nu een map op je computer. Alle bestanden in deze map vormen samen onze website. Afhankelijk van wat voor computer je gebruikt, zal het volgende scherm er een beetje anders uitzien, maar je zal al dezelfde bestanden en mappen zien. De mappen die voor jou interessant zijn, zijn gemarkeerd. <img src="/assets/documentatie/mappen.png" alt="GitHub Desktop First Launch" class="cover">Ga gerust eens kijken. Er kan niets kapot gaan aangezien je op de lokale versie werkt. 
  - **_kunstenaars**: Elk bestandje in deze map stelt een kunstenaar voor. De site gebruikt de informatie over elke kunstenaar om pagina's op te bouwen. Er zijn twee versie van elke kunstenaar: een in het Nederlands en een in het Engels. Zie [*Kunstenaar toevoegen*](/documentatie/nieuwe-kunstenaar.html).
  - **_exposities**: Analoog aan _kunstenaars. Zie [*Expositie toevoegen*](/documentatie/nieuwe-expositie.html).
  - **_werken**: Analoog aan _kunstenaars en _exposities. Let op dat een werk enkel vindbaar zal zijn op de site als de maker ervan vertegenwoordigd is met bestand in de map _kunstenaars. Zie [*Werk toevoegen*](/documentatie/nieuw-werk.html).
  - **assets/werken**: Hier staat een foto voor elk werk. De bestandsnamen van de foto's hebben hetzelfde formaat als de werken in de map _werken, maar zonder de taalcode *_nl* of *_en*. Zie [*Foto toevoegen*](/documentatie/nieuwe-foto.html).