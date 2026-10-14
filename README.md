# Prší Bank

Počítadlo lebek a banku pro karetní hru prší. Běží celé v prohlížeči, bez serveru a bez registrace.

- Každý hráč vkládá vklad do banku (výchozí 100 Kč). Za prohranou hru dostane lebku ☠️, po třetí je OUT a vklad mu propadá.
- Poslední hráč bere celý bank. Poslední dva (nebo polovina hráčů se stejným skóre) si ho mohou rozdělit v libovolném poměru.
- Na konci večera aplikace spočítá, kdo komu kolik pošle, a ukáže QR Platbu pro českou bankovní aplikaci.
- Fotky hráčů s automatickým zaměřením obličeje, týmové barvy, uložené party (max. 5) a databáze hráčů.
- Čísla účtů jde načíst z QR kódu platby, který si hráč vygeneruje ve své bance.

## Data

Vše se ukládá jen v prohlížeči daného zařízení (localStorage). Nic se nikam neodesílá.

## Instalace na iPhone

1. Otevřete adresu aplikace v Safari.
2. Klepněte na Sdílet → Přidat na plochu.
3. Aplikace se spouští z ikony na celou obrazovku a funguje i offline.

## Licence

MIT
