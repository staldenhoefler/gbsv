# Minichallenge Grundlagen Bild- und Signalverabeitung

In dieser Mini-Challenge werden LE1, LE2, LE3 und LE4 von gbsv geprüft. In Data Science und Machine Learning werden oft Merkmale (Features) von Bildern und Signalen generiert, um basierend darauf zu analysieren oder zu lernen. Diesem Thema widmen wir uns mittels klassischer Signal- und Bildverarbeitung.

Jede:r Studierende:r hat eine individualisierte Aufgabenstellung. Die Abgabe soll ebenfalls einzigartig sein. 

Dazu wird in dieser Mini-Challenge ein Steckbrief über ein Land in Form von Experimenten in Bild- und Signalverarbeitung zusammengestellt. Das heisst, du wählst passend zu deinem gewählten Land und den dir zugeordneten Aufgaben Bilder und Signale aus. Die Programmiersprache und die Code-Dokumentation darf frei gewählt werden. Sofern nicht anders erwähnt, dürfen vorhandene Bibliotheken verwendet werden. Gebe die Quellen deiner Daten und ggf. deines Codes an. Mit Diskutieren ist gemeint, das WAS WIE WARUM zu erläutern. 

Checkpoints:
- Reviewe deine ausgewählten Daten. 
- Reviewe den Durchstich einer deiner Analysen/Aufgaben in LE1/LE2. 
- Reviewe den Durchstich einer deiner Analysen/Aufgaben in LE3/LE4. 
- Die Reviews erfolgen mit der Fachexpertin in der Sprechstunde. Einschreibung via Calendly Link in Spaces.

Bewertung und PeerGrading:
- Abgabe LE1/LE2: Zwischennote zählt zur Hälfte. 
- PeerGrading LE1/LE2: Bewerte 3 Abgaben deiner Peers. 1 Woche Zeit.
- Abgabe LE3/LE4: Zwischennote zählt zur Hälfte.
- PeerGrading LE3/LE4: Bewerte 3 Abgaben deiner Peers. 1 Woche Zeit. 
- Termine siehe Spaces Kalender.

Abgaben:
- Anonymisierte Abgabe im Peer-Grading-Tool: Code inkl. Resultaten und Diskussionen (Python und HTML). Es können aktuell max. 100MB aufs Peer-Grading Tool geladen werden. 
- Abgabe an Fachexpertin: Code (Python und HTML) via Repository oder Shared Folder. Fehlende Abgaben geben 0.1 Noten Maluspunkte. 

Achtung: Gewissen Aufgabenstellungen sind offen gehalten. Setzt euch selbst einen Rahmen für die Beschränkung oder kommt in die Sprechstunde, sofern euch die Grenzen nicht klar sind. Treffende Datenwahl, auf den Punkt gebrachte Kreativität, massvolle Vielfalt und kritisches Denken sind gesucht.

