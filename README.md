# ATP Kolokvij
## Kratki opis projekta
Dalí je u povijesti zapamćen po svojim snažnim i bizarnim slikama te kao jedan od najpoznatijih predstavnika nadrealizma u slikarstvu, a mnogi stručnjaci smatraju da su na njegov stil utjecali renesansni majstori. Među njegovim opusom najpoznatija je slika Postojanost pamćenja (Mekani satovi) dovršena 1931. koja je, osim po svojoj umjetničkoj vrijednosti, poznata po tome što je korištena u mnogim igranim i animiranim filmovima.
![Slika](https://github.com/Luka137/atp-kolokvij/blob/main/slika.jpg)
### Linkovi
[Wikipedija](https://hr.wikipedia.org/wiki/Glavna_stranica)
[Pexels](https://www.pexels.com/search/ronaldo/)
[Gists](https://gist.github.com/discover)

1. Dodavanje H1
2. Dodavanje H2
3. Dodavanje teksta
4. Dodavanje slike
- Dodavanje koda
- Dodavanje linkova
- Dodavanje numeriranih popisa
- Dodavanje ne-numeriranih popisa

### Informacije o projektu

| Naziv projekta   | ATP Kolokvij      |
|------------------|-------------------|
| Pokušaj          | 1.                |
| Student          | Luka Gobin        |
| Datum            | 23.1.2025.        |

[LICENSE](https://github.com/Luka137/atp-kolokvij/blob/main/LICENSE.md)

### Check lista
- [x] Kreirati GitHub repozitorij nazvan atp-kolokvij
- [x] Dodati naslov projekta (H1)
- [x] Dodati kratki opis projekta (H2) – preuzeti tekst s Wikipedije
- [x] Dodati sliku – preuzeti s Unsplash ili Pexels
- [x] Dodati primjer koda – preuzeti s Gists
- [x] Dodati link na izvor slike i teksta
- [x] Linkati README.md i LICENSE.md (obostrano)
- [x] Napraviti popis (numerički i ne-numerički)
- [x] Izraditi kratku tablicu s informacijama o projektu
- [ ] Napraviti commit promjena s odgovarajućom porukom
- [ ] Otvoriti pull request unutar vlastitog repozitorija
- [x] Dodati LICENSE.md datoteku s MIT licencom
- [x] Aktivirati GitHub Pages za repozitorij

```const isProd = process.env.NODE_ENV === 'production'
let manifest

if(isProd) {
  try {
    manifest = require('../dist/.vite/manifest.json')
  } catch (e) {
    throw new Error(`Vite manifest.json not found. Have you run 'yarn run build'?`)
  }
}
