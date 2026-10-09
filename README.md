# Den bez hříchů

Jednoduchá instalovatelná PWA v češtině pro počítání času bez zlozvyku.

## Funkce
- Počítá dny, hodiny, minuty a sekundy od spuštění.
- Název cíle lze změnit (např. „Bez sladkostí“).
- Postava a motivační text se mění podle délky série: méně než 15 dní, 15–29 dní, 30 a více dní.
- Čas a cíl se ukládají do localStorage v daném zařízení.
- Service worker ukládá aplikaci pro offline použití.

## Spuštění přes GitHub Pages
1. Otevři **Settings → Pages**.
2. Jako zdroj vyber **Deploy from a branch**.
3. Vyber větev **main** a složku **/(root)** a potvrď **Save**.
4. Po zveřejnění bude aplikace na adrese `https://kockagejsa1.github.io/bez-hrichu/`.

Na Androidu otevři web v Chrome a použij nabídku **⋮ → Přidat na plochu** nebo **Instalovat aplikaci**.

## Poznámka
Časovač je založen na uloženém čase začátku, takže pokračuje i po zavření prohlížeče. Údaje se automaticky nesynchronizují mezi zařízeními. Resetování vyžaduje potvrzení.