## Aufgabe 1 Bildeigenschaften
### 1.1 Bildeigenschaften
### 1.1. Bildeigenschaften
Suche 1-3 Bilder passend zu deinem Land oder nehme selbst welche auf. Die Bilder sollen sich eignen, um Anpassungen der Bildeigenschaften {'Kontrast, Farbsättigung'} in Experimenten zu demonstrieren. Definiere pro zugeordneter Eigenschaft ein Ziel, das du verändern möchtest und 1-2 Experimente wie du das Ziel erreichen möchtest. In einem Experiment dürfen auch mehrere der Ziele gleichzeitig analysiert werden. Führe die Experimente mit deinen Bildern und geeigneten Methoden aus. Messe deine Ergebnisse mittels geeigneten Methoden. Analysiere die Histogramme der ursprünglichen Bilder und falls sinnvoll während deinen Experimenten.  Argumentiere deine Parameter- und Methodenwahl jeweils mittels Grafiken oder jeweils in 1-2 Sätzen. Diskutiere deine Erkenntnisse und Resultate in ca. 150 Wörtern.
### 1.2. Signaleigenschaften
Suche 1-3 Signale passend zu deinem Land oder nehme selbst welche auf. Die Signale sollen sich eignen, um Anpassungen der Signaleigenschaften {'Amplitude, Phase'} in Experimenten zu demonstrieren. Definiere pro zugeordneter Eigenschaft ein Ziel, das du verändern möchtest und 1-2 Experimente wie du das Ziel erreichen möchtest. In einem Experiment dürfen auch mehrere der Ziele gleichzeitig analysiert werden. Führe die Experimente mit deinen Signalen und geeigneten Methoden aus. Messe deine Ergebnisse mittels geeigneten Methoden. Argumentiere deine Parameter- und Methodenwahl jeweils mittels Grafiken oder jeweils in 1-2 Sätzen. Diskutiere deine Erkenntnisse und Resultate in ca. 150 Wörtern.
### 1.3. Nyquist Theorem
Demonstriere mit einem deiner Signale das Nyquist Theorem. Insbesondere interessieren mich da die Übergange der minimal benötigen Frequenz im Vergleich zu ungenügende Informationen. Diskutiere deine Daten-, Parameter- und Methodenwahl und die erzielten Ergebnisse in ca. 150 Wörtern. 
## 2. Faltung/Filterung in Bild und Signal (LE2)
### 2.1. Filterung in der räumlichen Domäne
Implementiere selbst einen klassischen Algorithmus zur Filterung entweder von Signalen (1D) oder Bildern (2D) in der räumlichen Domäne (Faltung/Convolution). Welche Elemente soll ein solcher Algorithmus enthalten? Teste deine Funktion mit jeweils einem Signal oder einem Bild passend zu deinem Land und Faltungskernels in geeigneter Grösse. Die Faltungskernel sollen das Signal bzw. Bild {'weichzeichnen, schärfen'}. Messe die Unterschiede deiner Daten vor und nach dem Filtern mittels einer quantitativen Methode. Diskutiere deine Daten-, Methoden- und Parameterwahl sowie die erzielten Ergebnisse in ca. 150 Wörtern. Weshalb hast du diese Faltungskernel bzw. diese quantitative Methoden gewählt? 
### 2.2. Filterung in der spektralen Domäne
Implementiere eine Methode basierend auf spektraler Filterung, welche ein repetitives Muster entweder aus einem Signal oder einem Bild filtert. Demonstriere das Resultat entweder anhand eines Signales oder eines Bildes passend zu deinem Land. Diskutiere deine Daten-, Methoden- und Parameterwahl sowie die erzielten Ergebnisse in ca. 150 Wörtern. 
### 2.3. Bonus: Filterung in der räumlichen und spektralen Domäne
Führe optional Experimente mit Signalen oder Bildern mit Methoden durch, welche das Filtern in der räumlichen und der spektralen Domäne ermöglichen. Z.B. mittels Wavelets. Diskutiere deine Daten-, Parameter- und Methodenwahl und die erzielten Ergebnisse in ca. 150 Wörtern.Bei erfolgreichem Lösen dieser optionalen Aufgabe gibt es 0.1 Notenpunkte Bonus. 
### 2.4. Algorithmen zur Erkennung von Strukturen in Bildern
Zeige die einzelnen Schritte eines bekannten klassischen Bildverarbeitungs-Algorithmus zur Detektion von {'Ecken'} in einem geeigneten Beispielbild deines Landes. Die einzelnen Schritte können selbst programmiert sein oder von Bibliotheken verwendet werden. Wichtig ist, dass Zwischenergebnisse der Schritte ersichtlich sind. Beschreibe zudem, was in jedem einzelnen Schritt konzeptionell relevant ist. Diskutiere deine Daten-, Methoden- und Parameterwahl sowie die erzielten Ergebnisse in ca. 150 Wörtern. Für welche Fälle funktioniert dein Algorithmus gut bzw. schlecht? Warum hast du dieses Bild gewählt?
## 3. Mustersuche in Bild und Signal (LE3)
### 3.1. Korrelation in Signalen
Suche 1 1D Signal, welches wiederkehrende Muster enthält. Analyisere dann mittels Auto-Korrelation die wiederkehrenden Muster innerhalb deines 1D Signals. Kann die Periodizität deines Musters via Auto-Korrelogramm sichtbar gemacht werden? Diskutiere deine Methoden- und Parameterwahl sowie die Resultate in ca. 150 Wörtern. 
Schneide nun ein Stück deines Signals aus und versuche es via Kreuzkorrelation im Ursprungssignal zu finden. Woran erkennst du, dass die Stelle passt? Beschreibe in 1-2 Sätzen. Verändere nun dein ausgeschnittenes Stück etwas und schaue, ob es immer noch via Kreuzkorrelation gefunden werden kann. Welche Arten von Veränderungen werden toleriert? Welche nicht? Diskutiere die Resultate in ca. 150 Wörtern. 
### 3.2. Segmentierung, morphologische Operationen, Objekteigenschaften in Bildern
Suche 1 Bild, welches mehrere ähnliche Objekte enthält. Diese Objekte sollen mittels geeigneter Methoden segmentiert werden. Die Resultate sollen als gelabelte Bilder (binär oder pro Klasse 1 Label) gespeichert werden. Zeige dabei, wie du die Labelmasken mittels morphologischer Operationen verbessert hast. Erkläre hier für jede angewendete Operation in 1-2 Sätzen, warum du diese Operation anwendest. Zeige auch in Einzelbildern die Zwischenresultate deiner angewendeten Operationen und dass du nur minimal die Objekte verändert hast (z.B. keine Verschiebungen, Verkleinerungen oder Vergrösserungen). Extrahiere am Ende deine einzelnen Objekte, zähle und vermesse 2-3 Eigenschaften deiner extrahierten Objekte mittels geeigneten Methoden. Erkläre pro Eigenschaft in 1-2 Sätzen, warum du diese gewählt hast und ob die Resultate brauchbar sind.  

