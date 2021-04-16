# Datennutzungsklauseln für kommunale Verträge

Die Städte Bonn und Münster haben die folgenden Formulierungen für ein „Musterlastenheft kommunale Datensouveränität“ entwickelt.

*Der primäre Zweck dieser Formulierungen ist, als **Bestandteil des Leistungsverzeichnisses** bei Beschaffungen bzw. Vergabeverfahren verwendet zu werden, um die Abstimmung, Regelung und Sicherung der **kommunalen Datensouveränität** zu unterstützen.*

Die Formulierungen sind in diesem Git-Repository veröffentlicht, um eine niederschwellige Kollaboration mit anderen Kommunen zu ermöglichen. Diese Formulierungen können entsprechend der Lizenz frei genutzt werden. Außerdem können in diesem Repository Verbesserungsvorschläge diskutiert und bearbeitet werden.

Der folgende Text „Musterlastenheft zur kommunalen Datensouveränität“ steht unter der Lizenz CC-BY 4.0:\
Stadt Bonn / Stadt Münster

## Musterlastenheft kommunale Datensouveränität

### 1. Datenrechte

> Zweck: Festlegung Urheberrechtsinhaber \
> -> Situation insb. Clouddienste bzw. gängige Datenbankrechte bei extern gehosteten Verfahren

1.1 Das Urheberrecht der erzeugten und verarbeiteten Daten liegt ausschließlich und zeitlich unbefristet bei der Stadt `Musterstadt`.

> Zweck: Klärung Urheberrecht und Nutzungsrecht \
> -> Nur Nutzungsrecht ist ggf. zu wenig, da Rechte entzogen bzw. bei zeitlich befristeten Verträgen ablaufen können. 

1.2 Das Urheberrecht umfasst dabei das uneingeschränkte und zeitlich unbefristete Nutzungsrecht der Stadt `Musterstadt` an den erzeugten und verarbeiteten Daten. Das Nutzungsrecht umfasst dabei auch das Recht zu einer Open Data-Veröffentlichung unter einer von der Stadt `Musterstadt` frei wählbaren Datenlizenz sowie jedwedes Recht zu einer beliebigen Weiterverarbeitung durch die Stadt `Musterstadt`.

> Zweck: Konkretisierung Auftragsdatenverarbeitung und Datenabfluss / Nachnutzung ohne Wissen des Auftraggebers

1.3 Eine Datennutzung der erzeugten und verarbeiteten Daten durch den Auftragnehmer ist gesondert schriftlich zu vereinbaren.

### 2. Technischer Datenzugang

> Zweck: Sicherstellung, dass ein automatisierter Zugriff auf die in der Anwendung verarbeiteten Daten möglich ist, z. B. für die Anbindung einer Datenplattform.\
> 

2.1 Der technische Datenzugang (API) erfolgt grundsätzlich durch eine vom Auftragnehmer bereitgestellte und produktiv nutzbare IT-Schnittstelle für einen vollständigen Datenzugriff im maschinenlesbaren Format. Ein Format ist maschinenlesbar, wenn die enthaltenen Daten automatisiert weiterverarbeitet werden können. Die Datenausgabe soll mit Metadaten versehen sein.

2.2 Die API folgt einem gängigen Standard (wie z. B. REST oder SOAP) und kann ohne weitere kostenpflichtige Entwicklungssysteme genutzt werden.

2.3 Technisch etablierte und produktiv einsetzbare API-Standards (beispielsweise XÖV) sind vorrangig zu nutzen. 

2.4 Eine detaillierte API-Dokumentation mit Erläuterung der Funktionen ist im Angebotspreis enthalten.

2.5 Soweit eine API nicht angeboten werden kann, ist optional mindestens eine maschinenlesbare Exportmöglichkeit der gesamten erzeugten und verarbeiteten Daten durch den Auftragnehmer umzusetzen.

> Zweck: Software mit expliziter Open-Data-Schnittstelle fördert einheitliche Datenformate und
> vereinfacht die Open-Data-Bereitstellung. Dies verstärkt Etablierung und Akzeptanz von Open
> Data in allen Fachbereichen.

2.6 Zusätzlich zu den Punkten 2.1 bis 2.3 ist optional eine extern nutzbare API oder mindestens ein Datenexport mit einer datenschutzkonformen und automatisierten Ausgabe der Inhalte in maschinenlesbaren Formaten zu realisieren (Externe Open Data-Veröffentlichung).

> Zweck: Absicherung einer Datenmigration: Rohdaten (Kompletter Datenbestand) als Absicherung, falls API für eine vollständige Datenmigration ggf. nicht ausreicht. Stichwort Sicherung des Datenzugangs bei Clouddienstleistern/ externes Hosting.

