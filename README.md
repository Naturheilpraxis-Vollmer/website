
Für eine lokale Vorschau HUGO installieren.

Unter `content` nur Ordner und keine Dateien anlegen &ndash; besonders nicht `index.*`.

In `content`-Dateien nicht `# Überschrift` verwenden, da diese bereits automatisch generiert wird.

Die Sichtbarkeit von Seiten kann durch `draft = true` (privat) bzw. `draft = false` (öffentlich) im Kopfelement von `content`-Dateien gesteuert werden.

Shortcodes (im Ordner `/layouts/shortcodes`) können via `{{< NAME >}}` genutzt werden (wichtig: kein Platz zwischen `{{<` und `>}}`).

Als Ordnernamen nur `a-z`, `A-Z`, `0-9` und `-` verwenden -- kein `äöüß`.

Bilder: z.B. im Ordner neben `index.md` speichern, dann im Text einfügen mit `![Beschreibung](name.jpg)` bzw. der jeweiligen Dateinamenerweiterung.

Weitere Hilfe unter https://gohugo.io/documentation/ und https://www.markdownguide.org/cheat-sheet/
