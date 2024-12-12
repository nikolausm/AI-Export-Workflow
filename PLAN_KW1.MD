# Woche 1 – Detaillierter Tagesplan

**Ziel der Woche:**  
Eine solide theoretische ML-Basis schaffen, grundlegende ML-Konzepte verstehen (Lineare Regression, Overfitting, Train/Test-Split) und ein erstes einfaches ML-Modell mit ML.NET umsetzen. Abschließend sollen Metriken (MSE, MAE) berechnet und dokumentiert werden.

## Überblick der Woche

- **Theorie (ML-Konzepte):** Lineare Regression verstehen, Problem von Overfitting erkennen, Train/Test-Split einsetzen.
- **Online-Kurs (Coursera):** „Machine Learning Fundamentals“ Kapitel 1–3 durcharbeiten (ca. 3 Std.).
- **Praxis (ML.NET):** Ein einfaches lineares Regressionsmodell zur Vorhersage von Hauspreisen umsetzen.
- **Dokumentation:** Berechnete Metriken (MSE, MAE) notieren, README aktualisieren.

## Täglicher Ablauf

### Montag (Tag 1)

**Ziele für den Tag:**  
- Grundlegendes Verständnis der linearen Regression, Overfitting und Train/Test-Split erlangen.  
- Einführung in den Online-Kurs und erste Lektionen anschauen.

**Aufgaben & Zeitplan:**
- **Vormittag (ca. 2 Std.):**  
  - Theoretische Grundlagen erarbeiten:  
    - Lineare Regression: Was ist das Modell, welche Annahmen gibt es?  
    - Overfitting: Begriff verstehen, Beispiel überlegen (Modell passt zu stark auf Trainingsdaten).  
    - Train/Test-Split: Warum Daten aufteilen, wie Verhältnis wählen (z. B. 80/20)?
  - Notizen in einem lokalen Notizbuch oder Wiki festhalten.

- **Nachmittag (ca. 1–1,5 Std.):**  
  - Coursera-Kurs „Machine Learning Fundamentals“: Kapitel 1 anschauen.  
    - Fokus: Grundbegriffe ML, Unterschied überwacht/unüberwacht lernen.  
  - Kurze Zusammenfassung des Gelernten notieren (Stichpunkte).

### Dienstag (Tag 2)

**Ziele für den Tag:**  
- Online-Kurs weiter vorantreiben, Kapitel 2 und 3 abschließen.  
- Theoretisches Verständnis vertiefen und in Praxisbezug setzen.

**Aufgaben & Zeitplan:**
- **Vormittag (1–1,5 Std.):**  
  - Coursera-Kurs Kapitel 2 durchgehen: Schwerpunkte könnten z. B. einfache lineare Regression, Kostenfunktionen und Gradientenabstieg sein.
  - Notizen: Wichtige Formeln (MSE) und Vorgehen beim Training vermerken.

- **Nachmittag (1–1,5 Std.):**  
  - Coursera-Kurs Kapitel 3 abschließen: Train/Test-Split, Evaluationsmetriken (MSE, MAE) theoretisch verstehen.
  - Zusammenfassung der Kursinhalte bis Kapitel 3 erstellen: Kurze PDF/Markdown-Notiz „ML Basics“.
  - Überlegen, wie diese Konzepte in ML.NET praktisch umgesetzt werden (erste Ideenskizze).

### Mittwoch (Tag 3)

**Ziele für den Tag:**  
- Praktischen Einstieg in ML.NET finden.  
- Projektgrundlage schaffen (C#-Konsolen-App, ML.NET-NuGet einbinden).

**Aufgaben & Zeitplan:**
- **Vormittag (2 Std.):**  
  - Neues C#-Konsolenprojekt anlegen (z. B. „HousePricePrediction“).  
  - ML.NET NuGet-Pakete installieren.  
  - Datensatz (z. B. CSV mit Hauspreisen und Features wie Anzahl Zimmer, Wohnfläche) vorbereiten.

- **Nachmittag (2 Std.):**  
  - Erste ML.NET-Pipeline schreiben:  
    - Daten laden.  
    - Features und Label definieren.  
    - Einfaches lineares Regressionsmodell trainieren.  
  - Code nach DRY und SOLID Prinzipien strukturieren (DataLoader-Klasse, ModelTrainer-Klasse).  
  - Erste Trainingsläufe starten, Ergebnisse prüfen.

### Donnerstag (Tag 4)

**Ziele für den Tag:**  
- Metriken berechnen (MSE, MAE) und Ergebnisse dokumentieren.  
- Codequalität sichern.

**Aufgaben & Zeitplan:**
- **Vormittag (1–2 Std.):**  
  - Evaluationscode schreiben: MSE und MAE berechnen (ML.NET bietet entsprechende Funktionen).  
  - Ergebniswerte in der Konsole ausgeben lassen.

- **Nachmittag (1–1,5 Std.):**  
  - README-Datei im GitHub-Repo aktualisieren:  
    - Kurze Erklärung des Projekts.  
    - Kurzanleitung zum Starten (Kommandos, Dependencies).  
    - Ergebnisse (MSE, MAE) eintragen.  
  - Kurzer Code-Review: Variablen- und Methodennamen anpassen, Übersichtlichkeit erhöhen.

### Freitag (Tag 5)

**Ziele für den Tag:**  
- Rückblick auf die Woche, Gelerntes festhalten.  
- Vorbereitung für nächste Woche.

**Aufgaben & Zeitplan:**
- **Vormittag (1 Std.):**  
  - Kurze schriftliche Reflexion (Markdown-Notiz):  
    - Was habe ich diese Woche gelernt? (z. B. Grundprinzipien der linearen Regression, wie Overfitting vermieden werden kann, wie man ML.NET einsetzt.)  
    - Wo gibt es noch Verständnislücken? (Notieren, um nächste Woche zu vertiefen.)
  
- **Nachmittag (optional, 0,5–1 Std.):**  
  - Optional: Kleine Experimente mit anderen Features im Hauspreisdatensatz, um Overfitting zu beobachten (z. B. Test: Mehr Features hinzufügen, Vergleich der Metriken auf Train und Test Set).
  - Plan für Woche 2 grob sichten (z. B. tiefer in PyTorch/TensorFlow einsteigen).

### Samstag & Sonntag (Tag 6–7) (Optional)

**Ziele:**  
- Freiraum für Wiederholung und Vertiefung.  
- Kein zwingender Terminplan, aber mögliche Aktivitäten:
  
**Aufgaben (freiwillig):**  
- Wiederholung der Kursinhalte: Nochmalige Durchsicht von Kapitelzusammenfassungen.  
- Lesen von ML-Artikeln (z. B. Medium-Artikel zu Overfitting und Regularisierung).  
- Keine Pflichtaufgaben, Erholung und Vorbereitung auf die nächste Woche.

---

**Endergebnis Woche 1:**  
- Theoretisches Verständnis: Grundlagen ML, lineare Regression, Overfitting, Train/Test-Split verinnerlicht.  
- Coursera-Kurs Kapitel 1–3 abgeschlossen.  
- Einfaches ML.NET-Projekt zur Hauspreisvorhersage erstellt, MSE & MAE berechnet.  
- Ergebnisse in README dokumentiert, Code nach SOLID und DRY Prinzipien strukturiert.
