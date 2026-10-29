# CLAUDE.md — projectwerkwijze

Algemene voorkeuren (taal, uitleg, backups, codecommentaar) staan in de
globale `~/.claude/CLAUDE.md`. Dit bestand regelt alleen de projectbestanden
en git. Projectspecifieke regels komen onderaan onder `## Project-specifiek`.

@PROJECT.md
@LESSONS.md

## Projectbestanden
- `PROJECT.md` = de WHAT (doel, scope, data/flow). Ontstaat door erover te
  sparren, niet door een sjabloon in te vullen. Claude past het alleen aan
  na akkoord; merkt Claude dat scope of aannames veranderen, meld dat.
- `Log.md` = status per sessie, nieuwste bovenaan. Alleen Claude bewerkt het.
  Lees bij de start de bovenste entry.
- `LESSONS.md` = regels uit fouten die echt zijn opgetreden, niet vooraf
  verzonnen. Alleen Claude bewerkt het.
- Is iets in deze bestanden achterhaald: pas de tekst ter plekke aan, voeg
  geen tegenstrijdige regel toe.

## Na elke afgeronde taak
1. `Log.md` bijwerken: wat gedaan (met bestandsnamen), wat open, volgende stap.
   Zelfde datum = dezelfde entry aanvullen.
2. Ging er iets echt mis dat het onthouden waard is → regel in `LESSONS.md`.
3. Commit (klein, zegt wat en waarom) en push.

Doe dit na de taak, niet "aan het eind van de sessie": Claude merkt niet
wanneer de sessie sluit.

## Version control (GitHub)
- Repo: [URL invullen per project]
- `git pull` bij sessiestart gebeurt automatisch (globale hook).
- Direct naar `main` is prima zolang ik de enige ben die commit.

## Project-specifiek
*(nog niets)*
