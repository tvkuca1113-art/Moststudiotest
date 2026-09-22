# MOST Studio — testni dizajn

Zasebna testna stranica odabranog tamnozelenog dizajna s kamenim lukom. Izrađena za vizuelnu provjeru na desktopu i mobitelu.

**Ovaj projekt ne mijenja `Moststudioba` niti `moststudioba.com`.**

## Pokretanje

```sh
npm ci
npm run dev
```

## Produkcijska izrada

```sh
npm run build
npm run test:sites
```

Vercel: importovati isključivo repozitorij `tvkuca1113-art/Moststudiotest`. Postavke su u `vercel.json`: Vite, `npm run build`, izlaz `dist/client`. Ne povezivati postojeću produkcijsku domenu.

## Obuhvat

- Responzivna početna stranica s pravim HTML tekstom i navigacijom.
- Optimizovan odabrani vizual; lokalne licencirane Inter i Playfair font datoteke.
- Bosanski / njemački prikaz, mobilni meni, prikazi projekata i otvaranje detalja.
- Proširive usluge i priprema / kopiranje upita, bez automatskog slanja.
- Dugme za postojeći demo otvara originalnu demonstraciju u zasebnom tabu; originalni sadržaj se ne mijenja.
- `noindex, nofollow` i robots zabrana za ovu testnu verziju.

Ovo je test izgleda, ne zamjena kompletnog produkcijskog sajta. Izvorni koncept sadrži rasterizovan scenski vizual; naslov i navigacija su stvarni elementi. Generated assets may contain small illustrative text within the scene.
