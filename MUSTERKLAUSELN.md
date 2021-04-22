



# Musterlastenheft kommunale Datensouveränität

Der Text „Musterlastenheft zur kommunalen Datensouveränität“ steht unter der Lizenz CC-BY 4.0:\
Stadt Bonn / Stadt Münster

Sie finden im Folgenden die vorgeschlagenen Formulierungen eingebettet in erklärende Erläuterungen.

<br/>

## 1. Datenrechte

> Ziel von Teil 1 "Datenrechte": \
> Die folgenden Klauseln  dienen der **Festlegung Urheberrechtsinhaber & Nutzungsrecht.**


1.1 Das Urheberrecht der erzeugten und verarbeiteten Daten liegt ausschließlich und zeitlich unbefristet bei der Stadt `Musterstadt`.

1.2 Das Urheberrecht umfasst dabei das uneingeschränkte und zeitlich unbefristete Nutzungsrecht der Stadt `Musterstadt` an den erzeugten und verarbeiteten Daten. Das Nutzungsrecht umfasst dabei auch das Recht zu einer Open Data-Veröffentlichung unter einer von der Stadt `Musterstadt` frei wählbaren Datenlizenz sowie jedwedes Recht zu einer beliebigen Weiterverarbeitung durch die Stadt `Musterstadt`.

1.3 Eine Datennutzung der erzeugten und verarbeiteten Daten durch den Auftragnehmer ist gesondert schriftlich zu vereinbaren.


> Erläuterung zu den Punkten:
> * Zweck 1.1: Urheberrecht festlegen. Situation insbesondere bei Clouddiensten und Datenbankrechte bei extern gehosteten Verfahren. Kann auch sinnvoll sein bei Werkverträgen.
> * Zweck 1.2: Klärung Urheberrecht und Nutzungsrecht. Nur Nutzungsrecht ist ggf. zu wenig, da Rechte entzogen bzw. bei zeitlich befristeten Verträgen ablaufen können.
> * Zweck 1.3: Konkretisierung Auftragsdatenverarbeitung und Datenabfluss / Nachnutzung ohne Wissen des Auftraggebers


 <br/>

## 2. Technischer Datenzugang

> Ziel von Teil 2 ist es, **den technischen Datenzugang zu ermöglichen.**\
> Leider bieten viele (Fach-)Anwendungen keine Möglichkeit, auf die in der Anwendung gespeicherten Daten zuzugreifen, außer über die grafische Benutzeroberfläche für Mitarbeiter/Sachbearbeiter.\
> Technische Barrieren führen dann zum Verlust der Datenhoheit und eine Weiternutzung der Daten wird erschwert oder unmöglich gemacht. \
> Das ist insbesondere bei extern gehosteten Anwendungen (SAAS, Cloud) der Fall. Aber auch wenn die Daten in städtischen Datenbanken gespeichert werden, ist ein direkter Datenbankzugriff aus informationstechnsichen Gesichtspunkten nicht immer ein geeigneter Weg, weswegen ein API-Zugriff möglich sein sollte. \
> Die Erfahrung zeigt, dass dies in vielen Kontexten Probleme vermeidet: Smart City, Open Data, Ämterübergreifende Datennutzung, Anwendung moderner Datenanalyseverfahren, Einführung von Datenplattformen, generell weitere Digitalisierungsthemen im Umfeld von OZG, E-Akte, DMS.


2.1 Der technische Datenzugang (API) erfolgt grundsätzlich durch eine vom Auftragnehmer bereitgestellte und produktiv nutzbare IT-Schnittstelle für einen vollständigen Datenzugriff im maschinenlesbaren Format. Ein Format ist maschinenlesbar, wenn die enthaltenen Daten automatisiert weiterverarbeitet werden können. Die Datenausgabe soll mit Metadaten versehen sein.

2.2 Die API folgt einem gängigen Standard (wie z. B. REST oder SOAP) und kann ohne weitere kostenpflichtige Entwicklungssysteme genutzt werden.

2.3 Technisch etablierte und produktiv einsetzbare API-Standards (beispielsweise XÖV) sind vorrangig zu nutzen.

2.4 Eine detaillierte API-Dokumentation mit Erläuterung der Funktionen ist im Angebotspreis enthalten.

2.5 Soweit eine API nicht angeboten werden kann, ist optional mindestens eine maschinenlesbare Exportmöglichkeit der gesamten erzeugten und verarbeiteten Daten durch den Auftragnehmer umzusetzen.

2.6 Zusätzlich zu den Punkten 2.1 bis 2.3 ist optional eine extern nutzbare API oder mindestens ein Datenexport mit einer datenschutzkonformen und automatisierten Ausgabe der Inhalte in maschinenlesbaren Formaten zu realisieren (Externe Open Data-Veröffentlichung).

2.7 Ein Zugriff bzw. alternative Bereitstellung der Rohdaten durch den Auftragnehmer ist grundsätzlich technisch möglich und ist im Angebotspreis enthalten.


> Erläuterung zu den Punkten:
> * Zweck 2.1 - 2.4: Sicherstellung, dass ein automatisierter Zugriff auf die in der Anwendung verarbeiteten Daten ohne zusätzlich zu lizensierende Systeme möglich ist, dass dabei Programmierstandards genutzt werden können und dass eine Dokumentation vorhanden ist.
> * Zweck 2.5: Alternativ muss eine Exportmöglichkeit gegeben sein.
> * Zweck 2.6: Eine einheitliche externe Schnittstelle vereinfacht die Open-Data-Bereitstellung und somit Akzeptanz in den Fachbereichen. Außerdem ermöglicht ein Datenstandard eine regional übrergreifende Nachnutzung von Open-Data-Anwendungsfällen.
> * Zweck 2.7: Absicherung einer Datenmigration: Rohdaten (Kompletter Datenbestand) als Absicherung, falls API für eine vollständige Datenmigration ggf. nicht ausreicht. Stichwort Sicherung des Datenzugangs bei Clouddienstleistern / externes Hosting.

<br/>

## Weitere Anregungen:

* Die o. g. Anforderungen sind eine Formulierungshilfe für ein Musterlastenheft, welche sich textlich im zu beauftragenden Vertragswerk wiederfinden muss.
* Das Musterlastenheft hat häufig eine tabellarische und einfach bewertbare Form (Ja/nein bzw. „Erfüllt zu XX Prozent“), um unterschiedliche Angebote vergleichen zu können.
* Derzeit sind in 2.2 und 2.3 allgemeine API-Standards genannt (SOAP, REST). Wenn eine Kommune bereits eine konkrete Datenplattform nutzt, die bestimmte Standards unterstützt, können diese explizit genannt werden. Beispiel Hamburg: https://geoportal-hamburg.de/urbandataplatform/HH_UDP-Schnittstellen.pdf
