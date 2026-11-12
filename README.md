# Thema für den Orbit-Sprint einreichen

Vor jedem Customer Sprint mit Orbit reicht ihr die Themen ein, die euch im Alltag mit Orbit Zeit kosten, am besten kleine Verbesserungen, die in einem Sprint machbar sind. Orbit bringt zum Sprint-Meeting je Thema einen Lösungsvorschlag mit, und im Meeting wählen wir gemeinsam aus, was in den Sprint kommt. Eingereicht wird über ein kurzes Formular, bis 48 Stunden vor dem Meeting, ein Thema je Formular.

Dieser Skill hilft euch, ein Thema mit dem KI-Assistenten eurer Wahl in wenigen Minuten sauber zu formulieren. Er fragt nach Situation, Häufigkeit, Kosten und woran ihr erkennt, dass es gelöst ist. Am Ende gibt er die Felder des Formulars fertig zum Kopieren aus. Er sagt nichts darüber, ob oder wann ein Thema umgesetzt wird. Das klären wir gemeinsam im Meeting. Screenshots, Beispieldaten oder eigene Ausarbeitungen könnt ihr im Formular unter "Anhänge" hochladen.

## Installation

**Claude Code:** Kopiert diesen Ordner nach `~/.claude/skills/orbit-sprint-thema/`, dann steht der Skill in allen Projekten bereit. Für nur ein Projekt kopiert ihr ihn nach `.claude/skills/orbit-sprint-thema/` in diesem Projekt.

```bash
git clone https://github.com/orbit-logistics/customer-sprint ~/.claude/skills/orbit-sprint-thema
```

Danach reicht ein Satz wie "Ich will ein Thema für den Orbit-Sprint einreichen".

**claude.ai:** Legt ein Projekt an, zum Beispiel "Orbit-Sprint", und fügt den Inhalt von `SKILL.md` als Projekt-Anweisung ein. Jeder neue Chat in diesem Projekt startet dann mit dem Skill.

**Andere Assistenten:** Fügt den Inhalt von `SKILL.md` als erste Nachricht in einen neuen Chat ein und erzählt danach euer Thema.

## Formular

Jeder Kunde hat sein eigenes Formular "Thema für den nächsten Sprint". Den Link bekommt ihr von Orbit, er steht in jedem Sprint-Post in eurem Orbit-Kanal.
