# Tempo-Exzesse auf Zürcher Strassen

Analyse von Geschwindigkeitsdaten auf drei von Zürichs umstrittensten Verkehrsachsen aus dem Januar 2021.  

**Hier kommt der Plot von einer der Karten hin mit ! aus dem Ordner aufrufen einfügen und erledigen** 


## 0 Recherche-These
------------------------------------------------------------------------------------------------------------------------

- **These**: Tempo 30 und die damit verbundenen Bussen zeigen Wirkung.
- **Thesen-Check**: Die Tempo-30-Diskussion wird in Zürich sehr dogmatisch geführt. Es gibt zwar Studien, die basieren allerdings häufig auf theoretischen Rechenmodellen. Zudem hat das Thema Schnellfahrer im Zusammenhang mit dem Unfall am Escher-Wyss-Platz zusätzliche Relevanz erhalten. Initialaufwand relativ gross, allerdings kann der Code später für API-Abfrage und weitere Geschichten im Zusammenhang mit Tomtom-Daten wiederverwendet werden: Aufwandsschätzung 6 Tage. 
- **Knackpunkt**: Die Datenlage ist zu knapp, um wirklich valide Aussagen treffen zu können. 
- **Briefing-Person konsultieren**: Eine Vorbesprechung fand im Januar statt. Justierung des Recherche-Fokus und Dimension innerhalb des Teams. 

## 1 Daten-Quelle
------------------------------------------------------------------------------------------------------------------------

Die niederländische Firma Tomtom ist eines der weitverbreitetsten Navigationssysteme weltweit: Tomtom schätzt, dass ihre Systemerund 20 Prozent des gesamten Autoverkehrs erfassen. Die Firma sammelt GPS-Daten und stellt sie in *aggregierter* Form für jeden Strassenabschnitt zur Verfügung. Ursprünglich stammen die Daten sowohl von portablen als auch von fest eingebauten Navigationsgeräten sowie Smartphones. **[Traffic-Stats-API](https://developer.tomtom.com/traffic-stats/documentation/api/introduction)**

### Probleme bei der Datenbeschaffung

Auch nach mehreren Monaten und unzähligen Versuchen der Kontaktaufnahme via Pressestelle, Developper-Tools und Support, wurde die **[Traffic-Stats-API](https://developer.tomtom.com/traffic-stats/documentation/api/introduction)** leider nicht geöffnet. 

Um trotzdem Daten zu Zürichs Strassen analysieren zu können, wurden die Daten mit einem Testzugang via **[Move-Portal](https://move.tomtom.com/register)** der Firma Tomtom beschafft. Ursprünglich war eine Analyse des gesamten Kantons Zürich vorgesehen. Allerdings können *via Move-Portal* nur maximal 20 Reports bezogen werden. Das machte eine Redimensionierung des Projektes notwendig. 

### Redimensionierung Recherche

Das machte eine redimensionierung des Projektes notwendig. Analysiert werden deshalb drei umstrittene Verkehrsachsen, die zuletzt politisch Anlass zu Diskussionen gab: 

- Bucheggplatz via Rosengartenstrasse und Hardbrücke bis zum Albisriedenplatz. [(Seit Jahren ein Politikum](https://www.20min.ch/story/laerm-ueber-grenzwert-trotzdem-blockiert-kantonspolizei-tempo-30-442140576340) 
- Die Wasserwerkstrasse, wo bereits im Jahr 2021 Tempo 30 eingeführt wurde. [(Siehe Ergebnisse Wirkungsanalyse Tempo30](https://www.zh.ch/de/news-uebersicht/medienmitteilungen/2020/07/resultate-der-wirkungsanalyse-zu-tempo-30--liegen-vor.html#-782269903) 
- Die Albisriedenstrasse, [wo kürzlich innert kurzer Zeit 350 Autos geblitzt wurden](https://www.tagesanzeiger.ch/radar-blitzte-350-mal-an-einem-tag-949756423047).


## 2 Daten-Reinigung, Segmentierung Strassenabschnitte und Berechnung Abweichung





## 3 Neustrukturierung der Files und Analye




## 4 Erstellung interaktive Grafiken




## 5 Story-Line und weiteres Vorgehen



## Aufwandslogbuch 

- Einlesen in API-Dokumentation und Datenstruktur: 1 Std. 
- Datenbeschaffung via Move-Portal: 2 Std. 
- Datenreinigung, Segmentierung und Berechnungen: 24 Std. (inkl. Recherchen, Nachschlagen, ausbessern des Codes mit Funktionen)
- Visualisierung: 16 Std. (inkl. Recherche für interaktive Karte) 
- Texten der Story-Line: 1 Std. (nach Entscheid für Variante 2)
- **Total: 28 Stunden**





