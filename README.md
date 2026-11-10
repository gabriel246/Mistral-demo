# Mistral-demo
## Browser-Demos (kein Installieren, direkt im Browser)

Vier eigenständige HTML-Dateien — reines HTML/CSS/JS, keine Abhängigkeiten, laufen offline per Doppelklick (`file://`) und über GitHub Pages.

| Datei | Inhalt | Steuerung |
|---|---|---|
| `index.html` | Übersicht | — |
| `shader.html` | Echtzeit-Raymarching (WebGL): leuchtender Knoten in Neon-Nebel | Maus = Kamera |
| `particles.html` | Particle Life: 1.400 Partikel, emergente Strukturen | Klick = Impuls, `R` = neues Regel-Set, `+`/`-` = Arten, Leertaste = Pause |
| `audio.html` | Generativer Synth-Track (Web Audio API) + radiales Spektrum mit Beat-Pulsen | Play, 3 Tracks, optional Mikrofon (https/localhost) |
| `brain.html` | Neuronales Netz trainiert live sichtbar (Entscheidungsgrenze + Genauigkeit) | Datensatz wählen, Netz neu starten |

Fürs Video: Datei öffnen, **F11** für Vollbild. `brain.html` braucht ca. 5–10 s, bis die Genauigkeit sichtbar steigt. `audio.html` startet nach Klick auf **Play** (Autoplay-Regel).

Lokal hosten: `python3 -m http.server 8000` → `http://localhost:8000/`