2.7 Ein Zugriff bzw. alternative Bereitstellung der Rohdaten durch den Auftragnehmer ist grundsätzlich technisch möglich und ist im Angebotspreis enthalten.

### Weitere Anregungen:

* Die o. g. Anforderungen sind eine Formulierungshilfe für ein Musterlastenheft, welche sich textlich im zu beauftragenden Vertragswerk wiederfinden muss.
* Das Musterlastenheft hat häufig eine tabellarische und einfach bewertbare Form (Ja/nein bzw. „Erfüllt zu XX Prozent“), um unterschiedliche Angebote vergleichen zu können.
* Derzeit sind nur allgemeine API-Standards genannt (SOAP, REST). Wenn eine Kommune bereits eine konkrete Datenplattform nutzt, die bestimmte Standards unterstützt, können diese explizit genannt werden, wie beim Beispiel Hamburg: https://geoportal-hamburg.de/urbandataplatform/HH_UDP-Schnittstellen.pdf

Kontakt:

```
Stadt Bonn, Sven Hense, Telefon: +49 228 77 36 99, E-Mail: sven.hense@bonn.de
Stadt Münster, Thomas Werner, Telefon: +49 251 492 19 09, E-Mail: wernerth@citeq.de
```

## Begründungen

Warum sind solche Vertragsklauseln wichtig?

A) Zitate aus PD "Datensouveraenitaet in der Smart City" 02/2020 \
(https://www.pd-g.de/assets/Presse/Fachpresse/200213_PD-Impulse_Datensouveraenitaet_Smart_City.pdf)

> 3.1.2.3 - Die Auswirkungen von IWG und PSI prüfen: Gehen Kommunen beziehungsweise kommunale Unternehmen im Smart-City-Kontext heute Verträge mit der Privatwirtschaft ein, stehen sie vor der Herausforderung, dass diese gegen die bis 2021 in nationales Recht umzusetzende, novellierte PSI-Richtlinie verstoßen könnten. 

> 3.1.2.4 - Datensouveränität in Ausschreibungsunterlagen aufnehmen - Kommunen unterliegen strikten Vergabevorschriften. Smart-City-Leistungen sind daher in der Regel ausschreibungspflichtig. Im Kontext der Datensouveränität stellt dies eine Chance dar: Wer bereits in den Ausschreibungsunterlagen genau definierte Anforderungen an die Datensouveränität formuliert, erspart sich rechtliche Unsicherheit beziehungsweise beugt (auch vergaberechtlich) schwierigen
Nachverhandlungen vor 

> 3.1.2.5 - Muster-Formulierungen entwickeln und interne Verwendung sicherstellen - Die Digitalisierung der Daseinsvorsorge im Sinne der Smart City ist ein kommunales Querschnittsthema. Diverse Fachbereiche nutzen die Digitalisierung entsprechend ihrer Fach-strategien und auch
kommunale Beteiligungen schließen Verträge mit Smart-City-Anbietern. 

B) Zitate aus Fraunhofer "Urbane Datenräume" 07/2018\
(https://www.iais.fraunhofer.de/content/dam/iais/pr/pi/2018/PI_20180629/UDR_Studie_062018.pdf)

> „Überführung der vorhandenen kommunalen technischen Infrastruktur in eine standardbasierte Infrastruktur mit offenen Schnittstellen und Formaten entsprechend einer allgemeinen IKTReferenzarchitektur“

> „Kommunen sollen den technischen und organisatorischen Aufbau ihres urbanen Datenraumes aktiv vorantreiben. Das soll sie in die Lage versetzen, ihre Daten nachhaltig für vielfältige innovative Dienste zu nutzen und die Datensouveränität herzustellen.“

> „Schärfung des Bewusstseins für mögliche Abhängigkeitsproblematiken (Vendor-Lock-ins) und frühes Entgegenwirken: Setzt eine Kommune bei der Gestaltung ihrer technischen IKTInfrastruktur auf die Technologien eines einzelnen Herstellers oder Betreibers, so kann hieraus eine Abhängigkeit entstehen, die sich auf lange Sicht Kosten- und aufwandsintensivaus wirkt. Daher sollten Kommunen in Verträgen den Aspekt der Offenheit bei der Anschaffung von Systemen und Produkten oder beim Outsourcing von Diensten berücksichtigen und sich die Auswirkungen von Vendor-Lock-ins bewusst machen“

> „Minimierung der Datenabhängigkeit von einem Anbieter“
 
