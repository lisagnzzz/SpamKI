# SpamKI – Interaktive Lernanwendung

## Starten
1. Lade `index.html` herunter.
2. Öffne die Datei per Doppelklick in einem aktuellen Browser.
3. Die Anwendung funktioniert ohne Installation und ohne Internetverbindung.

## Auf GitHub veröffentlichen (GitHub Pages)
1. Erstelle auf GitHub ein neues Repository, z. B. `spamki`.
2. Lade `index.html` in das Repository hoch.
3. Öffne im Repository **Settings → Pages**.
4. Wähle bei **Build and deployment** die Option **Deploy from a branch**.
5. Wähle den Branch `main` und den Ordner `/ (root)`, danach **Save**.
6. Nach kurzer Zeit wird eine öffentliche Webseite angezeigt. Der Link sieht ungefähr so aus:
   `https://DEIN-BENUTZERNAME.github.io/spamki/`

## Didaktische Idee
Die Lernenden geben Nachrichten ein, beobachten die Klassifikation, verändern die Gewichte typischer Merkmale und beantworten Verständnisfragen.

## Fachlicher Hinweis
Die Anwendung ist bewusst ein vereinfachtes didaktisches Modell: Sie verwendet gewichtete Merkmale und eine Schwellen-/Sigmoid-Berechnung. Sie ist kein trainiertes mehrschichtiges neuronales Netzwerk. Das wird in der Anwendung transparent erklärt.
