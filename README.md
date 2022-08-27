# Prometheus Toturial

## Einleitung
Prometheus ist eine 2-Layer PCB-Fräse (PCB = Printed Circuit Board). Angesteuert wird die PCB-Fräse mit ProCAM von Zippy Robotics. Die Windows-Software steht auf der Herstellerseite zippyrobotics.com zum Download zur Verfügung. Das PCB-Design wird z. B. mit KiCad erstellt und die Layer in ProCAM importiert. In ProCAM werden auch alle Parameter wie Fräser- und Bohrerdurchmesser oder die Anzahl der Fräs-Durchgänge festgelegt.

## Installation
ProCAM Download: http://www.zippyrobotics.com/download

## ProCAM installieren
Nach dem Download sind folgende Schritte auszuführen:
1. Den Ordner C:\Program Files (x86)\Zippy Robotics erstellen,
2. die Download-Dateien entpacken und in den Ordner kopieren,
3. die EXE-Datei starten.
4. Auf der Herstellerseite stehen auch Hilfe-Videos zur Verfügung

![procam1](https://github.com/frankyhub/Prometheus-Toturial/blob/main/PrometeusPIC/procam1.png)

Die ProCAM Software by Zippy Robotics

## KiCad Checkliste
In KiCad folgende Schritte ausführen:
[ ] Die max Platinengröße: 160 x 100

[ ] Große Pads verwenden (Empfehlung 3mm)

[ ] Gleich große Bohrlöcher definieren (Empfehlung 0,85)

[ ] Einen großen Leiterbahnquerschnitt verwenden (Empfehlung 0.5mm)

[ ] Für einen positiven Arbeitsbereich der X-Y-Achsen den "Offset für Bohrungen und Platzierungen" links unten einfügen

[ ] Die Edge Cut Linien müssen in sich geschlossen sein

[ ] Die Plotter Einstellungen anpassen

[ ] Die Plotter und Bohrdatei erzeugen

[ ] Das Leerzeichen aus der DRL-Datei löschen



In KiCad den Offset für Bohrungen links unten einfügen

![procam2](https://github.com/frankyhub/Prometheus-Toturial/blob/main/PrometeusPIC/procam2.png)

In KiCad die Plotter Einstellungen anpassen

![procam4](https://github.com/frankyhub/Prometheus-Toturial/blob/main/PrometeusPIC/procam4.png)

In KiCad die Drilldatei Einstellungen anpassen
![procam5](https://github.com/frankyhub/Prometheus-Toturial/blob/main/PrometeusPIC/procam5.png)

Änderung in der Drilldatei (Das Leerzeichen löschen - ;FORMAT)
![procam6](https://github.com/frankyhub/Prometheus-Toturial/blob/main/PrometeusPIC/procam6.png)

## ProCAM Checkliste

In ProCAM folgende Schritte ausführen:
[ ] Die Top-Copper, Drill- und Cut out-Datei importieren

[ ] Das Top-Copper Bohrwerkzeug einstellen (blau .005 in (.130mm) 15 deg. mill)

[ ]  Die Anzahl der Durchgänge festlegen (Empfehlung 2)

[ ]  Die Platine mit doppelseitigen Klebeband (4 Reihen) fixieren

[ ]  Die Elektrische Verbindung zwischen Platine und der Messingleiste herstellen (Krokodilklemme)

## Top Copper:
[ ]  Den .005 in (.130mm) 15 deg. mill Fräser einspannen (blau 5-mill 15°)

[ ]  Die Knuppel zum spannen nach links schieben

[ ]  Das Kugellager von der Frässpitze aus aufschieben

[ ]  Den Fräser mit der Magnetplatte in die Spannvorrichtung stecken

[ ]  Den Knuppel nach rechts schieben und festen Sitz kontrollieren

[ ]  Die Platinenoberfläche mit Öl benetzen

[ ]  Den Fräsvorgang starten

## Drill:
[ ]  Den Bohrer für die Bohrlöcher wechseln (lila 0,85mm)

[ ]  Die Elektrische Verbindung zwischen Platine und der Messingleiste herstellen

[ ]  Den Knuppel zum spannen nach links schieben

[ ]  Das Kugellager von der Bohrerspitze aus aufschieben

[ ]  Den Bohrer mit der Magnetplatte in die Spannvorrichtung stecken

[ ]  Den Knuppel nach rechts schieben und festen Sitz kontrollieren

[ ]  Den Bohrvorgang starten

## Cut out:
[ ]  Den Fräser für die Edge cut wählen (rot 0.0315" Router - Square End Mill)

[ ]  Die Elektrische Verbindung zwischen Platine und Messingleiste herstellen

[ ]  Den Knuppel zum spannen nach links schieben

[ ]  Das Kugellager von der Frässpitze aus aufschieben

[ ]  Den Fräser mit der Magnetplatte in die Spannvorrichtung stecken

[ ]  Den Knuppel nach rechts schieben und festen Sitz kontrollieren

[ ]  Die Platinenoberfläche mit Öl benetzen, ggf die Späne absaugen

[ ]  Den Edge cut starten

[ ]  Den Arbeitsplatz aufräumen



Prometheus Fräser und Bohrer

![procam9](https://github.com/frankyhub/Prometheus-Toturial/blob/main/PrometeusPIC/procam9.png)

![procam10](https://github.com/frankyhub/Prometheus-Toturial/blob/main/PrometeusPIC/procam10.png)

Die Startseite von ProCAM
![procam11](https://github.com/frankyhub/Prometheus-Toturial/blob/main/PrometeusPIC/procam11.png)