Erstelle dann ein möglichst minimales aber repräsentatives Skeleton eines deiner Objekte und gebe die Anzahl Pixel des Skeletons aus. 

Diskutiere deine Erkenntnisse und Resultate in ca. 150 Wörtern. 
  
Weiterführende Links: \
skimage: Label image regions \
skimage: Segment human cells (in mitosis)\
skimage: Measure region properties\
## 4. Feature Deskriptoren in Bildern (LE4)
4.1. Keypoint Matching
Suche ein paar Bilder mit dem gleichen Sujet/Objekt aus, welche das Objekt von unterschiedlichen Blickwinkeln, aus anderer Perspektive, aus unterschiedlicher Distanz oder rotiert zeigen. Wende dann den dir zugeordneten Keypoint Deskriptor {'ORB'} an, um mindestens zwei deiner Bilder via Keypoints zu "matchen". Wähle dafür geeignete Parameter und eine geeignete Anzahl Keypoints. Erläuere deine Entscheidungen in 1-2 Sätzen. Zeige deine Resultate visuell und stelle 2-3 Beobachtungen auf. 
Diskutiere in ca. 150 Wörtern wie robust der dir zugeordnete Algorithms {'ORB'} ist in Bezug auf Transformationen oder unterschiedlicher Aufnahmeverhältnisse (Licht, ...) und dessen rechnerische Effizienz. Zeige mindestens eine dieser Eigenschaften anhand deiner Beispieldaten. Diskutiere die Resultate und Erkenntnisse in 2-3 Sätzen.
## 5. Peer-Grading
Die Mini-Challenge Abgaben werden in zwei Teilen bewertet. In jedem Teil findet eine Bewertung via Peer-Grading statt. Die Zuordnung erfolgt via FHNW Peer-Grading-Tool. Orientiere dich für die Bewertung an den vorgegebenen Bewertungskriterien (siehe Excel-Datei oder Peer-Grading-Tool). Die Note 5 bedeutet, dass alles erfüllt ist, wie du es von einem guten Data Scientist in der Praxis erwarten würdest. Du startest als Baseline mit der Note 5. Entdeckst du Fehler, geht die Note nach unten. Der Note 5.5 nähert man sich, wenn die Erwartungen übertroffen wurden. Der Note 6 nähert man sich, wenn die Leistung ausserordentlich ist und kritisches Denken, Variabilität, eigene Ideen und Kreativität beinhaltet. Siehe Checkliste für Bewertung. Die Benotung soll auf Zehntel gerundet sein. Wer auf Zehntel gerundet mit 0.1 Abweichung die Endnote von der Fachexpertin trifft, kriegt einen Bonus von 0.1 Noten für die eigene Abgabe. 

Weiterführende Links:\
FHNW Peer-Grading-Tool

