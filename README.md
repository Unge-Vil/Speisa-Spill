🚀 Speisa Spill - Unge Vil

Velkommen til Speisa Spill! Dette er en spillportal laget av og for Unge Vil, fylt med kule spill og prosjekter vi har kodet sammen med kunstig intelligens (Gemini).

Nettsiden har et gjennomført verdensrom-tema ("speisa") og fungerer som en landingsside som lenker videre til alle de ulike spillene våre.

🎮 Om prosjektet

Teknologi: HTML, JavaScript og Tailwind CSS.

Design: Responsivt, futuristisk sci-fi design med neoneffekter og stjerneanimasjoner.

Hosting: Designet for å kjøre direkte på GitHub Pages.

🛠️ Hvordan legge til et nytt spill

Alt styres fra én fil: index.html. Du trenger ikke kunne mye koding for å legge til et nytt spill i listen!

Lag en ny mappe i repoet for spillet ditt (f.eks. /snake/) og legg spillets filer der.

Åpne index.html.

Scroll ned til bunnen av filen til du finner const spillListe.

Kopier en av blokkene (mellom { og }), lim den inn, og endre informasjonen:

{
    "id": 99,
    "tittel": "Navnet på Spillet",
    "beskrivelse": "Kort tekst om hva spillet går ut på.",
    "url": "/mappenavn/",  // F.eks. "/snake/" eller "[https://ekstern-lenke.no](https://ekstern-lenke.no)"
    "ikon": "fa-solid fa-gamepad", // Finn ikoner på fontawesome.com
    "farge": "bg-gradient-to-br from-purple-900 to-black" // Velg farge
}


🌍 Hvordan publisere (GitHub Pages)

Gå til Settings i dette repositoryet på GitHub.

Klikk på Pages i menyen til venstre.

Under Build and deployment -> Branch, velg main (eller master) og mappen / (root).

Klikk Save.

Vent et par minutter, så får du en lenke til din levende nettside!

📦 Mappestruktur

Slik ser det ryddigst ut:

/ (rot)
├── index.html       (Selve portalen)
├── README.md        (Denne filen)
├── /snake/          (Mappe for Snake-spillet)
│   ├── index.html
│   └── script.js
├── /gjett-tallet/   (Mappe for Gjett Tallet)
│   └── index.html
└── ...


Laget med ❤️ og 🤖 i Unge Vil.
