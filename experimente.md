<!--
author:   Herbert Schletter

email:    herbert.schletter@physik.tu-chemnitz.de

version:  0.0.1

language: de

narrator: Deutsch Male

comment:  Ergänzendes Lehrmaterial zu den Vorlesungsversuchen Experimentalphysik
          an der TU Chemnitz

link:     https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css

script:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js

-->

# Vorlesungsexperimente für die Experimentalphysik

*In den Vorlesungen des Instituts für Physik der TU Chemnitz*

**Dr. Herbert Schletter**

Technische Universität Chemnitz

## Hinweis zum Urheberrecht
[![Creative Commons Lizenzvertrag](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

Dieses Skriptum steht unter einer  [Creative Commons Namensnennung 4.0 International Lizenz](http://creativecommons.org/licenses/by/4.0/).

Ausgenommen hiervon sind Inhalte (insbesondere Abbildungen), die aus externen
Quellen übernommen wurden und dort unter einer anderslautenden Lizenz
veröffentlicht wurden. Derartige Inhalte sind im Skript stets mit einem eigenen
Lizenzhinweis versehen, der Vorrang vor der hier genannten Lizenz besitzt.

## Vorwort
Die Physik zielt als Naturwissenschaft darauf ab, die Eigenschaften der uns
umgebenden Dinge (die Physik spricht hier allgemein von Körpern) und deren
gegenseitige Wechselwirkungen zu beschreiben. Zur Erreichung dieses – zweifellos
sehr hoch gesteckten – Ziels haben sich zwei grundlegende Herangehensweisen
herausgebildet: die *Theoretische Physik* und die *Experimentalphysik*. Während
die theoretische Physik sich sehr stark am abstrakten Formalismus der Mathematik
orientiert und neue Erkenntnisse durch analytische oder numerische Berechnungen
gewinnt, bezieht die Experimentalphysik ihre Erkenntnisse aus den präzisen
Messungen und Beobachtungen der namensgebenden Experimente. Beide Disziplinen
der Physik stehen gleichberechtigt nebeneinander, ergänzen sich und bestätigen
sich gegenseitig.

An der Hochschule werden theoretische Physik und Experimentalphysik in jeweils
eigenen Lehrveranstaltungen unterrichtet. Dabei werden nicht nur die Ergebnisse,
sondern auch die Denk- und Arbeitsweisen beider Disziplinen vermittelt. In der
Experimentalphysik werden dafür häufig bereits in der Vorlesung Experimente
vorgeführt, die die zu vermittelnden Sachverhalte qualitativ oder auch
quantitativ zeigen. An vielen Hochschulen verfügen die Fachbereiche Physik daher
über einen Vorlesungsassistenten, dessen Aufgabe in der Vorbereitung (und
teilweise auch der Vorführung) der Vorlesungsexperimente liegt. Auch der
Autor dieser Versuchsbeschreibungen gehört zu dieser Gruppe.

Natürlich bieten Vorlesungen nur einen begrenzten zeitlichen Rahmen für die
Durchführung von Experimenten. Messergebnisse sind oftmals sehr schnell wieder
„verschwunden“, wenn der Versuch abgeschlossen ist und der Dozent wieder die
Vorlesung übernimmt. Auch bleibt in der Regel nicht die Zeit, um Berechnungen
vorzuführen, die vom Messwert zum eigentlichen Ergebnis führen. Der Verweis auf
die Übung ist an dieser Stelle nur ein schwacher Trost. Manche Versuche mit
großem „Knalleffekt“ bleiben den Studenten sicherlich eine Zeit lang im
Gedächtnis. Jedoch ist es keine Effekthascherei, auf die die
Vorlesungsexperimente abzielen und die meisten Versuche müssen ohne den
„großen Knall“ auskommen.

Die vorliegende Sammlung von Versuchsbeschreibungen soll bei der Sicherung der
Erkenntnisse aus den Vorlesungsexperimenten helfen. Neben der Beschreibung der
grundlegenden Fragestellung und der Durchführung bestimmter
Vorlesungsexperimente werden auch quantitative Ergebnisse einzelner
Durchführungen aufgenommen und die entsprechenden Auswertungen durchgeführt.

Der größte Teil der Vorlesungsexperimente entfällt auf die Bereiche der
klassischen Physik: Mechanik, Wärmelehre, Elektrizitätslehre, Optik. Für die
Gebiete der modernen Physik (Quantenphysik, Atomphysik, Festkörperphysik, …)
lassen sich nur wenige Experimente im Hörsaalmaßstab realisieren.

## Optik

![Kapiteltitelbild: Farbiger Bismutkristall](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d0/Bi-crystal-white-background.jpg/584px-Bi-crystal-white-background.jpg "[Quelle: [Bi-crystal.jpg](https://commons.wikimedia.org/wiki/File:Bi-crystal.jpg): [Alchemist-hp](https://commons.wikimedia.org/wiki/User:Alchemist-hp) ([www.pse-mendelejew.de](http://www.pse-mendelejew.de)) + [Richard Bartz](https://commons.wikimedia.org/wiki/User:Richard_Bartz); derivative work: [Matthias M.](https://commons.wikimedia.org/wiki/User:Matthias_M.), [Bi-crystal-white-background](https://commons.wikimedia.org/wiki/File:Bi-crystal-white-background.jpg), [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/legalcode) via Wikimedia Commons]")

### Bestimmung des Brechungsindexes
Die Phasengeschwindigkeit, mit der sich das Licht ausbreitet, ist abhängig vom
Medium, in dem diese Ausbreitung stattfindet. Im Vakuum beträgt sie

$$c_0 = 2{,}99792458\cdot 10^8~\frac{\mathrm m}{\mathrm s} \, ,$$

was allgemein als Lichtgeschwindigkeit, exakter als Vakuum-Lichtgeschwindigkeit
bezeichnet wird. In jedem stofflichen Medium ist die
Ausbreitungsgeschwindigkeit des Lichts kleiner, was durch den Brechungsindex
$n_\mathrm M$ dieses Mediums ausgedrückt wird:

$$c_\mathrm M = \frac{c_0}{n_\mathrm M} \lt c_0 \, .$$

Für das Vakuum (und in sehr guter Näherung auch für Luft) gilt
$n_\mathrm{Luft} \approx n_\mathrm{Vakuum} = 1 \, .$ Alle anderen Medien
besitzen Brechungsindizes $n_\mathrm M \gt 1$.

Zur experimentellen Bestimmung des Brechungsindexes eines Mediums ist folglich
die Lichtgeschwindigkeit in diesem Medium beziehungsweise die Abweichung von der
Vakuum-Lichtgeschwindigkeit zu bestimmen. In der Vorlesung wird dies für das
Ausbreitungsmedium Wasser durchgeführt.

#### Durchführung
Um die Ausbreitungsgeschwindigkeit des Lichts zu bestimmen, muss dessen Laufzeit
für eine vorgegebene Strecke gemessen werden. Für die Messung wird das
CASSY-System der Firma LD Didactic mit einem Laser-Entfernungsmesser verwendet.
Dieses Gerät sendet einen modulierten Laserstrahl aus, der am angepeilten Objekt
reflektiert wird und zurück in den Entfernungsmesser gelangt. Aus der
Phasenverschiebung der Modulation zwischen ausgesendeter und reflektierter
Welle ermittelt das Messgerät die Laufzeit des Lichts und hieraus die Entfernung
des angepeilten Objekts. In der CASSY-Software kann zwischen Laufzeit und
Entfernung als Messgröße gewählt werden. Für den vorliegenden Versuch wurde
erstere aufgezeichnet.

Dieser Entfernungsmesser befindet sich über einem hohen Standzylinder aus Glas.
Anfangs ist dessen Boden nur einige Zentimeter hoch mit Wasser bedeckt. Später
wird weiteres Wasser aus einem höher positionierten Behälter über einen seitlich
angebrachten Stutzen zufließen.
Dieser Stutzen befindet sich dicht über dem Boden des Zylinders liegt bereits zu
Beginn vollständig unter Wasser. Auf diese Weise werden Wellenbewegungen durch
zuströmendes Wasser vermieden, die sonst die Laufzeitmessung des Lichts stören
würden. Unter dem Standzylinder befindet sich eine Reflektorscheibe, auf die
der Laserstrahl des Entfernungsmessers gerichtet ist.

![Skizze des Versuchsaufbaus](grafik/BrechzahlWasser_Skizze.svg)<!-- style="width:8cm;" -->

In dieser Konfiguration wird die Aufzeichnung der Messwerte gestartet. Die
Laufzeit des Lichts ist erwartungsgemäß konstant. Wenn der Wasserzufluss
geöffnet wird, steigt der Wasserspiegel im Standzylinder an und die gemessene
Laufzeit des Lichts vergößert sich kontinuierlich. Dieser Anstieg der Laufzeit
ist der direkte Nachweis der verringerten Lichtgeschwindigkeit im Wasser (im
Vergleich zur Luft).

![Messkurve: Laufzeit des Lichts](grafik/BrechzahlWasser_Kurve.png "Messkurve: Laufzeit des Lichts (hier als Messgröße $\Delta t_\mathrm{A1}$ bezeichnet) im zeitlichen Verlauf der Befüllung des Standzylinders. Die vereinzelten starken Schwankungen des Messwerts entstanden durch Streueffekte an Luftblasen oder Wellen.")

Nachdem der Wasserspiegel um eine definierte Höhe $\Delta h$ angestiegen ist,
wird die Wasserzufuhr gestoppt. Die Laufzeit des Lichts ist nun wieder konstant.
Anschließend wird auch die Messwertaufzeichung beendet. Die Laufzeiten des
Lichts vor Beginn der Befüllung ($t_1$) sowie nach dem Ende der Befüllung
($t_2$) werden jeweils als Mittelwert aus den konstanten Abschnitten der
Messkurve bestimmt. Daraus und aus der Höhe $\Delta h$ kann der Brechungsindex
des Wassers bestimmt werden.

#### Auswertung
Der Laserstrahl verläuft vom Entfernungsmesser ausgehend durch Luft, Wasser,
Glas (Boden des Standzylinders) und Luft bis zur Reflektorscheibe und durch
dieselben Medien zurück in den Sensor. Dieser Laufweg des Lichts lässt sich in
zwei Anteile aufspalten:

1.  $s_\mathrm W=2\Delta h$: Die Strecke, um die der Wasserspiegel steigt. Zu
    Beginn legt das Licht diesen Weg durch Luft zurück, am Ende des Experiments
    durch Wasser. Da das Licht den Standzylinder zweimal passiert (Hin- und
    Rückweg) ist die Höhendiffernz doppelt zu berücksichtigen.

2.  $s_\mathrm R$: Die gesamte restliche Strecke durch Glas, Luft und die
    Anfangsmenge an Wasser. Für diese Strecke tritt keine Veränderung ein.

Der gesamte zurückgelegte Weg ist dann $s_\mathrm{ges}=s_\mathrm W + s_\mathrm R$.

Die Laufzeit des Lichts lässt sich in analoger Weise in die beiden Anteile
$t_\mathrm W$ und $t_\mathrm R$ aufteilen:
$t_\mathrm{ges}=t_\mathrm W +t_\mathrm R$.

Zu Beginn des Experiments:

$$t_1= t_\mathrm{W(Luft)}+t_\mathrm R$$

und am Ende des Experiments:

$$t_2= t_\mathrm{W(Wasser)}+t_\mathrm R$$

Für die Zeitdifferenz

$$\begin{aligned}
t_2-t_1 & = t_\mathrm{W(Wasser)}+t_\mathrm R-(t_\mathrm{W(Luft)}+t_\mathrm R) \\
& =t_\mathrm{W(Wasser)}- t_\mathrm{W(Luft)}
\end{aligned}$$

ist dabei nur die Teilstrecke $s_\mathrm W$ relevant. Für deren zugehörige
Laufzeit gilt am Anfang des Experiments:

$$t_\mathrm{W(Luft)}=\frac{s_\mathrm W}{c_0} \, ,$$

wobei für die Ausbreitungsgeschwindigkeit in Luft die Vakuumlichtgeschwindigkeit
angesetzt wurde ($n_\mathrm{Luft} =1$). Am Ende des Experiments gilt:

$$t_\mathrm{W(Wasser)}=\frac{s_\mathrm W}{c_\mathrm W}=\frac{s_\mathrm W}{c_0}n_\mathrm W$$

Einsetzen in die Formel für die Zeitdifferenz:

$$\begin{aligned}
t_2 - t_1 & =\frac{s_\mathrm W}{c_0}n_\mathrm W - \frac{s_\mathrm W}{c_0} \\
& = \frac{s_\mathrm W}{c_0}\left( n_\mathrm W -1 \right) \\
& = \frac{2\Delta h}{c_0}\left( n_\mathrm W -1 \right)
\end{aligned}$$

Umstellen liefert die Formel für die Brechzahl:

$$n_\mathrm W = 1+\frac{c_0}{2\Delta h}\left(t_2 - t_1 \right)$$

#### Ergebnisse vom 11.06.2021
In der Vorlesung „Elektrodynamik – Optik / Grundlagen der experimentellen Physik
II“ am 11.06.2021 wurden folgende Werte für diesen Versuch bestimmt:

* $t_1 = 5{,}248~\mathrm{ns}$
* $t_2 = 5{,}961~\mathrm{ns}$
* $\Delta h = 30~\mathrm{cm}$

Daraus ergibt sich ein Brechungsindex von $n_\mathrm W = 1{,}36$.

### Einzelphotoneninterferenz

Das Licht ist ein Quantenphänomen, das die Eigenschaften einer Welle und eines
Teilchens in sich vereint. Klassisch schließen sich Wellen- und
Teilchencharakter gegenseitig aus. Der Welle-Teilchen-Dualismus, wie ihn die
Quantenoptik kennt, ist mit der klassischen Physik nicht vereinbar.
Aus diesem Grund entzieht sich auch das Licht in seiner Gesamtheit unserer
Vorstellung.

Ungeachtet dessen lässt sich das Licht durch Anwendung des Wellen- oder
Teilchenmodells physikalisch sehr genau beschreiben. Die Frage, welches dieser
Modell anzuwenden ist, wird beantwortet durch den Charakter, den das Licht in
dem zu beschreibenden Sachverhalt zeigt. Eine scharfe Trennung zwischen
Welleneigenschaften (verkörpert eben durch eine Lichtwelle) und
Teilcheneigenschaften (verkörpert durch das Photon) ist dabei nicht möglich.
Auch das einzelne Photon trägt den vollständigen Wellencharakter des Lichts in
sich. Verdeutlicht wird dies im Vorlesungsexperiment durch den Nachweis der
Interferenz einzelnen Photonen.

#### Durchführung
Durchgeführt wird dieser Versuch mit dem Komplettaufbau „Two-Slit Interference,
One Photon at a Time“ der Firma TeachSpin.

Um die Interferenz einzelner Photonen überhaupt nachweisen zu können, müssen
einzelne Photonen detektiert werden. Dies geschieht mittels eines
Sekundärelektronenvervielfachers (englisch: photo multiplier), der aus einem
auftreffenden Photon einen messbaren Spannungspuls generiert.

Ferner müssen in der Apparatur einzelne Photonen erzeugt werden.
Grundsätzlich emittiert jede Lichtquelle eine Abfolge einzelner Photonen. Bei
hohen Lichtintensitäten kann dieser Photonenstrom als kontinuierlich angesehen
werden. Durch Verringerung der Intensität wird der (mittlere) zeitliche Abstand
zwischen zwei aufeinanderfolgenden Photonen vergrößert. Folglich kann eine
gewöhnliche Lichtquelle mit sehr geringer Intensität als Einzelphotonenquelle
aufgefasst werden. In der vorliegenden Apparatur beträgt der Lichtweg von der
Quelle bis zum Detektor $~\approx 1~\mathrm m$. Ein Photon legt diese Strecke in
$\approx 3~\mathrm{ns}$ zurück. Ist die mittlere Wartezeit zwischen zwei
emittierten Photonen groß im Vergleich zu dieser Laufzeit, kann davon
ausgegangen werden, dass sich stets höchstens ein Photon in der Anlage befindet.

Im Experiment wird die hierfür benötigte geringe Lichtintensität durch eine
Glühlampe erreicht, die mit sehr geringer Spannung betrieben wird. Das Licht
passiert anschließend einen monochromatischen Grünfilter, der die Intensität
nochmals reduziert. Außerdem ist die Beschränkung auf eine einzelne Wellenlänge
Voraussetzung für die Beobachtung des Interferenzmusters.

Das so erzeugte und gefilterte Licht trifft anschließend auf einen Doppelspalt.
Hinter diesem befindet sich eine Blende als „Spaltblocker“, mit der – je nach
Position – einer der beiden Spalte abgedeckt werden kann. Am „hinteren“ Ende der
Apparatur befindet sich schließlich der oben bereits beschriebene Detektor.
Davor ist eine verschiebbare Spaltblende angeordnet, mit deren Hilfe die Position
ausgewählt wird, an der die auftreffende Photonenzahl (Lichtintensität)
gemessen werden soll.

Im Vorlesungsversuch wird nur an zwei im Vorfeld bestimmten Detektorpositionen
gemessen, um den zeitlich Rahmen innerhalb der Vorlesung nicht zu sprengen. Für
jede Detektorposition werden drei Messungen mit unterschiedlichen Einstellungen
des Spaltblockers vorgenommen:

1. Nur der linke Spalt ist freigegeben, der rechte Spalt ist verdeckt.
2. Beide Spalte sind freigegeben.
3. Nur der rechte Spalt ist freigegeben, der linke Spalt ist verdeckt.

Bei jeder Messung wird über eine Zeit von 10 Sekunden die Anzahl der ankommenden
Photonen registriert. Für die Messungen muss die gesamte Apparatur lichtdicht
verschlossen sein, da jegliches Streulicht auf dem Detektor die zu messende
Intensität übersteigen würde.

#### Ergebnisse vom 27.01.2020
In der Vorlesung „Physik (mit Experimenten)“ am 27. Januar 2020 wurden folgende
Photonenzahlen registriert:

*  Detektorposition I

| offene Spalte | registrierte Photonen |
| ------------- | ---------------------:|
| links         | 275                   |
| beide         | 983                   |
| rechts        | 203                   |

*  Detektorposition II

| offene Spalte | registrierte Photonen |
| ------------- | ---------------------:|
| links         | 343                   |
| beide         | 48                    |
| rechts        | 202                   |

#### Diskussion
Die Messergebnisse zeigen ein grundlegend unterschiedliches Verhalten an den
beiden Detektorpositionen:
*  In Position I führt die Überlagerung des Signals beider Spalte zu einer
   Verstärkung des Photonenzählrate, die deutlich über die Summe der Zählraten
   beider Einzelspalte hinausgeht.
*  In Position II hingegen resultiert die Öffnung beider Spalte in einer
   Verrringerung der Zählrate im Vergleich zu den Einzelspalten.

Beide Erscheinungen lassen sich nur durch Interferenz erklären, die im
Maximum zur Verstärkung, im Minimum hingegen zu einer (nahezu vollständigen)
Auslöschung führt. Die beiden Detektorpositionen wurden bei der Justage des
Versuchsaufbaus so bestimmt, dass sie im Nullten Maximum (Position I)
beziehungsweise im ersten Minimum (Position II) liegen. Da sich entsprechend der
anfänglichen Ausführungen stets höchstens ein Photon in der Apparatur befindet,
kann dieser Effekt nicht durch die Überlagerung mehrerer Photonen erklärt
werden. Vielmehr interferiert das einzelne Photon mit sich selbst. Es folgt
daraus, dass auch das oft als Teilchen aufgefasste Photon den vollständigen
Wellencharakter in sich trägt.

## Atomphysik

### Franck<!-- style ="font-variant: small-caps;" -->-Hertz<!-- style ="font-variant: small-caps;" -->-Versuch

Dieser nach James<!-- style ="font-variant: small-caps;" -->
Franck<!-- style ="font-variant: small-caps;" --> und
Gustav<!-- style ="font-variant: small-caps;" --> Hertz<!-- style ="font-variant: small-caps;" -->
benannte Versuch untersucht die Anregung von Atomen durch Elektronenstoß. In
einem Gas unter geringem Druck treffen beschleunigte Elektronen auf die
Gasatome. Eine Anregung dieser Atome in ein höheres Energieniveau ist dabei nur
möglich, wenn die (kinetische) Energie der Elektronen der erforderlichen
Anregungsenergie entspricht oder diese übersteigt.

#### Durchführung

Für diesen Versuch wird eine evakuierte Glasröhre verwendet, die
mit einer geringen Menge eines Gases gefüllt ist. In den ursprünglichen
Experimenten verwendeten Franck und Hertz Quecksilberdampf; in der Vorlesung
wird eine Röhre mit Neonfüllung verwendet. Dies vereinfacht einerseits die
Durchführung (da die Röhre nicht aufgeheizt werden muss), andererseits lassen
sich Anregungszonen in der Röhre durch das charakteristische orange-rote
Leuchten der Neonatome erkennen (siehe Abbildung).

![Leuchtzonen in einer neongefüllten Franck-Hertz-Röhre](https://upload.wikimedia.org/wikipedia/commons/thumb/5/51/Franck-Hertz-Neon-3.png/279px-Franck-Hertz-Neon-3.png "Blick in eine in Betrieb befindliche Franck-Hertz-Röhre mit Neon-Füllung: Die Anregungszonen sind zwischen dem Steuergitter (unten) und der Anode (oben) durch ihr charakteristisches orange-rotes Leuchten erkennbar. [Quelle: [Infoczo](https://commons.wikimedia.org/wiki/User:Infoczo), [Franck-Hertz-Neon-3](https://commons.wikimedia.org/wiki/File:Franck-Hertz-Neon-3.png), [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode) via Wikimedia Commons]")

Eingeschmolzen in diese
Glasröhre sind vier Elektroden (siehe folgende Abbildung): Die Kathode (K) wird
durch die angelegte Heizspannung $U_\mathrm H$ zum Glühen gebracht und emittiert
so Elektronen, die durch die Beschleunigungsspannung $U_\mathrm B$ zur Anode (A)
hin beschleunigt werden. Kurz hinter der Kathode befindet sich mit dem
Steuergitter (SG) eine zusätzliche Elektrode, die den Stromfluss steuert, den
eigentlichen physikalischen Effekt jedoch nicht beeinflusst. Daher wird dieses
Gitter im Folgenden nicht weiter betrachtet. Die Anode ist als Netz ausgeführt,
sodass die Elektronen diese passieren können und danach auf die
Auffängerelektrode (E) treffen. Zwischen Anode und Auffängerelektrode liegt die
Gegenspannung $U_\mathrm G$ an, die die Elektronen abbremst.

![Schematischer Aufbau einer Franck-Hertz-Röhre](https://upload.wikimedia.org/wikipedia/commons/2/2b/FH_R%C3%B6hre_Ne.svg "Schematischer Aufbau einer neongefüllten Franck-Hertz-Röhre. Die Beschreibung des Aufbaus und der Abkürzungen erfolgt im Text. [Quelle: [Herbert Schletter](https://commons.wikimedia.org/wiki/User:HerrvomDorf) (derived from a work by [Sebastian Wagner](https://commons.wikimedia.org/wiki/User:RealSebix)), [FH Röhre Ne](https://commons.wikimedia.org/wiki/File:FH_Röhre_Ne.svg), [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode) via Wikimedia Commons]")

Gemessen wird im Franck-Hertz-Versuch der an der Auffängerelektrode ankommende
Elektronenstrom $I_\mathrm E$ als Funktion der Beschleunigungsspannung
$U_\mathrm B$.

#### Ergebnisse vom 08.07 2021

In der Vorlesung „Physik“ wurde am 08.07.2021 folgende Franck-Hertz-Kurve an
Neon gemessen:

![Franck-Hertz-Kurve an Neon, gemessen am 08.07.2021](grafik/franck-hertz_2021-07-08.png)

Dargestellt ist der Strom $I_\mathrm E$ an der Auffängerelektrode (in
willkürlichen  Einheiten) als Funktion der Beschleunigungsspannung $U_\mathrm A$.

Das Plateau des gemessenen Stroms bei $U_\mathrm A \gt 75~\mathrm V$ entstand
durch eine Sättigung des Messverstärkers. Die kleinen vertikalen Versatze in der
Messkurve entstanden, als die Beschleunigungsspannung konstant gehalten wurde
(um einen Sachverhalt in der Durchführung zu erklären), die Emission der Kathode
sich jedoch veränderte.

#### Diskussion

In der nachfolgenden Abbildung ist exemplarisch eine Messkurve gezeigt, die mit
dem in der Vorlesung gesezigten Franck-Hertz-Aufbau aufgenommen wurde.
Die einzelnen Abschnitte (im Bild durch die Zahlen 1 bis 5 markiert) dieser
$I_\mathrm E (U_\mathrm B )$-Abhängigkeit lassen sich unter Anwendung des
Atommodells und der Gesetze der Elektrizitätslehre erklären.

![Messkurve einer Franck-Hertz-Röhre.](grafik/V15_FH-kurve.png "Messkurve $I_\mathrm E (U_\mathrm B)$ einer neongefüllten Franck-Hertz-Röhre. Die Erläuterung der Abschnitte 1 bis 5 erfolgt im Text.")<!-- style="width:12cm;" -->

1.  Solange die Beschleunigungsspannung kleiner ist als die Gegenspannung
    ($U_\mathrm B < U_\mathrm G$), werden die Elektronen vor Erreichen der
    Auffängerelektrode vollständig abgebremst. Folglich wird an dieser kein
    Strom gemessen. In der Messkurve in obiger Abbildung zeigt sich an dieser
    Stelle ein Offset des Messstroms, der durch geeignete Kalibrierung der
    Messapparatur behoben werden könnte. Da dieser Offset jedoch für die gesamte
    Messung konstant ist, beeinflusst er die weitere Diskussion nicht.

2.  Sobald die Beschleunigungsspannung die Gegenspannung übersteigt, erreichen
    die Elektronen die Auffängerelektrode und es wird ein Strom gemessen. Mit
    zunehmender Beschleunigungsspannung wächst dieser Strom an, da die
    kinetische Energie der Elektronen zunimmt.

3.  Oberhalb einer gewissen Beschleunigungsspannung nimmt der Auffängerstrom ab.
    Dieser Effekt entsteht durch Anregung der Neonatome: Die Atome nehmen
    Energie der beschleunigten Elektronen auf, sodass innerhalb der Atome
    gebundene Elektronen in ein höheres Energieniveau übergehen können. Aufgrund
    der diskreten Energieniveaus kann diese Anregung erst stattfinden, wenn die
    kinetische Energie der beschleunigten Elektronen die erforderliche
    Energiedifferenz der Niveaus übersteigt. Gleichzeitig ist in der Röhre ein
    orange-rotes Leuchten erkennbar (siehe obere Abbildung), das durch die
    Rückkehr der angeregten Elektronen in ihren Ausgangszustand entsteht. Diese
    Leucht- oder Anregungszone entsteht zunächst unmittelbar vor der Anode, da
    erst dort die beschleunigten Elektronen eine ausreichend hohe Energie
    erreichen.

4.  Bei weiterer Erhöhung der Beschleunigungsspannung wandert die Anregungszone
    in Richtung Kathode, da die beschleunigten Elektronen bereits früher die zur
    Anregung erfoderliche Energie besitzen. Nach dieser Energieabgabe werden die
    Elektronen weiter zur Anode hin beschleunigt, sodass der an der
    Auffängerelektrode gemessene Strom wieder ansteigt.

5.  Bei ausreichend hoher Beschleunigungsspannung erhalten die Elektronen nach
    der ersten Energieabgabe wieder die zur Anregung der Neon-Atome
    erforderliche Energie. So entsteht unmittelbar vor der Anode eine zweite
    Anregungszone, in der die beschleunigten Elektronen Energie abgeben. In der
    Folge nimmt der Auffängerstrom wiederum ab. Bei weiterer Erhöhung von
    $U_\mathrm B$ wandern beide Anregungszonen in Richtung Kathode. Durch die
    weitere Beschleunigung der Elektronen nach der zweiten Anregungszone steigt
    der Auffängerstrom wieder an. Eine dritte Anregungszone entsteht, wenn nach
    zweimaliger Anregung der Neon-Atome die Elektronen wiederum auf die
    erforderliche Anregungsenergie beschleunigt werden. Dabei zeigt der
    Auffängerstrom ein drittes Minimum. Insgesamt sind dann drei Anregungszonen
    mit ihrem orange-roten Leuchten in der Röhre erkennbar (wie in der oberen
    Abbildung gezeigt).

In einer neongefüllten Franck-Hertz-Röhre treten die Minima des Auffängerstroms
in Abständen von $\Delta U_\mathrm B =19~\mathrm V$ auf. Dies entspricht der
Energiedifferenz der für die Anregung relevanten Energieniveaus
$\Delta E = 19~\mathrm{eV}$. Die Rückkehr in den Ausgangszustand erfolgt
stufenweise über mehrere Energieniveaus, wobei nur einer der beteiligten
Übergänge das charakteristische orange-rote Licht emittiert.
