# KUÇI-COIFFEUR — Cloudflare Pages

## Publikimi i faqes së re
1. Hyr në https://dash.cloudflare.com/ dhe zgjidh **Workers & Pages**.
2. Zgjidh **Create** → **Pages** → **Upload assets** (mund të shfaqet si Direct Upload).
3. Emërto projektin, p.sh. `kuci-coiffeur`.
4. Ngarko përmbajtjen e këtij ZIP-i (shpaketoje më parë; ngarko `index.html` dhe `_headers`, jo ZIP-in si skedar të faqes).
5. Shtyp **Deploy site**. Cloudflare do të japë adresë `*.pages.dev`.

## Çfarë punon në këtë version
- Dizajn responsive premium zi/ari.
- Shërbimet dhe çmimet: prerje 4 €, mjekër 1 €, stilim 7 €, paketë prerje + mjekër 5 €.
- Formulari krijon kërkesën dhe hap WhatsApp me tekstin e plotësuar në `+383 49 880 789`. Përdoruesi duhet ta dërgojë mesazhin dhe salloni duhet ta konfirmojë termin.

## Para publikimit
Kontrollo çmimet, orarin dhe fotografitë. Fotot janë imazhe të jashtme nga Unsplash dhe kërkojnë internet.

## E rëndësishme: administrimi dhe pagesat
Ky është version statik; **nuk përfshin ende panel privat real, ruajtje rezervimesh në databazë ose pagesa online**. Për panel privat duhet Cloudflare Worker + D1 (ose databazë tjetër), autentikim server-side dhe kontrolle aksesi. Për pagesa online duhet ofrues pagesash që mbështet biznesin tënd. Mos vendos fjalëkalime/API keys në `index.html`.
