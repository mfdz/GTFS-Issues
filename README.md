# GTFS-Issues

Documentation and tracking of data quality problems in [GTFS](https://gtfs.org) data sets.

Previously, this project had been limited to German data sets, but you're invited to document problems in other regions, too!

## Background
Data, just like software, contain errors. However, while (open source) software development projects deal openly and transparently with such errors, this is still rather uncommon with data: errors are reported via email to the data responsible party and then (hopefully) eventually disappear from the data.

This approach has several disadvantages:
- When discovering a data quality issue, I cannot tell if someone else has already investigated and reported it. It might happen that I replicate their work even though *another* detail report to the publisher might not help much.
- When a data quality issue is fixed, usually only the reporting part (if at all) will be notified about the fix. Others cannot observe the status "passively".
- Even as the publisher getting the reports, it is hard to get an overview over the current state of all data quality issues. For third parties that don't receive the reports, it is usually impossible.

This also applies to GTFS data, which is fortunately increasingly being published by transport associations.

As most of today's open data platforms do not yet include "issue trackers" for reporting and tracking data errors, we launched this GitHub project 6 years ago, originally only for German feeds (that's the reason why many issues were submitted in German language). Just like back then, we still hope today that the mobility industry recognizes the benefits of open issue trackers for datasets and eventually provides such tools themselves.

For GTFS feeds, we want to document known data issues and make them traceable. Anyone who identifies an error in the data is encouraged to post it here. Ideally, transport associations will use this platform to provide information about the error and updates on their work to eliminate it. Until we achieve this goal, we ask everyone who reports an error here to also report it to the transport association and document new information here.

## How do I report an issue?
If you have identified an error in the data, create a new issue. Prefix it with the abbreviation of the transport association or data provider in the title.

Describe the observed problem as specifically as possible, if necessary with a short GTFS feed extract, an image, or a validator's error message.

If the transport association/company is not already watching this project, also report the error by email to the responsible data authorities.

When you receive new information from the transport association/company, or the data has been corrected, update or close your issue created here.

* [Report a problem](https://github.com/mfdz/GTFS-Issues/issues/new/choose)
* [View Reported Issues](https://github.com/mfdz/GTFS-Issues/issues)

## Transport associations and companies
The following transport associations and companies are already monitoring this page and do not need to be contacted separately:

* Rhein-Neckar-Verkehr GmbH (RNV, Germany)
* Nahverkehrsgesellschaft Baden-Württemberg mbH (NVBW, Germany)
* [Verkehrsverbund Berlin-Brandenburg](https://en.wikipedia.org/wiki/Verkehrsverbund_Berlin-Brandenburg) (VBB, Germany)

--

# GTFS-Issues
Dokumentation und Verfolgung aktueller Probleme deutschsprachiger GTFS-Datensätze.

## Idee
Daten enthalten, genauso wie Software, Fehler. Doch während bei (Open-Source-)Software mit solchen Fehlern offen und transparent umgegangen wird, ist dies bei Daten bisher noch eher selten der Fall: Fehler werden per E-Mail an den Datenverantwortlichen gemeldet und sind dann (hoffentlich) irgendwann aus den Daten verschwunden.

Dies gilt auch so für GTFS-Daten, die erfreulicherweise zunehmend von Verkehrsverbünden veröffentlicht werden.

Da die heute häufig zur Veröffentlichung eingesetzten Open-Data-Plattformen noch nicht über "Issue-Tracker" zur Meldung und Nachverfolgung von Datenfehlern verfügen, haben wir vor 6 Jahren dieses GitHub-Projekt gestartet. Wie damals hoffen wir heute immer noch, dass die Mobilitäts-Branche den Nutzen offener Issue-Tracker für Datensätze erkennt und irgendwann einmal selbst solche bereitstellt.

Für GTFS-Feeds wollen wir hier bekannte Datenprobleme dokumentieren und nachverfolgbar machen. Alle, die in den Daten einen Fehler feststellen, können diesen hier veröffentlichen. Idealerweise nutzen die Verkehrsverbünde diese Plattform, um Informationen zum Fehler und dessen Beseitigung zu liefern. Bis wir dieses Ziel erreicht haben, bitten wir alle, die hier einen Fehler melden, diesen auch an den Verkehrsverbund zu melden und neue Informationen dazu hier zu dokumentieren.

## Wie melde ich einen Fehler?
Wenn Du einen Fehler in den Daten festgestellt hast, erstelle einen neuen Issue. Stelle diesen im Titel das Kürzel des Verkehrsverbundes bzw. -unternehmen voran.

Beschreibe möglichst konkret das festgestellte Problem, ggfs. mit einem kurzen Extrakt aus den GTFS-Daten, einem Bild oder der Fehlermeldung eines Validators.

Falls der Verkehrsverbund/ das Verkehrsunternehmen nicht bereits dieses Projekt verfolgt, melde den Fehler auch per Mail an die zuständigen Datenverantwortlichen.

Wenn Du vom Verkehrsverbung/Unternehmen neue Informationen erhältst, oder die Daten korrigiert wurden, aktualisiere bzw. schließe Deinen hier angelegten Issue.

* [Problem melden](https://github.com/mfdz/GTFS-Issues/issues/new/choose) 
* [Gemeldete Probleme ansehen](https://github.com/mfdz/GTFS-Issues/issues)

## Verkehrsverbünde und -unternehmen
Die nochfolgenden Verkehrsverbünde und -unternehmen beobachten diese Seite bereits und müssen nicht gesondert angeschrieben werden:

* Rhein-Neckar-Verkehr GmbH (RNV, D)
* Nahverkehrsgesellschaft Baden-Württemberg mbH (NVBW, D)
* [Verkehrsverbund Berlin-Brandenburg](https://de.wikipedia.org/wiki/Verkehrsverbund_Berlin-Brandenburg) (VBB, Germany)
