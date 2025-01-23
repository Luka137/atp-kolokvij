# ATP Kolokvij
## Kratki opis projekta
Dalí je u povijesti zapamćen po svojim snažnim i bizarnim slikama te kao jedan od najpoznatijih predstavnika nadrealizma u slikarstvu, a mnogi stručnjaci smatraju da su na njegov stil utjecali renesansni majstori. Među njegovim opusom najpoznatija je slika Postojanost pamćenja (Mekani satovi) dovršena 1931. koja je, osim po svojoj umjetničkoj vrijednosti, poznata po tome što je korištena u mnogim igranim i animiranim filmovima.
![Slika](https://github.com/Luka137/atp-kolokvij/blob/main/slika.jpg)
```const isProd = process.env.NODE_ENV === 'production'
let manifest

if(isProd) {
  try {
    manifest = require('../dist/.vite/manifest.json')
  } catch (e) {
    throw new Error(`Vite manifest.json not found. Have you run 'yarn run build'?`)
  }
}```
