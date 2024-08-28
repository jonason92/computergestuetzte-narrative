-   [Inhalt](#inhalt){#toc-inhalt}
-   [Vorwort](#vorwort){#toc-vorwort}
-   [Einleitung](#einleitung){#toc-einleitung}
    -   [Die Replikationskrise in den
        Wissenschaften](#die-replikationskrise-in-den-wissenschaften){#toc-die-replikationskrise-in-den-wissenschaften}
    -   [2.2 Die Künstliche Intelligenz lernt
        sprechen](#die-künstliche-intelligenz-lernt-sprechen){#toc-die-künstliche-intelligenz-lernt-sprechen}
    -   [2.3 Methodik, oder: Die Informationswissenschaft kommt zur
        Rettung!](#methodik-oder-die-informationswissenschaft-kommt-zur-rettung){#toc-methodik-oder-die-informationswissenschaft-kommt-zur-rettung}
    -   [2.4 Computergestützte Narrative \[Computational
        Narratives\]](#computergestützte-narrative-computational-narratives){#toc-computergestützte-narrative-computational-narratives}
-   [Historische
    Hintergründe](#historische-hintergründe){#toc-historische-hintergründe}
    -   [3.1 Die
        Schriftgeschichte](#die-schriftgeschichte){#toc-die-schriftgeschichte}
    -   [3.2 Die
        Buchgeschichte](#die-buchgeschichte){#toc-die-buchgeschichte}
    -   [3.3 Die Geschichte des
        Web](#die-geschichte-des-web){#toc-die-geschichte-des-web}
    -   [3.4 Linked Open Data](#linked-open-data){#toc-linked-open-data}
-   [Open Science in der
    Praxis](#open-science-in-der-praxis){#toc-open-science-in-der-praxis}
    -   [FAIR-Prinzipien & Digitale
        Objekte](#fair-prinzipien-digitale-objekte){#toc-fair-prinzipien-digitale-objekte}
    -   [4.2 Daten-Management &
        Repositorien](#daten-management-repositorien){#toc-daten-management-repositorien}
-   [5. Ausführbare Bücher als strukturierte
    Wissenschaftskommunikation](#ausführbare-bücher-als-strukturierte-wissenschaftskommunikation){#toc-ausführbare-bücher-als-strukturierte-wissenschaftskommunikation}
    -   [5.1 Digital History](#digital-history){#toc-digital-history}
    -   [](#section){#toc-section}
    -   [5.2 Digital Humanities im Zeitalter computergestützter
        Narrative und digitaler
        Reproduktion](#digital-humanities-im-zeitalter-computergestützter-narrative-und-digitaler-reproduktion){#toc-digital-humanities-im-zeitalter-computergestützter-narrative-und-digitaler-reproduktion}
-   [6. Fazit und
    Ausblick](#fazit-und-ausblick){#toc-fazit-und-ausblick}
-   [7.
    Literaturverzeichnis](#literaturverzeichnis){#toc-literaturverzeichnis}

Universität Bern

Historische Fakultät

MAS ALIS in Archiv-, Bibliotheks-, und Informationswissenschaften

**Masterarbeit**

Betreuung: Prof. Dr. Tobias Hodel

**Open Science in der Praxis: Über den Sinn und die Entstehung von
computergestützten Narrativen innerhalb der Wissenschaftskommunikation
im frühen 21. Jahrhundert.**

**-**

**Hoffnungen, Chancen und Möglichkeiten.**

Jonas Hässig

12-450-185

jonason@protonmail.ch

Bern/Burgdorf, 30.07.2024

**\
**

***Abstract***

Diese Abschlussarbeit leistet einen Beitrag zum Sinn und der Entstehung
von computergestützten Narrativen innerhalb der
Wissenschaftskommunikation im frühen 21. Jhdt. Dies geschieht in einem
Kontext von Open Access und Open Science Bestrebungen. Folgende
theorie-, und praxisbildenden Ebenen werden angesprochen: Ausgehend von
den beiden problematisierten Themenfeldern der Replikationskrise in den
Wissenschaften sowie schwer durchschaubaren Fortschritten im Bereich der
künstlichen Intelligenz, beleuchtet die Arbeit zunächst die historischen
Hintergründe, von der Schriftgeschichte über die Buchgeschichte bis zur
Entwicklung des World Wide Web und Linked Open Data. Ein Schwerpunkt
liegt auf der Analyse von Open Science Praktiken und deren Umsetzung,
insbesondere im Hinblick auf FAIR-Prinzipien, digitale Objekte und
Datenmanagement. Die Arbeit liefert einen fundierten Literaturbericht
und eine Dokumentation, wie ausführbare Bücher als Form strukturierter
Wissenschaftskommunikation den Weg in eine Daten-intensive Zukunft ebnen
könnten. Besondere Aufmerksamkeit wird den Implikationen für die Digital
Humanities und die Bibliotheks-, Archiv- und Informationswissenschaften
gewidmet.

Methodisch kombiniert die Arbeit einen umfassenden Literaturbericht mit
praktischen Beispielen, die in Form eines ausführbaren Jupyter-Notebooks
präsentiert werden. Dadurch demonstriert sie nicht nur die theoretischen
Konzepte, sondern setzt sie auch praktisch um. Als lebendes, offenes &
ausführbares Dokument, mit kurierter Bibliografie, zugänglich über das
BORIS Portal der Universität Bern und GitHub. Auf diese Weise besteht
eine grosse Auswahl and Anschlussmöglichkeiten für Studierende,
Forschende und Promovierende, die sich in Teilaspekte der vorliegenden
Informationen vertiefen möchten.

"All the books of the world

will not bring you happiness,

but build a secret path

toward your heart.

what you need is in you:

the sun, the stars, the moon,

the illumination you were seeking

shines up from within you.

the quest for wisdom

made you comb the libraries.

now every page speaks the truth

that flashes forth from you."

--Hermann Hesse, \"Books\"

> *ORCID von Jonas Hässig*: <https://orcid.org/0009-0004-2126-9129>
>
> *GitHub*: <https://github.com/jonason92>
>
> Webpage zum visualisierten Jupyter-Notebook:
> <https://jonason-mas.curve.space/>
>
> Zotero Group-Bibliographie:
> <https://www.zotero.org/groups/5580329/open_science_jh>

# Inhalt {#inhalt .TOC-Heading .unnumbered}

[1. Vorwort [3](#vorwort)](#vorwort)

[2. Einleitung [6](#einleitung)](#einleitung)

[2.1 Die Replikationskrise in den Wissenschaften
[6](#die-replikationskrise-in-den-wissenschaften)](#die-replikationskrise-in-den-wissenschaften)

[2.2 Die Künstliche Intelligenz lernt sprechen
[7](#die-künstliche-intelligenz-lernt-sprechen)](#die-künstliche-intelligenz-lernt-sprechen)

[2.3 Methodik, oder: Die Informationswissenschaft kommt zur Rettung!
[10](#methodik-oder-die-informationswissenschaft-kommt-zur-rettung)](#methodik-oder-die-informationswissenschaft-kommt-zur-rettung)

[2.4 Computergestützte Narrative \[Computational Narratives\]
[14](#computergestützte-narrative-computational-narratives)](#computergestützte-narrative-computational-narratives)

[3. Historische Hintergründe
[17](#historische-hintergründe)](#historische-hintergründe)

[3.1 Die Schriftgeschichte
[17](#die-schriftgeschichte)](#die-schriftgeschichte)

[3.2 Die Buchgeschichte [19](#die-buchgeschichte)](#die-buchgeschichte)

[3.3 Die Geschichte des Web
[22](#die-geschichte-des-web)](#die-geschichte-des-web)

[3.4 Linked Open Data [24](#linked-open-data)](#linked-open-data)

[4. Open Science in der Praxis
[25](#open-science-in-der-praxis)](#open-science-in-der-praxis)

[4.1 FAIR-Prinzipien & Digitale Objekte
[28](#fair-prinzipien-digitale-objekte)](#fair-prinzipien-digitale-objekte)

[4.2 Daten-Management & Repositorien
[32](#daten-management-repositorien)](#daten-management-repositorien)

[5. Ausführbare Bücher als strukturierte Wissenschaftskommunikation
[35](#ausführbare-bücher-als-strukturierte-wissenschaftskommunikation)](#ausführbare-bücher-als-strukturierte-wissenschaftskommunikation)

[5.1 Digital History [38](#digital-history)](#digital-history)

[5.2 Digital Humanities im Zeitalter computergestützter Narrative und
digitaler Reproduktion
[39](#digital-humanities-im-zeitalter-computergestützter-narrative-und-digitaler-reproduktion)](#digital-humanities-im-zeitalter-computergestützter-narrative-und-digitaler-reproduktion)

[6. Fazit und Ausblick [41](#fazit-und-ausblick)](#fazit-und-ausblick)

[7. Literaturverzeichnis
[43](#literaturverzeichnis)](#literaturverzeichnis)

**\
**

# Vorwort

Die vorliegende Abschlussarbeit geht zurück auf den Studiengang MAS ALIS
2022-2024 in Archiv-, Bibliotheks-, und Informationswissenschaften an
der Universität Bern. Während diesen Studien habe ich mir als
Wissenshistoriker, Wissenschaftsphilosoph und angehender Bibliothekar
und Informationswissenschaftler vertieft Gedanken über gegenwärtige
Entwicklungen innerhalb des Gebietes der modernen
Wissenschaftskommunikation machen und diese in einen grösseren
wissenshistorischen Kontext stellen können. Auf der einen Seite erlebten
wir über die vergangenen Jahre, wie grosse Sprachmodelle auf dem Gebiet
der künstlichen Intelligenz regelrecht sprechen lernten und nun auch in
der wissenschaftlichen Arbeit im Hinblick auf Literaturrecherchen,
Zusammenfassungen und Mind-Mapping-Prozesse sowie als Codier-Assistenten
den Weg in den Alltag gefunden haben. Gleichzeitig stammen diese Modelle
meist aus der Privatwirtschaft und erheben keinen Anspruch auf
Wissenschaftlichkeit. Ausserdem stellen sie teilweise sog. Black-Boxes
dar, da von den Anbietern nicht durchgehend erklärt werden kann, wie
einzelne Ausgabeinformationen in deren Benutzung zustande kommen. Wir
wissen, dass die Durchbrüche auf diesem Gebiet auf Datenanalysen
zurückgehen, die wiederum auf linguistischen Narrativ-Analysen basieren,
wie in Kapitel 2.4 aufgezeigt wird. Auf der anderen Seite hören wir seit
2005 von einer Replikationskrise, die vielen Wissenschaftlern einiges zu
denken gibt. Auch hier steht der Umgang mit Forschungsdaten im Zentrum
des Diskurses. Die Nicht-Reproduzierbarkeit der präsentierten
Forschungsergebnisse von teilweise mehr als der Hälfte der Studien in
einzelnen medizinischen und humanwissenschaftlichen Fachgebieten wird in
Kapitel 2.1 näher thematisiert.

Ein noch junges Gebiet, das sich annimmt, gleich beiden dieser hier
aufgeführten Problematiken entgegenwirken zu können, sind 'Ausführbare
Bücher' - als neue, reproduzierbare und auf den Fachbegriff von
'Computergestützten Narrativen' zurückgehende, digitale Medien und/oder
Formen der Wissenschaftskommunikation, um deren Sinn und die Entstehung
es in der vorliegenden Thesis geht. Sie versprechen nicht nur die beiden
hier angesprochenen Problemfelder zu lösen, sondern auch mehr Ordnung,
Kollaboration, Transparenz und Handlungsfreiheit in die Welt
reproduzierbarer Wissenschaft zu bringen, was sie auch für die 'Open
Science' Bestrebungen in dem global agierenden Forschungs- und
Universitäten-Netzwerk macht. Während meinem Studium hatte ich die
Möglichkeit, ein 20-tägiges Praktikum im Bibliotheksbereich 'Open
Science' der Universität Bern zu absolvieren und mich den aktuellen
Entwicklungen innerhalb dieses Gebietes, wie etwa dem Bereich
'Data-Stewardship', vertieft anzunehmen. Hier vorliegend findet sich
eine Dokumentation mit ausführlichen Bibliografien, die Studenten,
Forschenden und Promovierenden den Weg in ein nachhaltiges Paradigma der
modernen, reproduzierbaren & datengestützten Wissenschaftskommunikation
ebnen soll, die auf OPEN und FAIR-Prinzipien basiert und sich auf einen
Datenmanagement-Plan stützt. Ich versuche dabei die Thematik durch die
gleichzeitige Beleuchtung von kritischen Stimmen möglichst wertneutral
und dadurch gewissermassen ohne abschliessende Feststellungen auf diese
oder jene Seite zu halten. Vielmehr präsentiere ich eine fundierte
zeitliche Momentaufnahme mit einer grossen Anzahl an referenzierten
Vertiefungsmöglichkeiten auf der Seite des Lesers, der selbst der Stimme
der akademischen Berufung folgt.

> «*The earliest papers \[wissenschaftliche Artikel\] were in some ways
> more readable than papers are today. They were less specialized, more
> direct, shorter, and far less formal. Calculus had only just been
> invented. Entire data sets could fit in a table on a single page. What
> little "computation" contributed to the results was done by hand and
> could be verified in the same way.*»[^1]

Im selben *Atlantic* Artikel von 2018 wird der moderne wissenschaftliche
Artikel für obsolet erklärt und das graphische Benutzer-Interface (GUI)
als für wissenschaftlich-technische Kommunikationen als Nachkommenschaft
vorgeschlagen. Zusammenfassend aus dem Aufsatz *Jupyter, Mathematica,
and the Future of the Research Paper*:

> «0. A graphical user interface (GUI) can facilitate better technical
> writing.
>
> 1\. Wolfram's proprietary notebook showcased innovative technology,
> but decades after its introduction, still has few users.
>
> 2\. Jupyter is a new open-source alternative that is well on the way
> to becoming a standard for exchanging research results.
>
> *Each is spot on. I had to learn the hard way why so many kept their
> distance from Mathematica. Now, I'm much more productive with Jupyter.
> I'm experimenting with, and excited about, its potential as a way to
> write up research results*. »[^2]

Während der Autor Wolframs *Mathematica* Interface für wissenschaftliche
Kommunikation rechtmässig als Eigentümer-Modell einordnet, erkennt er
den von manchen verloren geglaubten Geist der Mitgliedschaft am
wissenschaftlichen Projekt in der Open Source Community wieder, zu der
das Jupyter-Projekt zu zählen ist. Mittlerweile bestehen geschätzt mehr
als 2.5 Millionen in der Jupyter-Programmierumgebung verfasste
Forschungsartikel. Damit ist in den Bibliotheks-, Archiv-, und
Informationswissenschaften die Zeit gekommen, sich aktiv an dem hier
vorliegenden Diskurs zu beteiligen.

Die vorliegende Arbeit in Form eines klassischen PDF-Ausdrucks sowie
einem ausführbaren Jupyter-Notebook mit GitHub Repositorium und eigenem
Online-Webauftritt, findet sich ebenfalls online im 'Berner Open
Repository and Information System' BORIS Portal. Die der Betreuung und
der Studienleitung vorgelegte, als Word-Dokument verfasste
Papierversion, findet ihre Endgültigkeit mit dem Ausdruck des
.doc-Files. Die BORIS-Version liefert einen digitalen Objekt-Identifier
\[DOI\], mit dem die digitale Version des schriftlichen Artikels
versehen wird. Die Jupyter-Notebook Version präsentiert die vorliegende
Abschlussarbeit als offen zugänglichen Code und eigenem
Datenrepositorium, der wissenschaftlichen Welt frei zugänglich und damit
ein weiterlaufendes Projekt darstellend, für alle, die daran teilhaben
möchten.

Die Arbeit liefert einen fundierten historischen Bericht über die
Entstehung der Schrift, über die Buchgeschichte, hin zu den Anfängen des
Internets, bis zu sprechenden Maschinen und bedient sich gleichzeitig
der informationswissenschaftlichen Methode des Literaturberichts, der
eine begleitende dokumentarische Anleitung auf dem Weg zu dieser, auf
nachhaltiger Datenwissenschaft beruhenden Art der
Wissenschaftskommunikation darstellt. Somit ist die Grundlage für eine
kontinuierliche Weiterarbeit an den vorliegenden Themenfeldern gegeben.
Ich hoffe, dem interessierten Leser durch die visuelle Präsentation des
ausführbaren Jupyter-Buches der hier vorliegenden Zahlen,
Schriftzeichen, Links und Literaturverweise Hoffnungen, Chancen und
Möglichkeiten dieser Art der Wissenschaftskommunikation vor Geist und
Auge führen zu können.

# Einleitung

In diesem Kapitel werden einleitend kurz die beiden Problemstellungen
erläutert, die am Anfang der vorliegenden Arbeit stehen. Im weiteren
Verlauf des Textes wird klar, wie diese mit computergestützten
Narrativen \[Computational Narratives\] in Verbindung stehen. Ausserdem
wird einleitend kurz auf die informationswissenschaftliche Methode des
Literaturberichts Bezug genommen, welche hier zusätzlich erweitert wird
anhand der Möglichkeit, die vorliegenden Daten in Form eines
ausführbaren Buches \[Executable Book\] in einer Computerumgebung zu
öffnen, zu reproduzieren, zu erweitern und/oder zu vertiefen. So dient
die vorliegende Arbeit als fundierter Ausgangspunkt für weitreichende
vertiefende Recherchen auf dem Gebiet. Dabei werden auch die in der Open
Science Praxis üblichen Vorteile der angewendeten FAIR- und
Openness-Definitionen sichtbar.

## Die Replikationskrise in den Wissenschaften

Unter dem Stichwort der Reproduzierbarkeitskrise, oder
Reproduktionskrise, ist seit 2005 ein Diskurs im Gange, der auf eine
weitreichende Problematik innerhalb der Wissenschaften schliessen lässt.
Ausgehend von Publikationen wie derjenigen von John P.A. Ioannidis *Why
Most Published Research Findings Are False* [^3]*,* gelang der Diskurs
ab 2015 dann auch in populäre wissenschaftliche Zeitschriften wie
*Nature* und ist seit jeher zu einem Begriff und einem Besorgnis in der
wissenschaftlichen Forschungscommunity geworden.[^4] Dieses
methodologische Problem, das sich durch verschiedene wissenschaftliche
Disziplinen offenbart, insb. den Sozial- und Lebenswissenschaften, geht
u.a. auf die mangelnde Transparenz in der Berichterstattung von Methoden
und Daten, einem Publikationsbias mit der Tendenz, vorwiegend positive
oder statistisch signifikante Ergebnisse zu veröffentlichen sowie
mangelnde Stichprobengrössen und fehlende Anreize für
Replikationsstudien zurück.[^5] Dabei handelt es sich nicht etwa um eine
kleine Anzahl von Studien, die nicht wissenschaftlich reproduziert
werden können, sondern in gewissen Fällen ist gar von mehr als 50%
nicht-reproduzierbarer Forschung die Rede.[^6] Währen im U.S. Diskurs
Lösungen zur Bekämpfung dieser Probleme gefordert werden, z.B. durch
transparenteres Records- und Qualitätsmanagement von den Labordaten[^7],
bestehen in den Bibliothekswissenschaften bereits Lösungsvorschläge und
Richtlinien, die die Reproduzierbarkeit der Forschung durch Open Science
Praktiken, Forschungsdatenmanagement, Daten/Code/Methoden-Transparenz
und Belohnungen für offene Forschungspraxis beinhalten.[^8]

## 2.2 Die Künstliche Intelligenz lernt sprechen {#die-künstliche-intelligenz-lernt-sprechen .unnumbered}

Seit ein paar Jahren hören wir von Durchbrüchen und einem rasanten
Fortschritt auf dem Gebiet der KI-Forschung, insbesondere der grossen
Sprachmodelle \[LLM's\], die sich in der Praxis mittlerweile auch als
schriftstellerische und recherchierende Assistenten für
wissenschaftliche Arbeiten nutzen lassen. Dessen vergewissern kann man
sich relativ schnell durch einen kurzen Test von Modellen wie
Anthropic's Claude Sonnet 3.5, das hochgeladene PDF-Inhalte von
wissenschaftlichen Artikeln innert kürze zu verstehen scheint und davon
Zusammenfassungen liefern kann, Literaturangaben extrahiert und
Vorschläge zu weiterer vorhandener Forschung auf den jeweiligen Gebieten
gibt. Bei Bedarf liefert das Modell auch gleich die Übersetzung der
Inhalte in verschiedenste Sprachen. Des Weiteren bestehen auf grossen
Sprachmodellen aufbauende Recherche-Assistenten wie Elicit, die zu
beliebigen wissenschaftlichen Gebieten über vorhandene Literatur und
Forschung befragt werden können und aktuelle Quellenvorschläge liefern.
Diese Ereignisse auf dem Gebiet der Künstlichen Intelligenz, zu den auf
maschinellem Lernen \[Machine Learning\] basierenden grossen
Sprachmodellen \[Large-Language-Models\] zählen, scheinen sich
sprichwörtlich zu überschlagen und es kann kaum eine Rede sein von einem
sachlichen Überblick durch wissenschaftliche Studien. Das geht zu einem
Teil auch auf die privatwirtschaftlichen Akteure und IT-Firmen zurück,
die sich nicht der Methode der offenen wissenschaftlichen Forschung und
fundierter sachlicher Wissenschaftskommunikation verschrieben sehen. Im
Gegenteil wird von Seiten der grossen IT-Firmen den politischen Akteuren
die fachkundige technologische Kenntnis in dieser Hinsicht abgesprochen
und gleichzeitig wird, nehmen wir das Beispiel USA, aus denselben
Kreisen bereits massiv Lobbyismus in Washington betrieben. Der
alltägliche Endnutzer ist diesen Entwicklungen gewissermassen
ausgesetzt, solange das technologische Know-How und die Einsicht in den
Code nicht nach Open Source Standards offengelegt werden. Diese
Feststellungen können insb. in Kapitel 5 des Stanford University '*AI
Index Report 2024'* vertieft werden.[^9]

Gleichzeitig können diese Durchbrüche auf diesem Gebiet auch positiv
gewertet werden und wie bei den meisten Entwicklungen im Softwarebereich
findet sich neben der eher skrupellosen kapitalistischen Vermarktung
einzelner Anwendungen auch fundierte und offene wissenschaftliche
Forschung, die hinterfragt und nichts für bare Münze nimmt. Um hier zwei
Beispiele aus den Archivwissenschaften anzuführen, die uns einen
aktuellen Einstieg in diese Forschungen geben, lassen sich insbesondere
die immerwährenden Apelle an die Ethik hervorheben, die im Hinblick auf
solch mächtige Instrumente stets präsent sein sollte. Gerade in der
Anwendung von KI-Algorithmen in Archiven beispielsweise, werden dadurch
neue Daten erzeugt und das Berufsbild vom passiven, datenvermittelnden
Archivar wird zum aktiven Akteur innerhalb eines 'Record Continuums':
«Finally, we described the role of AI technologies to open up new types
of archives such as social media collections or diaries, which extend
our current institution-focused ideas of archives. Because of their
scale, these pose distinct challenges in terms of organisation and
access to these collections that can only be solved with further AI
technology development, which sets access to these collections apart
from commercial Application Programming Interfaces (APIs). Only this way
can the core archival mission of building trust in the past record be
sustained.»[^10]

Dadurch, dass es sich in den in diesem Kapitel besprochenen
KI-Werkzeugen um *lernende* Algorithmen handelt, deren Qualität und
Fortschritt v.a. in der Qualität und der Anzahl von vorhandenen Daten
abhängt, ergeben sich diesen Technologien Möglichkeiten der Abnahme von
komplexen Aufgaben, die bisher nur von Menschen ausgeführt werden
konnten. So etwa im Archivbereich: «These \[die Arbeiten\] vary from
providing intelligent support for searching the archives to automate
tedious and time-consuming tasks.  In this article, we focus on
sensitivity review as a practical solution to unlock digital archives
that would allow archival institutions to make non-sensitive information
available. This promise to make archives more accessible does not come
free of warnings for potential pitfalls and risks: inherent errors,
\"black box\" approaches that make the algorithm inscrutable, and risks
related to bias, fake, or partial information. Our central argument is
that AI can deliver its promise to make digital archival collections
more accessible, but it also creates new challenges - particularly in
terms of ethics. In the conclusion, we insist on the importance of
fairness, accountability and transparency in the process of making
digital archives more accessible.»[^11] Ähnliche Feststellungen sind
anhand dieses Abschnittes also gemacht, wie wir sie hier bereits im
Vorwort erwähnt haben. Egal ob naturwissenschaftliche Forschung oder
archivarisches und/oder bibliothekarisches Datenmanagement, der Fokus
findet sich mehr und mehr darin, *wie* mit Information umgegangen werden
soll, ohne dabei unethisch, unwissenschaftlich und rechtsverletzend zu
werden. Die offene Wissenschaft, wie sie unter dem Begriff Open Science
weltweit in die Wissenschaftspraxis gefunden hat, scheint zumindest
einen ersten Ansatz zu liefern und den Diskurs zu vorhandenen Konzepten
zu lenken, die Lösungsansätze und Antworten zu den thematisierten
Problembereichen darstellen können.

Diese Punkte im Bewusstsein haltend, kommen wir nun zu dem Zweig der
Informationswissenschaften und deren methodologischen Grundlagen, um uns
den Möglichkeiten, dem Tätigkeitsbereich sowie der Vielfalt der darin
thematisierten Aufgaben und Arbeitsfelder gewahr zu werden. Es sind die
Informationswissenschaften, die zumindest theoretisch die nötige
fachliche Interdisziplinarität verkörpern, die gebraucht wird, um sich
in einer gemeinsamen Sprache den Fragen zu nähern, wie sie bisher auf
der Abstraktionsebene des vorliegenden Aufsatzes, Textes oder auch der
vorliegenden ausführbaren Datensammlung aufgestellt wurden.

## 2.3 Methodik, oder: Die Informationswissenschaft kommt zur Rettung! {#methodik-oder-die-informationswissenschaft-kommt-zur-rettung .unnumbered}

Innerhalb des Gebietes der Informationsdienstleistungen bildet der
Literaturbericht einen Mehrwertdienst, «der die Literatur zu einem
Thema, meistens freilich eine Auswahl davon, zusammenstellt und wie eine
Sammelrezension referiert, kommentiert und wertet.»[^12] Während diese
Art der Informationsvermittlung, läuft sie über den klassischen Weg von
ausgedruckten Literaturbericht-Artikeln, für den Leser einige Arbeit mit
sich bringt, um die im Literaturbericht präsentierte Literatur ausfindig
zu machen und zu konsultieren, gestaltet sich die moderne,
computergestützte Version davon, wie sie sich hier zumindest in der
computergestützten, ausführbaren Jupyter-Version präsentiert, wesentlich
einfacher. Der Literaturbericht mit einem Datenrepositorium innerhalb
der Jupyter-Notebook Umgebung lässt eine durchgehende Verlinkung
sämtlicher Informationsquellen zu. Sind diese zusätzlich via Open Access
verfügbar und mit einem digitalen Objekt Identifikator \[DOI\]
ausgestattet, lassen sich die rezensierten Artikel mit einem einzelnen
Klick abrufen. In einer idealen Welt wären so durch die Open Science
Standards, die in Kapitel 4 näher besprochen werden, sämtliche
aufeinander Bezug nehmenden wissenschaftlichen Artikel, Monographien und
Beiträge miteinander direkt verlinkt, was einen wesentlichen Fortschritt
in der Transparenz der Forschung darstellen würde. Ausserdem wäre
dadurch Bibliotheken und Archiven viel Zeit-lastige Arbeit
abgenommen.[^13]

An diesem Punkt gilt es sich als einen der Diversität verschriebenen
Bibliotheks-Menschen jedoch auch zu erinnern, dass selbst im Streben
nach mehr Offenheit in der Informationsvermittlung versteckte Bias
lauern könnten: «Bibliothekarische Arbeit wird oft als wertneutral
angesehen, da sie im Gegensatz etwa zu Wissenschaft und Kunst nicht
selbst Inhalte produziert, sondern diese „nur" erschliesst und
zugänglich macht. Dabei spielen jedoch Entscheidungen über Einschluss
beziehungsweise Ausschluss‒ und damit stets auch eine implizite Wertung
der Inhalte ‒ eine zentrale Rolle, besonders in Zeiten knapper
Erwerbungsbudgets oder bei der selektiven Aufnahme von Open
Access-Titeln in den Bibliothekskatalog.»[^14] Die zusammengetragenen
Informationsquellen in der vorliegenden Arbeit wurden somit nicht nur
aufgrund ihrer bereits vorhandenen Open Science Eigenschaften gewählt,
sondern im Zentrum stand der Blick, ganz allgemein die wichtigsten Werke
zu den jeweiligen Teilthemen, vereint in dem grösseren Kontext der
Thesis abzudecken. Während sich der vorliegende ausführbare Text in
einigen Start- und Mittelkapitel der Methode des historisch-kritischen
Fliesstextes mit klassischen Literaturreferenzen bedient, kann ab
insgesamt aus dem Sinn der Sache von der Methodik eines auf einem
computergestützten Narrativ basierenden Literaturberichts gesprochen
werden.

Um hier bereits hier ein Gefühl für die beschriebene
Literaturbericht-Methodik zu erhalten, möchte ich dieses Kapitel anhand
der besprochenen Methodik abschliessen.[^15] Es sind die
Informationswissenschaften, die gleichzeitig im Hintergrund dieser
Arbeit stehen und Lösungen für die einleitend besprochenen Probleme
innerhalb der heutigen Wissenschaftskommunikation sowie den
unüberschaubaren Entwicklungen auf dem Bereich der Künstlichen
Intelligenz bieten können, die wiederum auf die Datenwissenschaften
zurückgehen. Die Grenzen vom wissenschaftlichen Bibliothekar zum
digitalen Archivar zum Informationswissenschaftler und weiter zum
Datenwissenschaftler sind bereits fliessend und werden das
wahrscheinlich immer wie mehr. Nach und nach, mit immer grösserer
Digitalisierung, wird die Relevanz der Computerwissenschaften für alle
diese Tätigkeitsbereiche immer stärker sichtbar:

> «Making use of data is not anymore a niche project but central to
> almost every project. With access to massive compute resources and
> vast amounts of data, it seems at least in principle possible to solve
> any problem. However, successful data science projects result from the
> intelligent application of: human intuition in combination with
> computational power; sound background knowledge with computer-aided
> modelling; and critical reflection of the obtained insights and
> results.»[^16]

Während bereits ein riesiger Literaturkorpus zu den technischen Details
in den Datenwissenschaften besteht, findet sich nur wenig Literatur, die
darauf eingeht, was diese gesellschaftlichen Wandlungen für Bibliotheken
und Informationsspezialisten bedeuten.

> Herndon, Joel, Hrsg. Data Science in the Library: Tools and Strategies
> for Supporting Data-Driven Research and Instruction. London, England:
> Facet Publishing, 2022.

Ein wichtiger Artikel für grosse Digitalisierungsprojekte und die damit
einhergehende Publikation von Kollektionen als Daten-Services für
Gallerien, Bibliotheken, Archive und Museen \[GLAM\], findet sich unter
folgendem DOI-Link:

> Candela, Gustavo, Nele Gabriëls, Sally Chambers, Thuy-An Pham, Sarah
> Ames, Neil Fitzgerald, Katrine Hofmann, u. a. „A Checklist to Publish
> Collections as Data in GLAM Institutions". arXiv, 5. April 2023.
> \<https://doi.org/10.48550/arXiv.2304.02603\>, Stand: 16.07.2024.

Ein Werk aus dem Jahr 2020, das aufkommende Trends und Technologien in
den Bibliotheks- und Informationswissenschaften abdeckt und dabei die
Themenfelder 'Künstliche Intelligenz', Big Data, Distanz-Bildung,
Wissensmanagement und auch Soziale Netzwerke abdeckt, ist als
434-seitiges Hardcover-Handbuch oder als E-Book erhältlich, wobei nur
einzelne Kapitel unter einer Open Access Lizenz direkt abrufbar sind:

> Kaushik, Anna, Ashok Kumar, und Payel Biswas. Handbook of Research on
> Emerging Trends and Technologies in Library and Information Science.
> Advances in Library and Information Science (ALIS) Book Series.
> Hershey, PA: IGI Global, 2019. DOI: 10.4018/978-1-5225-9825-1, Stand:
> 16.07.2024.

Während das *Handbuch Methoden der Bibliotheks- und
Informationswissenschaft: Bibliotheks-, Benutzerforschung,
Informationsanalyse. Handbuch Methoden der Bibliotheks- und
Informationswissenschaft,* erschienen im De Gruyter Verlag, zu Beginn
dieses Kapitels bereits zitiert wurde, existiert vom selben Verlagshaus
das Open Access Grundlagenwerk zu den Informationswissenschaften. Über
mehr als 950 Seiten werden dort Theorien, Methoden, Ausbildungen und die
Institutionalisierung der Informationswissenschaft abgehandelt. Durch
einen Blick in das Inhaltsverzeichnis wird klar, welcher
Mannigfaltigkeit an Themenkomplexen sich die VertreterInnen dieses
Gebiets angenommen haben. Nicht nur die Wissensorganisation in
Bibliotheken, Archiven, Museen und Informationszentren, zu denen die
intellektuelle Indexierung, die Klassifikation, formale Erschliessungen,
Abstracting, Metadaten-Generierung und die Erstellung von Ontologien für
Linked Open Data gehören, sondern auch automatische Sprachverarbeitung,
Informationsvisualisierungen, maschinelle Übersetzungen, Verfahren
wissenschaftlicher Qualitätssicherung, Forschungsdatenmanagement,
Information Retrieval, Sprachmodelle und computervermittelte
Kommunikation sind Teil dieser Wissenschaft, die erst noch definieren
muss, wie jung sie ist oder ob es sie schon immer gab.

> Kuhlen, Rainer, Dirk Lewandowski, Wolfgang Semar, und Christa
> Womser-Hacker, Hrsg. Grundlagen der Informationswissenschaft, 2022.
> Online: \<https://doi.org/10.1515/9783110769043\>, Stand: 16.07.2024.

Die 6100-seitige, amerikanische Version davon wird als sieben Bände
umfassende Enzyklopädie herausgegeben, in der auch die Verbindung der
Linguistik mit der modernen Informationswissenschaft thematisiert wird,
wie sie hier in der vorliegenden Thesis auch speziell herausgehoben ist,
durch eine zusammenfassende historische Abdeckung der Schrift-, Buch-
und Webgeschichte, die im Denken des Autors untrennbar miteinander
verbunden sind.

> McDonald, John D.; Levine-Clark, Michael (Hg.): Encyclopedia of
> Library and Information Sciences, Boca Raton 2019. Online:
> \<https://doi.org/10.1081/E-ELIS4\>, Stand: 16.07.2024.

Um hier nicht weiter durch forschungssichernde Rezensionsverweise noch
das Thema der Zukunft der Informationswissenschaft abzudecken, zu dem
denn auf englischer[^17] sowie als auch auf deutscher[^18] Seite
tatsächlich einige Literatur vorhanden ist, kommen wir, dieses
einleitende Kapitel abschliessend, zum Fachbegriff des
computergestützten Narrativs, das als zentraler Begriff zum vorliegenden
Unterfangen den Weg in den Titel gefunden hat. Es verbindet
interdisziplinär die Sprachwissenschaft mit der Datenwissenschaft und
ist damit Dreh- und Angelpunkt vieler informationswissenschaftlicher
Fragestellungen und Aufgabenbereiche.

## 2.4 Computergestützte Narrative \[Computational Narratives\] {#computergestützte-narrative-computational-narratives .unnumbered}

Ohne hier vertieft in die KI-Forschung springen zu wollen, ist es an
diesem Punkt für unsere Zwecke nötig, kurz auf den Begriff der
computergestützten Narrativen und wie er hier verstanden wird,
einzugehen. Ich stiess das erste Mal bewusst auf diesen Begriff durch
die Lektüre des Textes *Project Jupyter: Computational Narratives as the
Engine of Collaborative Data Science,* der im April 2015 als
Fördermittel-Antrag formuliert wurde. Computer seien gut im Konsumieren,
in der Produktion und im Prozessieren von Daten. Menschen hingegen,
prozessieren die Welt durch Narrative. Vgl. dazu beispielsweise:

> Piper, Andrew, Richard Jean So, und David Bamman. „Narrative Theory
> for Computational Narrative Understanding". In *Proceedings of the
> 2021 Conference on Empirical Methods in Natural Language Processing*,
> herausgegeben von Marie-Francine Moens, Xuanjing Huang, Lucia Specia,
> und Scott Wen-tau Yih, 298--311. Online and Punta Cana, Dominican
> Republic: Association for Computational Linguistics, 2021.
> \<https://doi.org/10.18653/v1/2021.emnlp-main.26\>.

Und:

> Riedl, Mark O. „Computational Narrative Intelligence: A Human-Centered
> Goal for Artificial Intelligence". arXiv, 20. Februar 2016.
> \<https://doi.org/10.48550/arXiv.1602.06484\>.

Damit die Daten und deren computergestützte Prozessierung und
Visualisierung für Menschen brauchbar werden, müssen diese in ein
Narrativ eingebettet werden, in ein computergestütztes Narrativ -- das
eine Geschichte erzählt, für ein bestimmtes Publikum und einen
bestimmten Kontext. Diese fundamentalen Aspekte probieren
computergestützte Narrative zu adressieren. Erstens sollte ein einziges
computergestütztes Narrativ eine grosse Anzahl von Kontexten und
Audienzen abdecken können. Zum Beispiel macht ein biomedizinischer
Forscher zuerst eine statistische Analyse und Datenvisualisierungen für
eine höchst technische Studie, die in einem akademischen Journal
veröffentlicht werden soll. Mit der Zeit hält jedoch das selbe
Individuum Vorträge für andere Forscher oder auch nicht-gebietskundige
Audienzen. Dann könnte es auch wichtig werden, nicht-codierenden
Laborforschenden die selben statistischen Datenanalysen und
Datenvisualisierungen zugänglich machen zu können, in einem
vereinfachten graphischen Interface. Die Kernaspekte des
computergestützten Narrativs bleiben über alle diese verschiedenen
Anwendungen die gleichen. Zweitens müssen diese computergestützten
Narrative reproduzierbar sein. Andere Leute und der Autor mit
inbegriffen, müssen auch sechs Monate nach dem Erscheinen der Arbeit
nachvollziehen können, was mit dem Code, den Daten und dem Narrativ
gemacht wurde, um die Forschungen nachhaltig reproduzieren und darauf
aufbauen zu können. Die Reproduzierbarkeit stellt schon lange die
Fundation der wissenschaftlichen Methode dar, wobei die
Datenwissenschaft in dieser Hinsicht neue Herausforderungen mit sich
bringt und auch fragen lässt, wie diese in anderen Gebieten wie der
Festsetzung von politischen Richtlinien oder Wissenschaftsjournalismus
erfüllt werden können. Drittens können computergestützte Narrative
kollaborativ erstellt werden. Mehrere Individuen können am gleichen
Code, den gleichen Daten und den gleichen Narrativen arbeiten. Die
Kollaborationsfähigkeit ist fast in allen Kontexten gegeben im Hinblick
auf computergestützte Narrative, sei das zwischen zwei Postdocs und
einem Professor in der gleichen Forschungsgruppe, zwischen
Schriftsteller, Editoren und graphischen Designern von News-Seiten,
zwischen Datenwissenschaftlern und Unternehmensstrategen in grossen
Internet-Firmen, oder zwischen einem Lehrer und seinen Schülern in einem
Universitätszimmer. All dies möchte das Jupyter-Projekt, das zuerst
IPython hiess, mit den Open Source Software Werkzeugen für interaktives
und forschendes, computergestütztes Erzählen erreichen. Diese
Software-Entwicklungen in der Umgebung vom Jupyter-Projekt, in denen
sich eine grosse Anzahl von Programmiersprachen wie Python, Julia, R
etc. anwenden lassen, befindet sich in stetiger Entwicklung und es
erscheinen regelmässig Updates für die bereits vorhandenen
Nutzer-Umgebungen.[^19]

Im selben, hier auf Deutsch übersetzten Text wird eine weitere gängige
Definition des Begriffs des computergestützten Narrativs geliefert:

> «The problem the Jupyter project tackles is precisely this
> intersection: creating tools to support in the best possible ways the
> computational workflow of scientific inquiry, and providing the
> environment to create the proper narrative around that central act of
> computation. We refer to this as Literate Computing, in contrast to
> Knuth's concept of Literate Programming, where the emphasis is on
> narrating algorithms and programs. In a Literate Computing
> environment, the author weaves human language with live code and the
> results of the code, and it is the combination of all that produces a
> computational narrative.»[^20]

Die Hauptanwendung, das Jupyter-Notebook, ist eine Web-basierte,
interaktive Computer-Plattform, die es den Nutzern erlaubt,
computergestützte Narrative zu verfassen, die Live-Code, Formeln,
narrativer Text, interaktive, graphische Interfaces und andere digitale
Medien miteinander zu kombinieren. Diese Dokumente liefern die
kompletten Aufzeichnungen der gemachten computergestützten Arbeiten und
lassen sie unmittelbar in verschiedenste Formate wie HTML, PDF, Word,
LaTeX etc. konvertieren. Das kann auch heissen, dass die
Jupyter-Notebooks unmittelbar in akademische Publikationen,
Blog-Artikel, Bücher, journalistische Artikel, technische
Dokumentationen, Regierungsreporte, Finanzierungsanfragen und
kommerzielle Anwendungen konvertiert werden können. Je nach Gebrauch
lassen sich daraus Live-Demonstrationen, Webseiten, Präsentationen und
weiteres für verschiedenste Audienzen erstellen. Zudem sind
Jupyter-Notizbücher maschinenlesbar und erfüllen die FAIR-Kriterien der
Open Science Community.

Um sich ausserhalb des Kontextes vom Jupyter-Projekt in
computergestützte Narrative zu vertiefen, empfehlen sich folgende zwei
Beiträge:

> Ranade, Priyanka, Sanorita Dey, Anupam Joshi, und Tim Finin.
> „Computational Understanding of Narratives: A Survey". *IEEE Access*
> 10 (2022): 101575--94.
> \<https://doi.org/10.1109/ACCESS.2022.3205314\>.
>
> Mani, Inderjeet. „Computational Narratology". In *Handbook of
> Narratology*, 84--92. De Gruyter, 2014.
> \<https://doi.org/10.1515/9783110316469.84\>.

# Historische Hintergründe

## 3.1 Die Schriftgeschichte {#die-schriftgeschichte .unnumbered}

Erst kürzlich erschien im *Cambridge Archeology Journal* ein Artikel,
der die Datierung des ersten geschriebenen Wortes von 5\'000 Jahren
zurück bis auf 20\'000 Jahre vor unserer Zeit datiert, nämlich in die
Eiszeit. Ein Katalog von 862 gezeichneten Tierrepräsentationen in den
Höhlen von Frankreich und Spanien wurde ergänzt mit fast ebenso vielen
Punkten, Schrägstrichen und y-förmigen Zeichen, die auf monatliche
Assoziationen hinweisen, wann die Fortpflanzungszyklen dieser Tiere
stattfinden. Da es sich dabei um Assoziationen handelt, die noch nicht
wirklich dem entsprechen, was wir von Handschrift erwarten würden, wird
von einem «Proto-Schriftsystem» gesprochen.[^21] Die Schrift als ein
System grafischer Zeichen, die die Einheiten einer bestimmten Sprache
darstellen, geht zurück auf drei unabhängig voneinander vermutete
Entwicklungen in Mesopotamien, dem heutigen Irak, in China und in
Mesoamerika und wird auf ca. 3000 v. Chr. datiert. Als Vorläufer dieser
Keilschriften gelten Systeme, die der Aufzeichnung und der Zählung von
Waren und Tonmünzen galten. Die Entwicklung der Schrift von den
Spielsteinen über die Piktographie und das Silbenalphabet bis hin zum
heutigen Alphabet veranschaulicht die Informationsverarbeitung zur
Bewältigung immer grösserer Datenmengen in immer grösserer Abstraktion.
Auf die gleiche Weise wie ein Token heute in der Nutzung von künstlicher
Intelligenz für eine fundamentale Einheit von Daten steht, die von
natürlichen Sprachprozessoren verarbeitet werden in maschinellen
Lernsystemen, stehen Token in Form von Kugeln, Kegeln, Scheiben,
Zylinder etc. für als der Schrift vorläufige Artefakte. Einige solcher
Funde werden in der Archäologie bis auf 8000 v. Chr. datiert. Die
Schaffung phonetischer Zeichen, die die Laute der Sprache repräsentieren
und somit die gesprochene Sprache nachzuahmen versuchen, wird dann unter
dem Fachbegriff der Logographie v.a. in Bezug auf die Entwicklungen in
Mesopotamien untersucht. Als dritte Phase der Schriftgeschichte gilt die
Entwicklung des Alphabets um 1500 v. Chr. im Alten Orient, wo im
heutigen Libanon das erste proto-sinaitische Alphabet entstand. Als
System basiert es auf Akrophonie, kombiniert mit konsonantischen
Sprachlauten. Dieser Übergang von der Keilschrift zum Alphabet vollzog
sich über mehrere Jahrhunderte. So diktierten im sieben Jhdt. v. Chr.
die assyrischen Könige beispielsweise ihre Erlasse noch zwei Schreibern.
Der erste schrieb Akkadisch in Keilschrift auf eine Tontafel, der zweite
Aramäisch in einer kursiven Buchstabenschrift auf eine Papyrusrolle.
Perfektioniert wurde das Alphabet dann von den alten Griechen, die es
mit Vokalen für Sprachlaute ergänzten. Da das Alphabet nur einmal
erfunden wurde, stammen alle Alphabete der Welt, einschliesslich Latein,
Arabisch, Hebräisch, Amharisch, Brahmanisch und Kyrillisch vom
Proto-Sinaitischen ab. Das heute in der westlichen Welt verwendete
lateinische Alphabet ist der direkte Nachkomme des etruskischen
Alphabets. Es geht somit direkt auf die Etrusker zurück, die die heutige
Provinz der Toskana in Italien bewohnten und dort das griechische
Alphabet übernahmen und abänderten, bis es zu demjenigen der Römer
wurde.[^22] Zu erwähnen in dieser Hinsicht ist der Stein von Rosetta aus
Memphis, Ägypten, der auf das Jahr 196 v. Chr. zurückgeht und im Auftrag
des Königs Ptolemaios V. Epiphanes, einem Nachfolger von Alexander dem
Grossen, ein Synodaldekret enthält, verfasst in Hieroglyphen,
demotischer Schrift und altgriechischer Schrift. Er stellte für die
westliche Welt ein entscheidendes Puzzlestück zu der Entzifferung der
ägyptischen Schriftzeichen dar.[^23] Die chinesische Schrift musste nie
entziffert werden, weil sich die Zeichen in den 3400 Jahren ihres
Bestehens kaum verändert haben. Die phonetischen Glyphen der
mesoamerikanischen Maya bewahrten die von den Olmeken im vorherigen
Jahrtausend eingeführte Symbolik. Wie Marshall McLuhan definierte,
bestehen diese Alphabete aus semantisch bedeutungslosen Buchstaben, die
semantisch bedeutungslosen Lauten entsprechen. Das Alphabet brachte die
Datenverarbeitung somit zu einer endgültigen zweistufigen
Abstraktion.[^24]

Gerade im Hinblick auf Forschungen in Verbindung mit modernen
Wissenschaftskommunikation, computergestützten Narrativen und
Wissensrepräsentationen sollte m.E. der historische Blick, wie er hier
nur kurz ansatzweise skizziert werden kann, nie vergessen gehen. Alles
andere wäre, wie man so schön sagt, den Wald vor lauter Bäumen nicht
mehr sehen zu können.

## 3.2 Die Buchgeschichte {#die-buchgeschichte .unnumbered}

Aufbauend auf der Schriftgeschichte lässt sich die Buchgeschichte
skizzieren und eine Überleitung zu dem für uns relevanten
computergestützten, wissenschaftlichen Aufsatz denken.

Als Vorläufer der Buchgeschichte[^25] gelten, in Bezug auf die uns hier
vorliegenden Informationen, die Höhlenzeichnungen, in Stein gemeisselte
Hieroglyphen, Runen und anderweitige Schriftzeichen, gefolgt von der
Entwicklung des Papyrus im alten Ägypten, die auf ca. 2500 v. Chr.
datiert wird.[^26] In China hatten die ersten Bücher die Form von
Bambus- oder Holzstreifen, die mit Schnüren zusammengebunden waren und
auf die Shang-Dynastie (1600-1046 v. Chr.) zurückgehen. Die Erfindung
des Papiers durch Cai Lun im Jahr 105 n. Chr. revolutionierte die
schriftliche Kommunikation, da es ein billigeres und praktischeres
Medium darstellte.[^27] Als weiteres wichtiges Medium der Buchgeschichte
gilt der Kodex, unter dem ein Stapel beschrifteter Holz- oder
Wachstafeln verstanden wird. Die Geschichte des Kodex, die auch stark
mit der Geschichte religiöser Überlieferungen zusammenhängt,
unterscheidet Kodizes aus Papyruslagen, Kodizes aus Pergamentseiten,
Kodizes aus Papierseiten sowie Kodizes aus Seidenpapier. Diese
Entwicklungsgeschichte beginnt spätestens im 8 Jhdt. v. Chr. mit den
Holztafeln und zieht sich bis hinein ins Mittelalter, auf das die
Tradition des Manuskriptes zurückgeht.[^28] Die Manuskriptgeschichte
wiederum geht zurück auf das mittelalterliche Klosterleben ab dem 11.
Jhdt. n. Chr., wo Mönche oftmals mit der Handschriftlichen Kopie und der
damit einhergehenden Buchproduktion beschäftigt waren.[^29] Etwa
zweihundert Jahre nach dem Entstehen der ersten Universitäten in Europa
kommt es mit der von Johannes Gutenberg erfundenen Druckerpresse und der
Verwendung von beweglichen Metalllettern ab ca. 1450 zu einer
Medienrevolution in der Ausbreitung des Buchdrucks.[^30] Diese
Entwicklungen stehen dann auch am Anfang der Renaissance und dem
Aufkommen der modernen Wissenschaften, der naturwissenschaftlichen
Revolution in der frühen Neuzeit Europas.[^31] Vergleiche zu diesen
Ausführungen auch das Grundlagenwerk von der Cambridge University Press:

> Howsam, Leslie, Hrsg. *The Cambridge Companion to the History of the
> Book*. Cambridge Companions to Literature. Cambridge: Cambridge
> University Press, 2014. \<https://doi.org/10.1017/CCO9781139152242\>.

Im deutschen Sprachraum empfiehlt sich für interessierte der
Buchgeschichte folgendes Werk, in dem sich auch ein Kapitel zum Übergang
ins elektronische Medium findet:

> Janzin, Marion, und Joachim Güntner. *Das Buch vom Buch: 5000 Jahre
> Buchgeschichte*. Schlütersche, 2007.

Im selben Werk wird auf S. 474 die Haltbarkeit von Informationen nach
Trägermedien aufgeführt. Während bei der Felsmalerei die Angabe ca.
20\'000 Jahre zu lesen ist, werden bei den Steintafeln ca. 10\'000 Jahre
angegeben, beim Papyrus ca. 2000 Jahre, beim Pergament ca. 1\'000 Jahre,
beim entsäuerten Papier ca. 300 Jahre, bei der Magnetplatte ca. 50-100
Jahre und beim elektronischen Chip nur ca. 20 Jahre angegeben. Die
Haltbarkeit von Datenbanken im Internet ist theoretisch unendlich, wobei
diese Technologie einem stetigen Wandel ausgesetzt bleibt. Es lässt sich
bisher nur spekulieren, ob wir es bei diesem Medium also tatsächlich
auch mit einer langlebigen Entwicklung zu tun haben, spricht man in
Jahrhunderten oder Jahrtausenden. Trotz allem sieht sich der
realistische Blick erst am Anfang dieser Entwicklungen. Der grosse
Vorteil dieses neuen Mediums ist jedenfalls die Möglichkeit der
einfachen Vervielfältigung der vorhandenen Informationen sowie deren
unmittelbare Teilbarkeit. Überlegungen bezüglich der Haltbarkeit von
digitalen Informationen auf einer physischen Ebene könnten
beispielsweise auch die Thematik der Dezentralisierung von Daten
innerhalb eines Blockchain-Paradigmas beinhalten. In diesem Fall würden
die Informationen unabhängig von einzelnen zentralisierten Datenbanken
so lange bestehen bleiben, wie es Datenbanken gibt, die die
nicht-manipulierbaren Datenketten bestätigen. So wird bei dieser
Technologie von einem verteilten Datenbankmanagementsystem gesprochen.

Bezüglich dem unter dem Begriff der Digitalisierung thematisierten
Übergang von Printmedien hin zu elektronischen Medien empfiehlt sich für
weitere Recherchen ein Ausgehen von den folgenden beiden Beiträgen.
Natürlich handelt es sich dabei um ein riesiges Gebiet, in dessen Mitte
sich auch die vorliegende Arbeit befindet und einen eigenen,
pragmatischen Beitrag dazu zu leisten versucht. Weitere Texte zu dieser
Thematik, bezogen auf konkretere Teilaspekte dieses Übergangs von Print
zu Elektronik, finden sich im Verlauf der vorliegenden Ausführungen. In
Bezug auf die Digitalisierung im Zusammenhang mit der
Bibliotheksgeschichte:

> Kumar, Bhardwaj, Raj. *Digitizing the Modern Library and the
> Transition from Print to Electronic*. IGI Global, 2017.
>
> Thompson, John B. *Book Wars: The Digital Revolution in Publishing*.
> Polity Press, 2021.

Computergestützte Narrative in Form von ausführbaren Büchern in einem
Open Science Kontext und Umfeld versprechen zumindest auf einer
theoretischen Ebene eine Vielfältigkeit von pragmatischen
Lösungsvorschlägen in Bezug auf diesen grösseren digitalen Wandel
innerhalb der Wissenschaftskommunikation. In den kommenden Jahren wird
sich zeigen, ob sich diese Art der Text- und Datenvisualisierung in
einem globalen Masse wird durchsetzen können und wie in der Bibliotheks-
und Archivwissenschaft damit einen Umgang gefunden wird. Denn bisher
finden sich noch keine abschliessenden Lösungen, wie denn diese
computergestützten, wissenschaftlichen Ansätze den Weg in die
elektronischen & universitären Bibliotheksverzeichnisse finden könnten.
Wir haben es also noch mit einer äusserst jungen Entwicklung zu tun, die
erst gerade dabei ist, ihren Weg in einen grösseren, das Gebiet des
Wissensmanagement betreffenden Diskurs zu finden.

## 3.3 Die Geschichte des Web {#die-geschichte-des-web .unnumbered}

Die Geburt des Internets, ohne das die heutige Welt nur noch schwer
interpretiert werden kann, hängt kulturhistorisch stark mit der
Bibliotheksgeschichte zusammen.[^32] Vor dem Hintergrund sich stark
durch Querverweise und Marginalien auszeichnenden mittelalterlichen
Texten (z.B. der Talmud, oder der King-James Bibel), frühneuzeitlichen
Drucken, die Konkordanzen durch Verweissysteme herstellen (z.B. die
Stephanus-Paginierung der *Platonis opera quae extant omnia*) sowie die
Zettelkästen von Paul Otlet, einem Pionier der modernen
Dokumentationswissenschaft, und denjenigen vom unverzichtbaren
Soziologen Niklas Luhmann, lässt sich über den Begriff des Hypertext
nachdenken. Bereits 1945 wurde von Vannevar Bush über vernetzte Formen
von Wissensmanagement und *information retrieval* publiziert, anhand des
Gedankenexperiments der Memex-Maschine. Weiter realisierte anfangs der
1960er Jahre Douglas C. Engelbart Bush im Rahmen seines *Augmented*
Projekts ein Computersystem mit einem digitalen Hypertext, das den
Menschen befähigen sollte, seine Gedanken verlinkt abspeichern,
modifizieren und annotieren zu können. Der Begriff des *Hypertext* wurde
dann 1965 von Theodor Holm Nelson in seinem Aufsatz *A File Structure
for the Complex, the Changing and the Indeterminate* eingeführt.
«'Hyper' ist dem mathematischen und naturwissenschaftlichen Jargon
entlehnt und bedeutet ›erweitert und generalisiert‹. Nelson erklärt:
"Hypertext can include sequential text, and is thus the most general
form of writing." Er fasst das Konzept weiter zusammen: "Well, by
›hypertext‹ I mean non-sequential writing -- text that branches and
allows choices to the reader, best read at an interactive display."
Nelson prägte auch die Begriffe Hypermedia und Hyperfilm. Letzterer
konnte sich allerdings nie durchsetzen. Sein Hypertext-Konzept versucht
Nelson bis heute in seinem Projekt Xanadu zu realisieren. Ein besonderes
Merkmal davon ist der Verzicht auf jede Redundanz: Ein digitales Objekt
soll genau einmal gespeichert, aber universell adressierbar sein
('Xanalogical Storage'). So würde für universelle Aktualisierung von
Inhalten gesorgt und gleichzeitig die Grundlage für ein
Abrechnungssystem (mit Micropayment), vor allem für Kulturgüter,
geschaffen. Die an verschiedenen Stellen (in Hypertext-Dokumenten)
repräsentierten Inhalte bleiben per Transklusion miteinander
verbunden.»[^33]

Im März 1989 sowie zusätzlich im Mai 1990 folgte dann Tim Berners-Lee's
historische Arbeit *Information Management: A Proposal* am CERN in der
Schweiz, das ein «hypertext project» namens «WorldWideWeb» beschreibt,
in dem ein «web» von «hypertext documents» in «browsern» abgerufen
werden konnte.[^34] Die damit einhergehende weltweit erste Webseite
info.cern.ch ist auch heute noch abrufbar. «The WorldWideWeb (W3) is a
wide-area hypermedia information retrieval initiative aiming to give
universal access to a large universe of documents.» Ist der erste
definierende Satz auf dieser Webseite. Prominent findet sich dann auch
gleich ein Link zur World-Wide Web Bibliography und den Verweisen zu
Berner-Lees informationstheoretischen Arbeiten zur umgesetzten
W3-Infrastruktur. Noch auf der selben Seite findet sich dann auch ein
UDI-Proposal und Gedanken zum «World-Wide Web Book».[^35] Prominent auch
die 1984 Auszeichnungssprache LaTeX, die im Hinblick auf «Executable
Books» heute immer noch eine zentrale Rolle einnimmt.[^36] Während UDI
*Universal Document Identifiers* bezeichnet, haben sich heute in der
wissenschaftlichen Landschaft eher digitale Objekt-Identifikatoren
durchgesetzt, die in der vorliegenden Arbeit in Kapitel 4.1 behandelt
werden. Wichtig ist in Bezug auf die Geschichte des Web, dass diese mit
dem Hypertext einhergeht, also der HTML-Sprache. Ausführbare Bücher
innerhalb der Jupyter-Umgebung können ohne Probleme in HTML-Code
konvertiert werden und können anhand dieser Möglichkeit direkt als
Webseite veröffentlicht werden, wie ich es auch mit dem vorliegenden
Text gemacht habe. Hier eine kleine Hyptertext-Bibliographie zur
Vertiefung der Thematik im Hinblick auf unsere Themenbereiche:

> Bernstein, Mark. „On hypertext narrative". In *Proceedings of the 20th
> ACM conference on Hypertext and hypermedia*, 5--14. HT '09. New York,
> NY, USA: Association for Computing Machinery, 2009.
> \<https://doi.org/10.1145/1557914.1557920\>.
>
> Krameritsch, Jakob. *Geschichte(n) im Netzwerk: Hypertext und dessen
> Potenziale für die Produktion, Repräsentation und Rezeption der
> historischen Erzählung*. Medien in der Wissenschaft, Band 43. Münster:
> Waxmann, 2007.
>
> Wachter, Christian. *Geschichte digital schreiben: Hypertext als
> non-lineare Wissensrepräsentation in der Digital History*. 1. Aufl.
> Bd. 2. Geschichtstheorie. Bielefeld, Germany: transcript Verlag, 2021.
> \<https://doi.org/10.14361/9783839458013\>.
>
> Lobin, Henning. „Intelligente Dokumente. Linguistische Repräsentation
> komplexer Inhalte für die hypermediale Wissensvermittlung". In *Text
> im digitalen Medium. Linguistische Aspekte von Textdesign,
> Texttechnologie und Hypertext Engineering*, 155--77. Westdeutscher
> Verlag, 1999.
> \<https://ids-pub.bsz-bw.de/frontdoor/index/index/docId/7630\>.

## 3.4 Linked Open Data {#linked-open-data .unnumbered}

Das semantische Web und die Begrifflichkeit von Linked Open Data gehen
ebenfalls auf Tim Berners-Lee und seine Arbeit im W3C (World Wide Web
Consortium) zurück. Im Internet frei verfügbare Daten ergeben zusammen
ein weltweites Netz, das auch als 'Linked Open Data Cloud', 'Giant
Global Graph' oder 'Knowledge Graph' bezeichnet wird. Dieses gilt dann
auch als das Konzept eines auf Maschinenlesbarkeit basierenden World
Wide Webs (Web 3.0). Es folgt den Idealvorstellungen des Gremiums zur
Standardisierung des WWW und Tim Berners-Lee und kann als offenes
Forschungsgebiet bezeichnet werden. Wikidata, DBpedia und GeoNames
können als Projekte genannt werden, die auf diesen Technologien beruhen.
In den Bibliotheks-, Archiv-, und Informationswissenschaften stellt
'Linked Open Data' weiterhin ein oftmals erwähntes Themenfeld dar,
deshalb habe ich hier der Vollständigkeit halber eine Literaturliste
zusammengestellt, die zu vertiefenden Informationen dazu führt:

Rahaman, Wasim. „Semantic Web-Linked Data and Libraries". \<DOI:
10.4018/978-1-7998-

8051-6.ch009\>. Zugegriffen 22. Juli 2024.

Carlson, Scott, Cory Lampert, Darnelle Melvin und Anne Washington.
*Linked Data for the*

*Perplexed Librarian*. ALCTS Monograph. Chicago: ALA Editions, 2020.

Fensel, Dieter. *Spinning the Semantic Web: Bringing the World Wide Web
to Its Full Potential*.

Cambridge, Mass.: MIT Press, 2005.

Fensel, Dieter, Umutcan Şimşek, Kevin Angele, Elwin Huaman, Elias Kärle,
Oleksandra

Panasiuk, Ioan Toma, Jürgen Umbrich, und Alexander Wahler. *Knowledge
Graphs:*

*Methodology, Tools and Selected Use Cases*. Cham: Springer
International Publishing,

2020\. \<https://doi.org/10.1007/978-3-030-37439-6\>.

Stuckenschmidt, Heiner, und Frank Van Harmelen. *Information Sharing on
the Semantic Web*.

Berlin, Heidelberg: Springer, 2005. \<https://doi.org/10.1007/b138282\>.

Allemang, Dean, und Jim Hendler, Hrsg. „Semantic Web for the Working
Ontologist (Second

> Edition)", iv. Boston: Morgan Kaufmann, 2011.
> \<https://doi.org/10.1016/B978-0-12- 385965-5.10021-4\>.

Lu, Liyang. „Introduction to the Semantic Web and Semantic Web
Services". Routledge &

> CRC Press. Zugegriffen 21. Juli 2024.
> \<https://www.routledge.com/Introduction-to-the-Semantic\--Web-and-Semantic-Web-Services/Yu/p/book/9780367388973\>.

# Open Science in der Praxis

Open Science kann als Überbegriff von verschiedenen Initiativen gedeutet
werden, die sich auf eine offene Wissenschaft beziehen. Das Schweizer
Staatssekretariat für Bildung, Forschung und Innovation sieht darin
einen der wichtigsten Trends im globalen Wissenschaftssystem.[^37] In
Europa fanden 2018 und 2021 in Frankreich zwei Konferenzen statt, um
Orientierungspunkte für eine gesteigerte Qualität, Transparenz,
Reproduzierbarkeit und Inklusivität der Wissenschaften zu finden:

> Open Science European Conference. *Proceedings of the Paris Open
> Science European Conference : OSEC 2022*. *Proceedings of the Paris
> Open Science European Conference : OSEC 2022*. Laboratoire d'idées.
> Marseille: OpenEdition Press, 2022.
> \<https://books.openedition.org/oep/15829\>.

Als einleitende & zu diesem Zeitpunkt aktuelle Werke empfiehlt sich die
Lektüre des philosophischen Werks von Sabina Lionelli sowie das
historisch fundierte Grundlagenwerk von Frank Miedema, in dem viele
konkrete Beispiele aus dem wissenschaftlichen Alltag zu finden sind und
wie diese mit der Idee von Open Science zusammenhängen:

> Leonelli, Sabina. *Philosophy of Open Science*. Elements in the
> Philosophy of Science. Cambridge: Cambridge University Press, 2023.
> \<https://doi.org/10.1017/9781009416368\>.
>
> Miedema, Frank. *Open Science: The Very Idea*. Dordrecht: Springer
> Netherlands, 2022. \<https://doi.org/10.1007/978-94-024-2115-6\>.

An der Universität Bern gehört das Open Science-Team dem gleichnamigen
Bibliotheksbereich an. Es deckt u.a. die Aufgabenbereichr Kurse &
Schulungen, das BORIS Portal als Datenrepositorium der Universität Bern,
den Open Access Bereich, das Bern Open Publishing, OS-Initiativen, die
Langzeitarchivierung von Forschungsdaten sowie die digitalen
Identifikatoren ab, zu denen sich hier zusätzlich detaillierte
Unterkapitel finden. Um ein Bild für den Zusammenhang von Open Science
und Bibliothekswesen zu erhalten, hier zwei Literaturreferenzen:

> .
>
> Gerdes, Thomas. *Die Open-Science-Bewegung und ihre Bedeutung für die
> wissenschaftlichen Bibliotheken. Eine Analyse von Positionspapieren
> und Entwicklungsperspektiven*, 2018.
> \<https://doi.org/10.18452/18983\>.
>
> Vancauwenbergh, Sadia. *Digital Libraries - Advancing Open Science*,
> 2021. \<https://doi.org/10.5772/intechopen.87798\>.

Im Zusammenhang mit Open Access Initiativen, die neben den Bereichen
'Open Educational Resources', 'Open Peer Review', 'Open Methodology',
'Open Source' sowie 'Open Data' einen der sechs Grundpfeiler dieses
Bereichs abdecken, lassen sich Stephen Pinfields Bücher anführen, die
insbesondere den praktischen Teil von angewandter und offener
Wissenschaft thematisieren, wie er hier in der vorliegenden
Abschlussarbeit auch erfüllt sein will.

> Pinfield, Stephen. *Achieving Global Open Access: The Need for
> Scientific, Epistemic and Participatory Openness*. London: Routledge,
> 2024. \<https://doi.org/10.4324/9781032679259\>.
>
> Pinfield, Stephen, Simon Wakeling, David Bawden, und Lyn Robinson.
> *Open Access in Theory and Practice: The Theory-Practice Relationship
> and Openness*. London: Routledge, 2020.
> \<https://doi.org/10.4324/9780429276842\>.

Ausserdem findet sich hinsichtlich dieser Bestrebungen innerhalb der
Wissenschaftskultur auch Beiträge, die sich mit dem Aspekt
Gesellschaft-Wissenschaft befassen, wie etwa folgender Artikel:

> Lakomý, Martin, Renata Hlavova, und Hana Machackova. „Open Science and
> the Science-Society Relationship". *Society* 56 (15. Juni 2019):
> 1--10. \<https://doi.org/10.1007/s12115-019-00361-w\>.

Im Hinblick auf die Wissenschaftskommunikation und auch in Bezug auf die
'Digital Republic', wie die digitalisierte Gesellschaft manchmal genannt
wird, werden hier weitere Artikel festgehalten, die bereits eine etwas
spezialisiertere Auseinandersetzung mit der Open Science Thematik
zulassen. So wird die Wissensproduktion innerhalb von Open Science auch
in epistemologischen und die Ethik betreffenden Diskursen besprochen,
bis hin zu Entwürfen von kollaborativen, wissenschaftlichen Ökosystemen.

> Scientific And Technical Information. *White Paper --- Open Science in
> a Digital Republic*. OpenEdition Press, 2016.
> \<https://doi.org/10.4000/books.oep.1635\>.
>
> Grand, Ann. „Open science". *Journal of Science Communication* 14 (15.
> Dezember 2015). \<https://doi.org/10.22323/2.14040302\>.
>
> Hofmann, Bjørn. „Open Science Knowledge Production: Addressing
> Epistemological Challenges and Ethical Implications". *Publications*
> 10 (14. Juli 2022): 24.
> \<https://doi.org/10.3390/publications10030024\>.
>
> Thibault, Robert T., Olavo B. Amaral, Felipe Argolo, Anita E.
> Bandrowski, Davidson Alexandra R, und Natascha I. Drude. „Open Science
> 2.0: Towards a Truly Collaborative Research Ecosystem". *PLOS Biology*
> 21, Nr. 10 (19. Oktober 2023): e3002362.
> \<https://doi.org/10.1371/journal.pbio.3002362\>.

Abschliessend führe ich hier zwei Literaturauswertungen von Open Science
Praktiken und deren Applikation in Forschungsprozessen an, mit denen
sich auch Rückschlüsse auf Ausbildungsfragen innerhalb der modernen
Wissenschaften ziehen lassen.

> Stracke, Christian. „Open Science and Radical Solutions for Diversity,
> Equity and Quality in Research: A Literature Review of Different
> Research Schools, Philosophies and Frameworks and Their Potential
> Impact on Science and Education", 17--37, 2020.
> \<https://doi.org/10.1007/978-981-15-4276-3_2\>.
>
> Zarghani, Maryam, Leila Nemati-Anaraki, Shahram Sedghi, Abdolreza
> Noroozi Chakoli, und Anisa Rowhani-Farid. „The Application of Open
> Science Potentials in Research Processes: A Comprehensive Literature
> Review". *Libri* 73, Nr. 2 (1. Juni 2023): 167--86.
> \<https://doi.org/10.1515/libri-2022-0007\>.

## FAIR-Prinzipien & Digitale Objekte

Unter den FAIR-Prinzipien versteht man die 2016 im Aufsatz *The FAIR
Guiding Principles for Scientific Data Management and Stewardship*
veröffentlichten Leitlinien für die Beschreibung, Speicherung und
Veröffentlichung wissenschaftlicher Daten.

> Wilkinson, Mark D., Michel Dumontier, IJsbrand Jan Aalbersberg,
> Gabrielle Appleton, Myles Axton, Arie Baak, Niklas Blomberg, u. a.
> „The FAIR Guiding Principles for Scientific Data Management and
> Stewardship". *Scientific Data* 3, Nr. 1 (15. März 2016): 160018.
> \<https://doi.org/10.1038/sdata.2016.18\>.

Insgesamt wurden unter den vier Abkürzungen **F**indable -- auffindbar,
**A**ccessible -- zugänglich, **I**nteroperable -- interoperabel und
**R**eusable -- wiederverwendbar 15 Prinzipien formuliert, die sich
unter folgendem Link abrufen lassen:

> GO FAIR. „F1: (Meta) Data Are Assigned Globally Unique and Persistent
> Identifiers". Zugegriffen 25. Juni 2024.
> \<https://www.go-fair.org/fair-principles/f1-meta-data-assigned-globally-unique-persistent-identifiers/\>.

Diese Ansätze stehen in enger Verbindung mit offener Wissenschaft und
werden auch teilweise als Ansätze in den Bereichen Gesundheit und
Verwaltung (Open Government) verwendet. Ein ausführbares
Jupyter-Notebook entspricht in jedem Fall denn FAIR-Prinzipien, in dem
es die dahinter liegenden Daten genügend dokumentiert. Eine theoretische
Vertiefung zu den FAIR-Prinzipien findet sich in den beiden folgenden
Beiträgen:

> Jacobsen, Annika, Ricardo de Miranda Azevedo, Nick Juty, Dominique
> Batista, Simon Coles, Ronald Cornet, Mélanie Courtot, u. a. „FAIR
> Principles: Interpretations and Implementation Considerations". *Data
> Intelligence* 2, Nr. 1--2 (1. Januar 2020): 10--29.
> \<https://doi.org/10.1162/dint_r_00024\>.
>
> Schultes, Erik, und Peter Wittenburg. „FAIR Principles and Digital
> Objects: Accelerating Convergence on a Data Infrastructure". In *Data
> Analytics and Management in Data Intensive Domains*, herausgegeben von
> Yannis Manolopoulos und Sergey Stupnikov, 3--16. Cham: Springer
> International Publishing, 2019.
> \<https://doi.org/10.1007/978-3-030-23584-0_1\>.
>
> .

Eine weitere wichtige Kategorie im Hinblick auf computergestützte
Narrative sind digitale Objekte, deren Identifikatoren \[DOI's\][^38]
und auch digitale Identifikationsnummern von Forschenden
\[ORCID's\][^39]. Eine Publikation, die einen guten & aktuellen
Überblick für die DOI-Thematik leistet ist 2021 bei De Gruyter
erschienen:

> Liu, Jia. „Digital Object Identifier (DOI) and DOI Services: An
> Overview". *Libri*
>
> 71, Nr. 4 (1. Dezember 2021): 349--60.
> \<https://doi.org/10.1515/libri- 2020-0018\>.

Das Vergeben von DOI's für wissenschaftliche Artikel geht auf das Jahr
2000 zurück, wobei

ein Digitaler Objektbezeichner nach ISO 26324 einen möglichst
eindeutigen und dauerhaften

digitalen Identifikator für physische, digitale oder abstrakte Objekte
liefern soll. Bisher wird

dieses System von der Internationalen DOI Foundation betrieben und die
Vergabe eines DOI

für einen wissenschaftlichen Artikel ist kostenpflichtig. Dabei finden
sich verschiedene

Registrierungsagenturen wie Crossref[^40] oder Datacite[^41]. Das System
ist teilweise fehleranfällig,

wie dem folgenden Beitrag zu entnehmen ist:

> Zhu, Junwen, Guangyuan Hu, und Weishu Liu. „DOI Errors and Possible
> Solutions for Web of Science". *Scientometrics* 118, Nr. 2 (1. Februar
> 2019): 709--18. \<https://doi.org/10.1007/s11192-018-2980-7\>.

Dass das DOI-System teilweise zu unspezifisch ist und z.B. auf
Forschungsinstitutionen \[Research Infrastructures -- RI's\] ausgebaut
werden sollte, lässt sich folgendem Forschungsartikel entnehmen:

> Koulouzis, Spiros, Rahaf Mousa, Andreas Karakannas, Cees de Laat, und
> Zhiming Zhao. „Information Centric Networking for Sharing and
> Accessing Digital Objects with Persistent Identifiers on Data
> Infrastructures". In *2018 18th IEEE/ACM International Symposium on
> Cluster, Cloud and Grid Computing (CCGRID)*, 661--68, 2018.
> \<https://doi.org/10.1109/CCGRID.2018.00098\>.

Somit finden sich gegenwärtig im Data Stewardship und
Datamanagement-Umfeld weitläufige Debatten, die persistenten digitalen
Identifikatoren von einfachen DOI's weiter zu differenzieren hin zu
*Research Organization Registry's* \[ROR's\][^42], die einzelnen
Institutionen und Universitäten zugewiesen werden, *Research Resource
Identifiers* \[RRID's\][^43], die z.B. digital festgehaltenen
Forschungsdaten von Biosamples, Organismen und Zelllinien zugewiesen
werden sowie *Research Activity Identifiers* \[RAiD's\][^44], die
Forschungsprojekten und Forschungsaktivitäten zugewiesen werden. Es ist
zu betonen, dass es sich dabei um äusserst neuartige Entwicklungen
handelt, die teilweise noch nicht in der grösseren
Forschungsgemeinschaft angekommen sind. Ein interessanter Beitrag, den
man in unserer Zeit bereits als ein historischer betrachten könnte, geht
er denn auf das Jahr 2005 zurück, befasst sich genau mit derartigen
Entwicklungen, die mit hoch-kollaborativer, datenintensiver Forschung
innerhalb von computergestützten, digitalen Netzwerktechnologien den Weg
in die modernen Wissenschaften finden:

> Warner, Simeon. „The Transformation of Scholarly Communication".
> *Learned*
>
> *Publishing* 18, Nr. 3 (2005): 177--85.
> \<https://doi.org/10.1087/0953151054636156\>.

Die drei Gebiete des World Wide Web, die FAIR-Grundsätze digitaler Daten
und das Konzept der digitalen Objektbezeichner zusammenbringend und im
Hinblick auf das Szenario reflektierend, in dem autonome Computeragenten
in der Lage sind, «eine selbstgesteuerte Erkundung des globalen
Datenökosystems» durchzuführen, wird im folgenden Beitrag aus dem Jahre
2023 besprochen:

> Santos, Luiz Olavo Bonino da Silva, Tiago Prince Sales, Claudenir M.
> Fonseca, und Giancarlo Guizzardi. „Towards a conceptual model for the
> FAIR Digital Object Framework", 2023.
> \<https://doi.org/10.3233/FAIA231131\>.

Innerhalb der Jupyter-Softwareumgebungen lassen sich digitale
Objektbezeichner automatisch integrieren. Den wissenschaftlichen Autoren
wird damit viel Arbeit abgenommen im Vergleich zu einer Verfassung von
wissenschaftlichen Arbeiten in einem herkömmlichen Text-Editor wie etwa
MS-Word. Diese Funktionen gehen auf die Jupyter-interne
Programmiersprache MyST Markdown zurück. Sie erlaubt es, Metadaten
direkt von den Identifikatoren zu holen und überprüft in Echtzeit, ob
die Links korrekt sind.[^45]

## 4.2 Daten-Management & Repositorien {#daten-management-repositorien .unnumbered}

Ein weiterer wichtiger Aspekt, im Hinblick auf computergestützte
Narrative innerhalb des hier behandelten
Wissenschaftskommunikations-Paradigmas, sind Daten-Management-Pläne und
beständige Repositorien, die den Forschenden den Zugriff auf die Daten
ermöglichen, die nötig sind, um Forschungen zu reproduzieren, zu
ergänzen, weiterzuführen und/oder zu referenzieren. Die Hauptthematik
meines 20-tägigen Praktikums im Open Science Bibliotheksbereich der
Universität Bern war die Organisation geistigen Vermögenswerten,
zurückgehend auf die am 1. März 2023 veröffentlichten Empfehlungen der
Europäischen Kommission. Im Englischen werden diese *Intellectual
Assets* genannt, was ich für einen etwas treffenderen Ausdruck halte.

> „Commission Recommendation (EU) 2023/499 of 1 March 2023 on a Code of
> Practice on the Management of Intellectual Assets for Knowledge
> Valorisation in the European Research Area". *OJ L*. Bd. 069, 1. März
> 2023. \<http://data.europa.eu/eli/reco/2023/499/oj/eng\>.

In diesem Code wird definiert: «'Geistiger Vermögenswert' \[meint\] alle
Ergebnisse oder Produkte, die durch FuI-Tätigkeiten generiert werden
(wie Rechte des geistigen Eigentums, Daten, Know-how, Prototypen,
Prozesse, Verfahrensweisen, Technologien, Software)», wobei mit
FuI-Tätigkeiten Forschung und Innovation gemeint ist. Im selben Bericht
finden sich auch die offiziellen EU-Definitionen von 'geistigem
Eigentum', 'offener Wissenschaft', 'Verwaltung geistiger Vermögenswerte'
etc. und auch die Anwendung der FAIR-Grundsätze hat den Weg in dieses
Dokument der EU gefunden. Für grössere Forschungsprojekte sollten diese
Definitionen zu Beginn konsultiert werden, da sie gewissermassen die
verbindlichsten Richtlinien zur Valorisierung von Wissen im Europäischen
Forschungsraum liefern.

Um diesen Richtlinien nachzukommen, empfiehlt sich die Erstellung eines
Daten-Management-Plans \[DMP\] zu Beginn der Forschung, wie sich eine
Kopie davon im GitHub Repositorium der vorliegenden Arbeit befindet und
zusätzlich als Anhang dem ausgedruckten Dokument beigelegt wird. Gerade
im Hinblick auf Daten- und Software-intensive Projekte, wie dies bei
computergestützten, ausführbaren Notebooks der Fall ist, lohnt sich die
planmässige Übersicht über die geistigen Vermögenswerte. Wie diese
*Intellectual Asset-*Planungen mit Open Science Praktiken vereinbar
sind, ist in folgendem *International Digital Curation
Conference*-Artikel nachzulesen:

> Toro, Federico Grasso. „DMPs as Management Tool for Intellectual
> Assets by SMART-Metrics". *International Journal of Digital Curation*
> 18, Nr. 1 (17. Juni 2024). \<https://doi.org/10.2218/ijdc.v18i1.919\>.

In unserem Fall haben wir uns an eine DMP-Vorlage der *St. Andrews
University* gehalten, wo diese Forschungspraxis bereits Alltag ist.[^46]
Dort wird definiert, dass ein DMP in der Regel zu Beginn der Forschung
erstellt wird. Darin sollen die Absichten für alle Daten skizziert
werden, die während der Forschung kreiert oder wiederverwendet werden.
Es handelt sich um ein lebendiges Dokument, das im Laufe des Projekts
bei Bedarf angepasst werden kann. I.d.R. übersteigt es den Umfang von
1-2 Seiten nicht. Zu den darin gemachten Angaben gehören auch, wie die
Daten organisiert werden, ob möglicherweise Einschränkungen gelten und
wie die Daten in Zukunft bewahrt und weiterverbreitet werden können.
Alle diese Überlegungen stehen auch am Beginn der Erstellung von
Daten-Repositorien für Forschungs- oder Softwareprojekte.

Institutionelle Datenrepositorien, wie etwa die BORIS Plattform der
Universität betreffende Forschung befindet sich noch in den
Kinderschuhen. Institutionelle Repositorien \[IR\] werden in der Regel
als eine Reihe von Diensten definiert, die von einer Institution für die
Verwaltung und Verteilung verschiedener Forschungsmaterialien in
digitaler Form angeboten werden. Die darin enthaltenen Daten, wurden von
Wissenschaftlern oder einer Gemeinschaft von Wissenschaftlern erstellt.
Oftmals stehen die universitären Repositorien in einer engen
Zusammenarbeit mit den Bibliotheksbereich der jeweiligen Institutionen.
Open Science Praktiken sind unmittelbar mit IR verbunden. Einen
systematischen Überblick über die vorhandene Literatur zur Thematik
liefert der folgende Artikel:

> Asadi, Shahla, Rusli Abdullah, Yusmadi Yah, und Shah Nazir.
> „Understanding Institutional Repository in Higher Learning
> Institutions: A Systematic Literature Review and Directions for Future
> Research". *IEEE Access* 7 (2019): 35242--63.
> \<https://doi.org/10.1109/ACCESS.2019.2897729\>.

Wie Repositorien mit Daten und Literaturreferenzierung sowie digitalen
Objektidentifikatoren zusammenhängen und wie diese Dinge aus der Sicht
eines Teams aussehen könnten, das sich Überlegungen macht, ein IR zu
eröffnen, lässt sich in folgendem Beitrag erkunden:

> Fenner, Martin, Mercè Crosas, Jeffrey S. Grethe, David Kennedy,
> Henning Hermjakob, Phillippe Rocca-Serra, Gustavo Durand, u. a. „A
> Data Citation Roadmap for Scholarly Data Repositories". *Scientific
> Data* 6, Nr. 1 (10. April 2019): 28.
> \<https://doi.org/10.1038/s41597-019-0031-8\>.

Des Weiteren empfiehlt sich im Hinblick auf die Repositorien-Forschung
eine Konsultation dieses aktuellen (April 2024) Artikels, in dem zu
lesen ist, dass sich mittlerweile weltweit mehr als 6\'000 registrierte
Open Access Repositorien finden und dies meist in einem universitären
Kontext:

> Lake, Savannah, und Stephannie Regenauer. „Growing an Institutional
> Repository: Leveraging a Citation Database as a Tool for Sourcing
> Deposits and Conducting Outreach". *Library Resources & Technical
> Services* 68, Nr. 1--2 (29. April 2024).
> \<https://doi.org/10.5860/lrts.68n1.8217\>.

An dieser Stelle möchte ich abschliessend noch auf die SSH Open Cloud
verweisen, der offene Marktplatz für Sozialwissenschaften & \[Digital\]
Humanities. Neben Software-Tools & Services finden sich dort
Publikationen, Datensets, kurierte digitale Workflows und auch
Trainingsmaterial für Digital Humanities Projekte und/oder auf
wissenschaftlichen Daten basierende, algorithmische Forschungen. Selbst
Smartphone Apps wie beispielsweise ein ISBN-Barcode Scanner für Importe
von bibliographischen Metadaten in die Zotero-Bibliothek sind auf dieser
Plattform vorhanden.

> „SSH Open Marketplace \| SSHOPENCLOUD". Zugegriffen 24. Juli 2024.
> \<https://sshopencloud.eu/ssh-open-marketplace\>.
>
> .

# 5. Ausführbare Bücher als strukturierte Wissenschaftskommunikation {#ausführbare-bücher-als-strukturierte-wissenschaftskommunikation .unnumbered}

Wie im Vorwort erwähnt, gilt Wolframs *Mathematica* Interface, das auf
1988 zurückgeht und seither stets weiterentwickelt wurde, als das erste
computergestützte Notizbuch. Es erlaubt BenutzerInnen die Kombination
von Code, Text und Datenvisualisierungen in einem einzigen Dokument.
Entgegen dem Jupyter-Projekt wurde es primär für die Darstellung
mathematischer Computation entwickelt. 2011 wurde das «iPython Notebook»
von einem Forscher-Team der University of California, Berkeley und der
California Polytechnic State University kreiert. Diese digitalen
Notizbücher können Code von verschiedensten Programmiersprachen
verarbeiten, Datenvisualisierungen erzeugen und menschenlesbaren Text,
geschrieben in HTML oder Markdown abbilden und verarbeiten sowie durch
LaTeX eingegebene Formeln verwerten. 2014 kam es dann zur Non-Profit,
Open-Source Spin-Off-Gründung des «Project Jupyter», das kürzlich vom
White House Office of Science & Technology Policy als einer der Gewinner
der «Open Science Recognition Challenge» gekürt wurde.[^47] Eine
Übersicht über die konkreten Impulse, die im Hintergrund der
Jupyter-Software Entwicklung stehen, findet sich hier:

> Cockett, Rowan. „Future of Research Communication & Collaboration".
> 20. April 2022. \<https://doi.org/10.5281/zenodo.6476040\>.

In einem historischen Kontext kann gesagt werden, dass es dem
klassischen wissenschaftlichen Artikel

-   an Interaktionsmöglichkeiten für den Leser fehlt, da sie die
    präsentierten Daten nur passiv betrachten und nicht damit
    interagieren können,

-   aus Platzgründen nicht möglich ist, sämtliche relevanten Daten sowie
    den Code und die Algorithmen im Hintergrund der Forschung
    präsentieren zu können,

-   nicht gelingt, eine Separation von Text und Code zu präsentieren, da
    der Code den Narrativen Fluss unterbrechen würde,

-   nur möglich ist, statische Informationen zu präsentieren, was
    letztendlich nur einen ganz bestimmten Moment in der Zeit festhält,
    der schon bald nicht mehr aktuell sein kann.

Wie diese Probleme in Jupyter-Notebooks überwunden werden, zeigt
einerseits der Artikel:

> Granger, Brian E., und Fernando Pérez. „Jupyter: Thinking and
> Storytelling With Code and Data". *Computing in Science & Engineering*
> 23, Nr. 2 (März 2021): 7--14.
> \<https://doi.org/10.1109/MCSE.2021.3059263\>.

Wieso sich in einem globalen Kontext spezifisch die Jupyter-Software
durchsetzt, ist hier zu lesen:

> Perkel, Jeffrey M. „Why Jupyter Is Data Scientists' Computational
> Notebook of Choice". *Nature* 563, Nr. 7729 (30. Oktober 2018):
> 145--46. \<https://doi.org/10.1038/d41586-018-07196-1\>.

Ein Standard-Artikel für einen Einstieg in die Benutzung von
Jupyter-Notizbüchern findet sich hier:

> Beg, Marijan, Juliette Belin, Thomas Kluyver, Alexander Konovalov, Min
> Ragan-Kelley, Nicolas Thiéry, und H. Fangohr. „Using Jupyter for
> Reproducible Scientific Workflows". *Computing in Science &
> Engineering* PP (15. Januar 2021): 1--1.
> \<https://doi.org/10.1109/MCSE.2021.3052101\>.

Wie sich Jupyter-Projekte, Dokumentationen, Forschungsarbeiten und
Bücher für die Schulung, die Lehre und die Datenwissenschaft einsetzten
lassen, ist unter dem folgenden DOI aufzufinden:

> Fleischer, Yannik, Sven Hüsing, Rolf Biehler, Susanne Podworny, und
> Carsten Schulte. „Jupyter Notebooks for Teaching, Learning, and Doing
> Data Science", 2022. \<https://doi.org/10.52041/iase.icots11.T10E3\>.

Im Hinblick auf GLAM-Institutionen (Gallerien, Bibliotheken, Archive &
Museen) und den Einsatz von Jupyter-Notebooks möchte abschliessend auf
folgende beiden Beiträge aufmerksam machen:

> Candela, Gustavo, Sally Chambers, und Tim Sherratt. „An Approach to
> Assess the Quality of Jupyter Projects Published by GLAM
> Institutions". *Journal of the Association for Information Science and
> Technology* 74, Nr. 13 (2023): 1550--64.
> \<https://doi.org/10.1002/asi.24835\>.
>
> Laboratorio de la Biblioteca Virtual Miguel de Cervantes. „GLAM
> Jupyter Notebooks - BVMC.Labs". Zugegriffen 31. Juli 2024.
> \<https://data.cervantesvirtual.com/glam-jupyter-notebooks\>.

Eine nachhaltige Einführung von Jupyter-Software in Prozesse der
Wissenschaftskommunikation ist verbunden mit der Einführung neuer
Infrastruktur-Systeme, Schulungen, Überlegungen zur
Langzeitpräservation- und Ausführbarkeit der Software sowie einer
Anpassung des Peer-Review Prozesses. Dazu mehr im folgenden Kapitel.

## 5.1 Digital History {#digital-history .unnumbered}

Der Fachbereich, der angesprochen ist im Hinblick auch eine nachhaltige
Entwicklung von

computergestützten Narrativen in ausführbaren Büchern wird manchmal
*Digital History*

genannt. Dieses Gebiet, von dem an der Universität Basel beispielsweise
bereits eine

Forschungsabteilung besteht ist wiederum stark verbunden mit dem Gebiet
der Digital

Humanities, deren Namen schon etwas besser bekannt und etabliert ist als
derjenige der

digitalen Geschichte. Eine genaue Definition der Gebiete ist noch in
keinem Fall gegeben.

Folgende Artikel versuchen eine Gebietskizze:

> „Digital History: A Guide to Gathering, Preserving, and Presenting the
> Past on the Web". Zugegriffen 25. Juni 2024.
> \<https://chnm.gmu.edu/digitalhistory/\>.
>
> „Interchange: The Promise of Digital History". *Journal of American
> History* 95, Nr. 2 (1. September 2008): 452--91.
> \<https://doi.org/10.2307/25095630\>.

Als Grundlagenband aus der Geschichtstheorie gilt folgender Band von
Christian Wachter, der 2021 beim *transcript Verlag* erschienen ist und
über *DeGruyter* eingesehen werden kann:

> Wachter, Christian. *Geschichte digital schreiben: Hypertext als
> non-lineare Wissensrepräsentation in der Digital History*. 1. Aufl.
> Bd. 2. Geschichtstheorie. Bielefeld, Germany: transcript Verlag, 2021.
> \<https://doi.org/10.14361/9783839458013\>.

Es ist also nicht weit hergeholt, dass das sich seit 2020 im Aufbau
befindende *Journal of Digital History* (JDH) ebenfalls auf Software aus
der Jupyter-Umgebung stützt. Das JDH ist eine gemeinsame Initiative des
*Luxembourg Centre for Contemporary and Digital History* (C²DH) an der
Universität Luxemburg und der Verlagsgruppe *De Gruyter*. Die
Zeitschrift dient als Forum für kritische Debatten und Diskussionen auf
dem Gebiet der digitalen Geschichte, indem sie eine innovative
Publikationsplattform bietet und eine neue Form der datengesteuerten
Wissenschaft und des transmedialen Geschichtenerzählens in den
Geschichtswissenschaften fördert. Als internationale, von Experten
begutachtete Open-Access-Zeitschrift setzt das JDH neue Maßstäbe im
Bereich der Geschichtspublikation, die auf einem neuartigen,
vielschichtigen Ansatz beruhen. Die Artikel basieren auf Code-Notebooks
und umfassen:

-   **eine Erzählebene**, die die Möglichkeiten des multimedialen
    Geschichtenerzählens erforscht;

-   **eine hermeneutische Ebene**, die die methodischen Implikationen
    der Verwendung digitaler Werkzeuge, Daten und Codes beleuchtet;

-   **eine Datenebene**, die den Zugang zu Daten ermöglicht und diese
    (wenn möglich) wiederverwendbar macht.

Es findet sich dort beispielsweise eine Anleitung, wie Jupyter-Notebooks
erstellt werden können und eine Variante des digitalen Peer-Review
Prozesses ist bereits gegeben.

Siehe dazu:

> Journal of Digital History. „Journal of Digital History". Zugegriffen
> 25. Juni 2024. \<https://journalofdigitalhistory.org\>.

##  {#section .unnumbered}

## 5.2 Digital Humanities im Zeitalter computergestützter Narrative und digitaler Reproduktion {#digital-humanities-im-zeitalter-computergestützter-narrative-und-digitaler-reproduktion .unnumbered}

Abschliessend möchte ich noch auf einen wichtigen Aufsatz[^48] *Digital
humanities in the era of digital reproducibility: towards a fairest and
post-computational framework* hinweisen, der auf ein Publikationsdatum
im Januar 2024 zurückgeht. Darin werden zwei Hauptthemen angesprochen,
die für die vorliegende Arbeit eine Relevanz aufweisen:

1.  *Die Geschichte und Akzeptanz computergestützter Methoden in der
    Linguistik und Geschichtswissenschaft*:

-   In der Linguistik haben computergestützte Ansätze eine lange
    Tradition und sind weitgehend akzeptiert. Sie ist essenziell für
    Forschungen auf dem Bereich computergestützter Narrative, wie wir im
    gleichnamigen Kapitel hier gesehen haben.

-   In der Geschichtswissenschaft, insbesondere in der Archäologie und
    Wirtschafts- und Sozialgeschichte, werden quantitative Methoden seit
    langem eingesetzt. Viele der in der im vorliegenden Literaturbericht
    angesprochenen Themen kommt also durchaus eine Berechtigung zu, in
    Software Umgebungen wie derjenigen von Jupyter-Notebooks
    computergestützt untersucht zu werden.

-   Es wird auch erwähnt, dass die Verwendung computergestützter
    Methoden in der historischen Forschung generell unumstritten ist,
    solange bestimmte Bedingungen erfüllt sind (z.B. Transparenz des
    Korpus, kritische Interpretation der Ergebnisse).

-   In Bereichen wie Kunstgeschichte und Literaturwissenschaft ist die
    Akzeptanz quantitativer Methoden geringer. Wir haben es in diesen
    Gebieten mit dem Bereich zu tun, den wir kulturbildende Kunst
    nennen. Kultur wird nicht nach mathematischen Gesetzten binär
    reproduziert und ist deshalb im Hinblick auf computergestützte
    Narrative als eine Bewegung oder Kraft zu behandeln, die i.d.R. eine
    unendliche, nicht nach mathematischen Gesetzten festzuhaltende
    Entwicklung darstellt. Vielmehr umfasst Kulturwissenschaftliche
    Forschung auch den Bereich, wie computergestützte Narrative in der
    Wissenschaft eingesetzt werden, da der Forschungsgegenstand auch
    immer von der Methode geprägt wird.

2.  *Die Herausforderungen der Reproduzierbarkeit in den Digital
    Humanities*:

-   Ein überstürzter, rein computergestützter Ansatz zur
    Reproduzierbarkeit im Hinblick auf **sämtliche Wissenschaft** kann
    problematisch sein. Die Reproduzierbarkeit an sich ist im Hinblick
    auf die Wissenschaftsforschung zu analysieren.

-   Reproduzierbarkeit in den Digital Humanities ist nur für bestimmte
    algorithmische Schritte geeignet, nicht für die gesamten Korpora. Es
    sei an diesem Punkt beispielsweise auf Walter Benjamins Aufsatz *Das
    Kunstwerk im Zeitalter seiner technischen Reproduzierbarkeit* (1936)
    hingewiesen, in dem gezeigt wird, wie die Aura eines singulären
    Kunstwerks mit dessen technischer Reproduktion bedroht ist.

-   Statt der FAIR-Prinzipien wird für die Digital Humanities ein
    FAIREST-Ansatz vorgeschlagen, der ethische Aspekte, Expertenwissen
    und Quellentransparenz berücksichtigt.

-   Forscher sollten sich nicht allein auf computergestützte Methoden
    verlassen, sondern deren Relevanz im breiteren Kontext und mit
    nicht-computergestützten Methoden demonstrieren.

-   Es wird argumentiert, dass die Digital Humanities über eine reine
    Nachahmung der Reproduzierbarkeit der Informatik hinausgehen müssen,
    um ihre Legitimität zu etablieren und relevant für andere
    Geisteswissenschaften zu bleiben.

Als selbst aus den Geisteswissenschaften kommender Autor scheinen mir
diese Bemerkungen wichtig. Der grosse Vorteil des vorliegenden
computergestützten Narrativs in Form dieser Arbeit ist die Möglichkeit
der exakten Verlinkung zum Literaturkorpus, der sonst über lange Tage in
der Bibliothek bzw. in mehreren Bibliotheken weltweit vom Leser hätten
zusammengesucht werden müssen, um den Folgerungen und Angaben der Thesis
folgen zu können. Ausserdem bleibt der Text dadurch *aktiv* und stellt
in diesem Sinne kein abgeschlossenes Werk dar -- ausser man will in der
ausgedruckten Papierversion davon ein solches sehen.

# 6. Fazit und Ausblick {#fazit-und-ausblick .unnumbered}

Innerhalb des Spannungsfelds von den Problematiken reproduzierbarer
Wissenschaft und der zunehmenden Verwendung von Black-Box-Algorithmen in
grossen Sprachmodellen liefert der vorliegende dokumentarische
Literaturbericht viele Anschlusspunkte, wie diese Problematiken in der
Forschung effizient angegangen werden können. Computergestützte
Narrative in Form von ausführbaren Büchern bieten vielversprechende
Lösungsansätze für diese aktuellen Herausforderungen in der
Wissenschaftskommunikation, in einer Welt fortschreitender
Digitalisierung und der zunehmenden Komplexität von Forschungsdaten.
Ausführbare Bücher vereinen die Prinzipien computergestützter Narrative
mit den Anforderungen von Open Science und den FAIR-Prinzipien. Sie
ermöglichen eine transparente, reproduzierbare und interaktive Form der
Wissenschaftskommunikation. Im Bereich der Digital Humanities zeigt
sich, dass datengestützte Reproduzierbarkeit nicht in allen Fällen
sinnvoll oder möglich ist. Die Interpretation und der Kontext spielen
hier eine ebenso wichtige Rolle wie die reinen Daten.

Ausblickend lässt sich feststellen, dass die Integration
computergestützter Narrative in die wissenschaftliche Praxis noch am
Anfang steht. Zukünftige Entwicklungen werden zeigen, wie sich diese
Methoden in verschiedenen Disziplinen etablieren und welche neuen Formen
der Wissenschaftskommunikation daraus entstehen. Dabei wird es
entscheidend sein, einen Ausgleich zwischen technologischen
Möglichkeiten und wissenschaftlichen Prinzipien wie Transparenz,
Nachvollziehbarkeit und ethischer Verantwortung zu finden.

Für Bibliotheks- und Informationswissenschaften ergibt sich daraus die
Aufgabe, neue Wege zur Archivierung, Katalogisierung und Bereitstellung
dieser dynamischen Formate zu entwickeln. Gleichzeitig bietet sich die
Chance, eine aktive Rolle in der Gestaltung und Vermittlung dieser neuen
Formen wissenschaftlicher Kommunikation einzunehmen.

Abschließend lässt sich sagen, dass computergestützte Narrative und
ausführbare Bücher das Potenzial haben, die Art und Weise, wie wir
Wissenschaft kommunizieren und verstehen, grundlegend zu verändern. Sie
bieten neue Möglichkeiten für Interaktion, Transparenz und
Zusammenarbeit in der Forschung. Gleichzeitig werfen sie wichtige Fragen
zur Rolle von Technologie in der Wissenschaft und zur Natur
wissenschaftlichen Wissens im digitalen Zeitalter auf.

[\
]{.underline}

# 7. Literaturverzeichnis {#literaturverzeichnis .unnumbered}

Allemang, Dean; Hendler, Jim (Hg.): Semantic Web for the Working
Ontologist (Second Edition), in, Boston 2011, S. iv. Online:
\<https://doi.org/10.1016/B978-0-12-385965-5.10021-4\>, Stand:
21.07.2024.

Asadi, Shahla; Abdullah, Rusli; Yah, Yusmadi u. a.: Understanding
Institutional Repository in Higher Learning Institutions: A Systematic
Literature Review and Directions for Future Research, in: IEEE Access 7,
2019, S. 35242--35263. Online:
\<https://doi.org/10.1109/ACCESS.2019.2897729\>, Stand: 25.06.2024.

Bacon, Bennett; Khatiri, Azadeh; Palmer, James u. a.: An Upper
Palaeolithic Proto-writing System and Phenological Calendar, in:
Cambridge Archaeological Journal 33 (3), 08.2023, S. 371--389. Online:
\<https://doi.org/10.1017/S0959774322000415\>, Stand: 13.07.2024.

Baker, David; Ellis, Lucy; Baker, David: Future directions in digital
information: predictions, practice, participation, Cambridge MA 2021
(Chandos digital information review series).

Baker, Monya: 1,500 scientists lift the lid on reproducibility, in:
Nature 533 (7604), 01.05.2016, S. 452--454. Online:
\<https://doi.org/10.1038/533452a\>, Stand: 17.07.2024.

Baker, Monya: Over half of psychology studies fail reproducibility test,
in: Nature, 27.08.2015. Online:
\<https://doi.org/10.1038/nature.2015.18248\>, Stand: 16.07.2024.

Beg, Marijan; Belin, Juliette; Kluyver, Thomas u. a.: Using Jupyter for
Reproducible Scientific Workflows, in: Computing in Science &
Engineering PP, 15.01.2021, S. 1--1. Online:
\<https://doi.org/10.1109/MCSE.2021.3052101\>.

Begley, C. Glenn; Buchan, Alastair M.; Dirnagl, Ulrich: Robust research:
Institutions must do their part for reproducibility, in: Nature
525 (7567), 09.2015, S. 25--27. Online:
\<https://doi.org/10.1038/525025a\>, Stand: 16.07.2024.

Bernstein, Mark: On hypertext narrative, in: Proceedings of the 20th ACM
conference on Hypertext and hypermedia, New York, NY, USA 2009 (HT '09),
S. 5--14. Online: \<https://doi.org/10.1145/1557914.1557920\>, Stand:
25.06.2024.

Berthold, Michael R.; Borgelt, Christian; Höppner, Frank u. a.: Guide to
Intelligent Data Science: How to Intelligently Make Use of Real Data,
Cham 2020 (Texts in Computer Science). Online:
\<https://doi.org/10.1007/978-3-030-45574-3\>, Stand: 21.07.2023.

Bredemeier, Willi (Hg.): Zukunft der Informationswissenschaften: hat die
Informationswissenschaft eine Zukunft? : Grundlagen und Perspektiven,
Berlin 2019.

Candela, Gustavo; Chambers, Sally; Sherratt, Tim: An approach to assess
the quality of Jupyter projects published by GLAM institutions, in:
Journal of the Association for Information Science and Technology
74 (13), 2023, S. 1550--1564. Online:
\<https://doi.org/10.1002/asi.24835\>, Stand: 31.07.2024.

Candela, Gustavo; Gabriëls, Nele; Chambers, Sally u. a.: A Checklist to
Publish Collections as Data in GLAM Institutions, in: Global Knowledge,
Memory and Communication, 09.11.2023. Online:
\<https://doi.org/10.1108/GKMC-06-2023-0195\>, Stand: 25.06.2024.

Cockett, Rowan: Future of Research Communication & Collaboration,
20.04.2022. Online: \<https://doi.org/10.5281/zenodo.6476040\>, Stand:
24.07.2024.

Colavizza, Giovanni; Blanke, Tobias; Jeurgens, Charles u. a.: Archives
and AI: An Overview of Current Debates and Future Perspectives, in:
Journal on Computing and Cultural Heritage 15 (1), décembre.2021,
S. 4:1-4:15. Online: \<https://doi.org/10.1145/3479010\>, Stand:
03.05.2023.

De Hamel, Christopher: Scribes and Illuminators. Online:
\<https://utorontopress.com/9780802077073/scribes-and-illuminators\>,
Stand: 21.07.2024.

Eichenberger, Nicole; Harnisch, Franziska; Schmid, Larissa: Editorial:
Critical Library Perspectives. Ein digitales Denklabor, in: 027.7
Zeitschrift für Bibliothekskultur / Journal for Library Culture 9 (4),
12.09.2022. Online: \<https://doi.org/10.21428/1bfadeb6.7b5106f5\>,
Stand: 13.09.2022.

Eisenstein, Elizabeth L.: The Printing Press as an Agent of Change,
Cambridge 1980. Online: \<https://doi.org/10.1017/CBO9781107049963\>,
Stand: 13.07.2024.

Fenner, Martin; Crosas, Mercè; Grethe, Jeffrey S. u. a.: A data citation
roadmap for scholarly data repositories, in: Scientific Data 6 (1),
10.04.2019, S. 28. Online:
\<https://doi.org/10.1038/s41597-019-0031-8\>, Stand: 25.06.2024.

Fensel, Dieter: Spinning the Semantic Web: bringing the World Wide Web
to its full potential, Cambridge, Mass. 2005.

Fensel, Dieter; Şimşek, Umutcan; Angele, Kevin u. a.: Knowledge Graphs:
Methodology, Tools and Selected Use Cases, Cham 2020. Online:
\<https://doi.org/10.1007/978-3-030-37439-6\>, Stand: 21.07.2024.

Fernandez, Peter D.; Tilton, Kelly (Hg.): Applying library values to
emerging technology: decision-making in the age of open access, maker
spaces, and the ever-changing library, Chicago, Illinois 2018 (ACRL
Publications in Librarianship ; Number 72).

Fleischer, Yannik; Hüsing, Sven; Biehler, Rolf u. a.: Jupyter Notebooks
for Teaching, Learning, and Doing Data Science, in, 2022. Online:
\<https://doi.org/10.52041/iase.icots11.T10E3\>.

Gerdes, Thomas: Die Open-Science-Bewegung und ihre Bedeutung für die
wissenschaftlichen Bibliotheken. Eine Analyse von Positionspapieren und
Entwicklungsperspektiven, 2018. Online:
\<https://doi.org/10.18452/18983\>.

Grand, Ann: Open science, in: Journal of Science Communication 14,
15.12.2015. Online: \<https://doi.org/10.22323/2.14040302\>.

Granger, Brian E.; Pérez, Fernando: Jupyter: Thinking and Storytelling
With Code and Data, in: Computing in Science & Engineering 23 (2),
03.2021, S. 7--14. Online:
\<https://doi.org/10.1109/MCSE.2021.3059263\>, Stand: 13.07.2024.

Herndon, Joel (Hg.): Data science in the library: : tools and strategies
for supporting data-driven research and instruction, London 2022.

Hofmann, Bjørn: Open Science Knowledge Production: Addressing
Epistemological Challenges and Ethical Implications, in: Publications
10, 14.07.2022, S. 24. Online:
\<https://doi.org/10.3390/publications10030024\>.

Howsam, Leslie (Hg.): The Cambridge Companion to the History of the
Book, Cambridge 2014 (Cambridge Companions to Literature). Online:
\<https://doi.org/10.1017/CCO9781139152242\>, Stand: 16.07.2024.

Ioannidis, John P. A.: Why Most Published Research Findings Are False,
in: PLOS Medicine 2 (8), 30.08.2005, S. e124. Online:
\<https://doi.org/10.1371/journal.pmed.0020124\>, Stand: 17.07.2024.

Jacobsen, Annika; Miranda Azevedo, Ricardo de; Juty, Nick u. a.: FAIR
Principles: Interpretations and Implementation Considerations, in: Data
Intelligence 2 (1--2), 01.01.2020, S. 10--29. Online:
\<https://doi.org/10.1162/dint_r_00024\>, Stand: 25.06.2024.

Jaillant, Lise; Caputo, Annalina: Unlocking digital archives:
cross-disciplinary perspectives on AI and born-digital data, in: AI &
SOCIETY 37 (3), 01.09.2022, S. 823--835. Online:
\<https://doi.org/10.1007/s00146-021-01367-x\>, Stand: 03.05.2023.

Janzin, Marion; Güntner, Joachim: Das Buch vom Buch: 5000 Jahre
Buchgeschichte, 2007.

Joyeux-Prunel, Béatrice: Digital humanities in the era of digital
reproducibility: towards a fairest and post-computational framework, in:
International Journal of Digital Humanities 6 (1), 01.04.2024,
S. 23--43. Online: \<https://doi.org/10.1007/s42803-023-00079-6\>,
Stand: 21.06.2024.

Jupyter, Project: Project Jupyter: Computational Narratives as the
Engine of Collaborative Data Science, Medium, 12.08.2023,
\<https://blog.jupyter.org/project-jupyter-computational-narratives-as-the-engine-of-collaborative-data-science-2b5fb94c3c58\>,
Stand: 17.07.2024.

Kaushik, Anna; Kumar, Ashok; Biswas, Payel: Handbook of Research on
Emerging Trends and Technologies in Library and Information Science.
Online:
\<https://www.igi-global.com/book/handbook-research-emerging-trends-technologies/www.igi-global.com/book/handbook-research-emerging-trends-technologies/223984\>,
Stand: 17.07.2024.

Keith Norambuena, Brian Felipe; Mitra, Tanushree; North, Chris: A Survey
on Event-Based News Narrative Extraction, in: ACM Comput. Surv.
55 (14s), 17.07.2023, S. 300:1-300:39. Online:
\<https://doi.org/10.1145/3584741\>, Stand: 17.07.2024.

Koulouzis, Spiros; Mousa, Rahaf; Karakannas, Andreas u. a.: Information
Centric Networking for Sharing and Accessing Digital Objects with
Persistent Identifiers on Data Infrastructures, in: 2018 18th IEEE/ACM
International Symposium on Cluster, Cloud and Grid Computing (CCGRID),
2018, S. 661--668. Online:
\<https://doi.org/10.1109/CCGRID.2018.00098\>, Stand: 25.06.2024.

Krameritsch, Jakob: Geschichte(n) im Netzwerk: Hypertext und dessen
Potenziale für die Produktion, Repräsentation und Rezeption der
historischen Erzählung, Münster 2007 (Medien in der Wissenschaft).

Kumar, Bhardwaj, Raj: Digitizing the Modern Library and the Transition
From Print to Electronic, 2017.

Lake, Savannah; Regenauer, Stephannie: Growing an Institutional
Repository: Leveraging a Citation Database as a Tool for Sourcing
Deposits and Conducting Outreach, in: Library Resources & Technical
Services 68 (1--2), 29.04.2024. Online:
\<https://doi.org/10.5860/lrts.68n1.8217\>, Stand: 25.06.2024.

Lakomý, Martin; Hlavova, Renata; Machackova, Hana: Open Science and the
Science-Society Relationship, in: Society 56, 15.06.2019, S. 1--10.
Online: \<https://doi.org/10.1007/s12115-019-00361-w\>.

Leonelli, Sabina: Philosophy of Open Science, Cambridge 2023 (Elements
in the Philosophy of Science). Online:
\<https://doi.org/10.1017/9781009416368\>, Stand: 25.06.2024.

Liu, Jia: Digital Object Identifier (DOI) and DOI Services: An Overview,
in: Libri 71 (4), 01.12.2021, S. 349--360. Online:
\<https://doi.org/10.1515/libri-2020-0018\>, Stand: 25.06.2024.

Lobin, Henning: Intelligente Dokumente. Linguistische Repräsentation
komplexer Inhalte für die hypermediale Wissensvermittlung, in: Text im
digitalen Medium. Linguistische Aspekte von Textdesign, Texttechnologie
und Hypertext Engineering, 1999, S. 155--177. Online:
\<https://ids-pub.bsz-bw.de/frontdoor/index/index/docId/7630\>, Stand:
25.06.2024.

Lu, Liyang: Introduction to the Semantic Web and Semantic Web Services,
Routledge & CRC Press,
\<https://www.routledge.com/Introduction-to-the-Semantic\--Web-and-Semantic-Web-Services/Yu/p/book/9780367388973\>,
Stand: 21.07.2024.

Mani, Inderjeet: Computational Narratology, in: Handbook of Narratology,
2014, S. 84--92. Online: \<https://doi.org/10.1515/9783110316469.84\>,
Stand: 17.07.2024.

McDonald, John D.; Levine-Clark, Michael (Hg.): Encyclopedia of Library
and Information Sciences, Boca Raton 2019^4^. Online:
\<https://doi.org/10.1081/E-ELIS4\>.

Miedema, Frank: Open Science: the Very Idea, Dordrecht 2022. Online:
\<https://doi.org/10.1007/978-94-024-2115-6\>, Stand: 25.06.2024.

Needham, Joseph; Tsuen-Hsuin, Tsien: Science and Civilisation in China,
Part 1, Paper and Printing, 1985.

Nestor Maslej, Loredana Fattorini, Raymond Perrault, Vanessa Parli, Anka
Reuel, Erik Brynjolfsson, John Etchemendy, Katrina Ligett, Terah Lyons,
James Manyika, Juan Carlos Niebles, Yoav Shoham, Russell Wald, and Jack
Clark: AI Index Report 2024 -- Artificial Intelligence Index,
\<https://aiindex.stanford.edu/report/\>, Stand: 16.07.2024.

Open Science European Conference: Proceedings of the Paris Open Science
European Conference : OSEC 2022, Marseille 2022 (Laboratoire d'idées).
Online: \<https://books.openedition.org/oep/15829\>, Stand: 25.06.2024.

Parkinson, R. B.; Quirke, Stephen: Papyrus, 1995.

Perkel, Jeffrey M.: Why Jupyter is data scientists' computational
notebook of choice, in: Nature 563 (7729), 30.10.2018, S. 145--146.
Online: \<https://doi.org/10.1038/d41586-018-07196-1\>, Stand:
13.07.2024.

Pinfield, Stephen: Achieving Global Open Access: The Need for
Scientific, Epistemic and Participatory Openness, London 2024.

Pinfield, Stephen; Wakeling, Simon; Bawden, David u. a.: Open Access in
Theory and Practice: The Theory-Practice Relationship and Openness,
London 2020. Online: \<https://doi.org/10.4324/9780429276842\>.

Piper, Andrew; So, Richard Jean; Bamman, David: Narrative Theory for
Computational Narrative Understanding, in: Moens, Marie-Francine; Huang,
Xuanjing; Specia, Lucia u. a. (Hg.): Proceedings of the 2021 Conference
on Empirical Methods in Natural Language Processing, Online and Punta
Cana, Dominican Republic 2021, S. 298--311. Online:
\<https://doi.org/10.18653/v1/2021.emnlp-main.26\>, Stand: 17.07.2024.

Rahaman, Wasim: Semantic Web-Linked Data and Libraries,
https://services.igi-global.com/resolvedoi/resolve.aspx?doi=10.4018/978-1-7998-8051-6.ch009,
\<https://www.igi-global.com/gateway/chapter/www.igi-global.com/gateway/chapter/274750\>,
Stand: 22.07.2024.

Ranade, Priyanka; Dey, Sanorita; Joshi, Anupam u. a.: Computational
Understanding of Narratives: A Survey, in: IEEE Access 10, 2022,
S. 101575--101594. Online:
\<https://doi.org/10.1109/ACCESS.2022.3205314\>, Stand: 17.07.2024.

Riedl, Mark O.: Computational Narrative Intelligence: A Human-Centered
Goal for Artificial Intelligence, 20.02.2016. Online:
\<https://doi.org/10.48550/arXiv.1602.06484\>, Stand: 17.07.2024.

Robson, Eleanor: The Clay Tablet Book in Sumer, Assyria, and Babylonia,
in: A Companion to the History of the Book, 2007, S. 63--83. Online:
\<https://doi.org/10.1002/9780470690949.ch5\>, Stand: 15.07.2024.

Rosa-Clark: You are Crossref, website, Crossref,
\<https://www.crossref.org/\>, Stand: 25.06.2024.

Santos, Luiz Olavo Bonino da Silva; Sales, Tiago Prince; Fonseca,
Claudenir M. u. a.: Towards a conceptual model for the FAIR Digital
Object Framework, in, 2023. Online:
\<https://doi.org/10.3233/FAIA231131\>, Stand: 25.06.2024.

Sayre, Franklin; Riegelman, Amy: Replicable Services for Reproducible
Research: A Model for Academic Libraries, in: College & Research
Libraries 80 (2), 01.03.2019, S. 260. Online:
\<https://doi.org/10.5860/crl.80.2.260\>, Stand: 16.07.2024.

SBFI, Staatssekretariat für Bildung, Forschung und Innovation: Open
Science,
\<https://www.sbfi.admin.ch/sbfi/de/home/hs/hochschulen/hochschulpolitische-themen/open-science.html\>,
Stand: 22.07.2024.

Schultes, Erik; Wittenburg, Peter: FAIR Principles and Digital Objects:
Accelerating Convergence on a Data Infrastructure, in: Manolopoulos,
Yannis; Stupnikov, Sergey (Hg.): Data Analytics and Management in Data
Intensive Domains, Cham 2019, S. 3--16. Online:
\<https://doi.org/10.1007/978-3-030-23584-0_1\>.

Scientific And Technical Information: White Paper --- Open Science in a
Digital Republic, 2016. Online:
\<https://doi.org/10.4000/books.oep.1635\>, Stand: 25.06.2024.

Somers, James: The Scientific Paper Is Obsolete, The Atlantic,
05.04.2018,
\<https://www.theatlantic.com/science/archive/2018/04/the-scientific-paper-is-obsolete/556676/\>,
Stand: 13.07.2024.

Spencer, Ross: Binary trees? Automatically identifying the links between
born-digital records, in: Archives & Manuscripts 45 (2), 06.08.2017,
S. 77--99. Online: \<https://doi.org/10.1080/01576895.2017.1330158\>,
Stand: 25.06.2024.

Stracke, Christian: Open Science and Radical Solutions for Diversity,
Equity and Quality in Research: A Literature Review of Different
Research Schools, Philosophies and Frameworks and Their Potential Impact
on Science and Education, in, 2020, S. 17--37. Online:
\<https://doi.org/10.1007/978-981-15-4276-3_2\>.

Stuckenschmidt, Heiner; Van Harmelen, Frank: Information Sharing on the
Semantic Web, Berlin, Heidelberg 2005. Online:
\<https://doi.org/10.1007/b138282\>, Stand: 21.07.2024.

Thibault, Robert T.; Amaral, Olavo B.; Argolo, Felipe u. a.: Open
Science 2.0: Towards a truly collaborative research ecosystem, in: PLOS
Biology 21 (10), 19.10.2023, S. e3002362. Online:
\<https://doi.org/10.1371/journal.pbio.3002362\>, Stand: 25.06.2024.

Thompson, John B.: Book Wars: The Digital Revolution in Publishing,
2021.

Umlauf, Konrad; Fühles-Ubach, Simone; Seadle, Michael (Hg.): Handbuch
Methoden der Bibliotheks- und Informationswissenschaft: Bibliotheks-,
Benutzerforschung, Informationsanalyse, 2013. Online:
\<https://doi.org/10.1515/9783110255546\>, Stand: 09.07.2022.

Vancauwenbergh, Sadia: Digital Libraries - Advancing Open Science, 2021.
Online: \<https://doi.org/10.5772/intechopen.87798\>, Stand: 25.06.2024.

Vierkant, Paul: DataCite -- Connecting Research, Advancing Knowledge,
DataCite, \<https://datacite.org/\>, Stand: 25.06.2024.

Wachter, Christian: Geschichte digital schreiben: Hypertext als
non-lineare Wissensrepräsentation in der Digital History, Bd. 2,
Bielefeld, Germany 2021^1^ (Geschichtstheorie). Online:
\<https://doi.org/10.14361/9783839458013\>, Stand: 25.06.2024.

Warner, Simeon: The transformation of scholarly communication, in:
Learned Publishing 18 (3), 2005, S. 177--185. Online:
\<https://doi.org/10.1087/0953151054636156\>, Stand: 25.06.2024.

Wilkinson, Mark D.; Dumontier, Michel; Aalbersberg, IJsbrand Jan u. a.:
The FAIR Guiding Principles for scientific data management and
stewardship, in: Scientific Data 3 (1), 15.03.2016, S. 160018. Online:
\<https://doi.org/10.1038/sdata.2016.18\>, Stand: 25.06.2024.

Yamauchi, Edwin: Review of The Birth of the Codex, in: The Journal of
Library History (1974-1987) 20 (2), 1985, S. 202--204. Online:
\<https://www.jstor.org/stable/25541600\>, Stand: 21.07.2024.

Zarghani, Maryam; Nemati-Anaraki, Leila; Sedghi, Shahram u. a.: The
Application of Open Science Potentials in Research Processes: A
Comprehensive Literature Review, in: Libri 73 (2), 01.06.2023,
S. 167--186. Online: \<https://doi.org/10.1515/libri-2022-0007\>, Stand:
25.06.2024.

Sonstige Quellenangaben, ohne Autor-Informationen:

Begriffe der Digital Humanities: Ein diskursives Glossar, Wolfenbüttel
2023 (Zeitschrift für digitale Geisteswissenschaften. Working Papers. -
Wolfenbüttel : Forschungsverbund Marbach Weimar Wolfenbüttel,
\[2021\]- ; ZDB-ID: 3154630-4 2), S. 1. Online:
\<https://zfdg.de/wp_2023\>, Stand: 22.07.2024.

Grundlagen der Informationswissenschaft, 2022. Online:
\<https://doi.org/10.1515/9783110769043\>, Stand: 16.07.2024.

Interchange: The Promise of Digital History, in: Journal of American
History 95 (2), 01.09.2008, S. 452--491. Online:
\<https://doi.org/10.2307/25095630\>, Stand: 25.06.2024.

Johannes Gutenberg - Deutsche Digitale Bibliothek,
\<https://www.deutsche-digitale-bibliothek.de/person/gnd/118543768\>,
Stand: 21.07.2024.

The original proposal of the WWW, HTMLized,
\<https://www.w3.org/History/1989/proposal.html\>, Stand: 25.06.2024.

LaTeX - A document preparation system,
\<https://www.latex-project.org/\>, Stand: 25.06.2024.

DOI.org, \<https://www.doi.org/the-foundation/about-us/\>, Stand:
25.06.2024.

DOI (Digital Object Identifier) \| CERN Scientific Information Service
(SIS),
\<https://sis.web.cern.ch/submit-and-publish/persistent-identifiers/doi\>,
Stand: 25.06.2024.

ORCID, \<https://orcid.org/\>, Stand: 25.06.2024.

Research Organization Registry (ROR), Research Organization Registry
(ROR), \<https://ror.org/\>, Stand: 24.07.2024.

RRID \| Welcome\..., \<https://rrid.site/\>, Stand: 24.07.2024.

Research Activity Identifier, Research Activity Identifier,
\<https://raid.org\>, Stand: 24.07.2024.

External References - MyST Markdown,
\<https://mystmd.org/guide/external-references\>, Stand: 24.07.2024.

Data management plans - Research - University of St Andrews,
\<https://www.st-andrews.ac.uk/research/support/open-research/research-data-management/requirements-for-postgraduate-students/data-management-plans/\>,
Stand: 24.07.2024.

F1: (Meta) data are assigned globally unique and persistent identifiers,
GO FAIR,
\<https://www.go-fair.org/fair-principles/f1-meta-data-assigned-globally-unique-persistent-identifiers/\>,
Stand: 25.06.2024.

SSH Open Marketplace \| SSHOPENCLOUD,
\<https://sshopencloud.eu/ssh-open-marketplace\>, Stand: 24.07.2024.

Journal of Digital History, Journal of Digital History,
\<https://journalofdigitalhistory.org\>, Stand: 25.06.2024.

Digital History: A Guide to Gathering, Preserving, and Presenting the
Past on the Web, \<https://chnm.gmu.edu/digitalhistory/\>, Stand:
25.06.2024.

GLAM Jupyter Notebooks - BVMC.Labs, Laboratorio de la Biblioteca Virtual
Miguel de Cervantes,
\<https://data.cervantesvirtual.com/glam-jupyter-notebooks\>, Stand:
31.07.2024.

[^1]: Somers, James: The Scientific Paper Is Obsolete, The Atlantic,
    05.04.2018,
    \<https://www.theatlantic.com/science/archive/2018/04/the-scientific-paper-is-obsolete/556676/\>,
    Stand: 13.07.2024.

[^2]: Paul Romer,
    \<https://paulromer.net/jupyter-mathematica-and-the-future-of-the-research-paper/\>,
    Stand: 13.07.2024.

[^3]: Ioannidis, John P. A.: Why Most Published Research Findings Are
    False, in: PLOS Medicine 2 (8), 30.08.2005, S. e124. Online:
    \<https://doi.org/10.1371/journal.pmed.0020124\>, Stand: 17.07.2024.

[^4]: Baker, Monya: 1,500 scientists lift the lid on reproducibility,
    in: Nature 533 (7604), 01.05.2016, S. 452--454. Online:
    \<https://doi.org/10.1038/533452a\>, Stand: 17.07.2024.

[^5]: Begley, C. Glenn; Buchan, Alastair M.; Dirnagl, Ulrich: Robust
    research: Institutions must do their part for reproducibility, in:
    Nature 525 (7567), 09.2015, S. 25--27. Online:
    \<https://doi.org/10.1038/525025a\>, Stand: 16.07.2024.

[^6]: Baker, Monya: Over half of psychology studies fail reproducibility
    test, in: Nature, 27.08.2015. Online:
    \<https://doi.org/10.1038/nature.2015.18248\>, Stand: 16.07.2024.

[^7]: Begley; Buchan; Dirnagl: Robust research.

[^8]: Sayre, Franklin; Riegelman, Amy: Replicable Services for
    Reproducible Research: A Model for Academic Libraries, in: College &
    Research Libraries 80 (2), 01.03.2019, S. 265. Online:
    \<https://doi.org/10.5860/crl.80.2.260\>, Stand: 16.07.2024.

[^9]: Nestor Maslej, Loredana Fattorini, Raymond Perrault, Vanessa
    Parli, Anka Reuel, Erik Brynjolfsson, John Etchemendy, Katrina
    Ligett, Terah Lyons, James Manyika, Juan Carlos Niebles, Yoav
    Shoham, Russell Wald, and Jack Clark: AI Index Report 2024 --
    Artificial Intelligence Index,
    \<https://aiindex.stanford.edu/report/\>, Stand: 16.07.2024.

[^10]: Colavizza, Giovanni; Blanke, Tobias; Jeurgens, Charles u. a.:
    Archives and AI: An Overview of Current Debates and Future
    Perspectives, in: Journal on Computing and Cultural Heritage 15 (1),
    décembre.2021, S. 4:1-4:15. Online:
    \<https://doi.org/10.1145/3479010\>, Stand: 03.05.2023.

[^11]: Jaillant, Lise; Caputo, Annalina: Unlocking digital archives:
    cross-disciplinary perspectives on AI and born-digital data, in: AI
    & SOCIETY 37 (3), 01.09.2022, S. 823--835. Online:
    \<https://doi.org/10.1007/s00146-021-01367-x\>, Stand: 03.05.2023.

[^12]: Umlauf, Konrad; Fühles-Ubach, Simone; Seadle, Michael (Hg.):
    Handbuch Methoden der Bibliotheks- und Informationswissenschaft:
    Bibliotheks-, Benutzerforschung, Informationsanalyse, 2013, S.25
    Online: \<https://doi.org/10.1515/9783110255546\>, Stand:
    09.07.2022.

[^13]: Spencer, Ross: Binary trees? Automatically identifying the links
    between born-digital records, in: Archives & Manuscripts 45 (2),
    06.08.2017, S. 77--99. Online:
    \<https://doi.org/10.1080/01576895.2017.1330158\>, Stand:
    25.06.2024.

[^14]: Eichenberger, Nicole; Harnisch, Franziska; Schmid, Larissa:
    Editorial: Critical Library Perspectives. Ein digitales Denklabor,
    in: 027.7 Zeitschrift für Bibliothekskultur / Journal for Library
    Culture 9 (4), 12.09.2022, S. 2 Online:
    \<https://doi.org/10.21428/1bfadeb6.7b5106f5\>, Stand: 13.09.2022.

[^15]: Fernandez, Peter D.; Tilton, Kelly (Hg.): Applying library values
    to emerging technology: decision-making in the age of open access,
    maker spaces, and the ever-changing library, Chicago, Illinois 2018
    (ACRL Publications in Librarianship ; Number 72).

[^16]: Berthold, Michael R.; Borgelt, Christian; Höppner, Frank u. a.:
    Guide to Intelligent Data Science: How to Intelligently Make Use of
    Real Data, Cham 2020 (Texts in Computer Science). Online:
    \<https://doi.org/10.1007/978-3-030-45574-3\>, Stand: 21.07.2023.

[^17]: Baker, David; Ellis, Lucy; Baker, David: Future directions in
    digital information: predictions, practice, participation, Cambridge
    MA 2021 (Chandos digital information review series).

[^18]: Bredemeier, Willi (Hg.): Zukunft der Informationswissenschaften:
    hat die Informationswissenschaft eine Zukunft? : Grundlagen und
    Perspektiven, Berlin 2019.

[^19]: Vgl. Jupyter, Project: Project Jupyter: Computational Narratives
    as the Engine of Collaborative Data Science, Medium, 12.08.2023,
    \<https://blog.jupyter.org/project-jupyter-computational-narratives-as-the-engine-of-collaborative-data-science-2b5fb94c3c58\>,
    Stand: 17.07.2024.

[^20]: Ebd.

[^21]: Bacon, Bennett; Khatiri, Azadeh; Palmer, James u. a.: An Upper
    Palaeolithic Proto-writing System and Phenological Calendar, in:
    Cambridge Archaeological Journal 33 (3), 08.2023, S. 371--389.
    Online: \<https://doi.org/10.1017/S0959774322000415\>, Stand:
    13.07.2024.

[^22]: Vgl. Schmandt-Besserat, Denise: The Evolution of Writing, in
    James Wright, ed., INTERNATIONAL ENCYCLOPEDIA OF SOCIAL AND
    BEHAVIORAL SCIENCES, Elsevier, 2014 Online:
    \<https://sites.utexas.edu/dsb/tokens/the-evolution-of-writing/\>,
    Stand: 13.07.2024.

[^23]: Ray, John: The Rosetta Stone and the Rebirth of Ancient Egypt,
    Harvard University Press,
    \<https://www.hup.harvard.edu/books/9780674063945\>, Stand:
    21.07.2024.

[^24]: Vgl. ebd.

[^25]: Robson, Eleanor: The Clay Tablet Book in Sumer, Assyria, and
    Babylonia, in: A Companion to the History of the Book, 2007,
    S. 63--83. Online: \<https://doi.org/10.1002/9780470690949.ch5\>,
    Stand: 15.07.2024.

[^26]: Parkinson, R. B.; Quirke, Stephen: Papyrus, 1995.

[^27]: Needham, Joseph; Tsuen-Hsuin, Tsien: Science and Civilisation in
    China, Part 1, Paper and Printing, 1985.

[^28]: Yamauchi, Edwin: Review of The Birth of the Codex, in: The
    Journal of Library History (1974-1987) 20 (2), 1985, S. 202--204.
    Online: \<https://www.jstor.org/stable/25541600\>, Stand:
    21.07.2024.

[^29]: De Hamel, Christopher: Scribes and Illuminators. Online:
    \<https://utorontopress.com/9780802077073/scribes-and-illuminators\>,
    Stand: 21.07.2024.

[^30]: Johannes Gutenberg - Deutsche Digitale Bibliothek,
    \<https://www.deutsche-digitale-bibliothek.de/person/gnd/118543768\>,
    Stand: 21.07.2024.

[^31]: Eisenstein, Elizabeth L.: The Printing Press as an Agent of
    Change, Cambridge 1980. Online:
    \<https://doi.org/10.1017/CBO9781107049963\>, Stand: 13.07.2024.

[^32]: A short history of the Web, CERN, 18.07.2024,
    \<https://home.cern/science/computing/birth-web/short-history-web\>,
    Stand: 22.07.2024.

[^33]: Begriffe der Digital Humanities: Ein diskursives Glossar,
    Wolfenbüttel 2023 (Zeitschrift für digitale Geisteswissenschaften.
    Working Papers. - Wolfenbüttel : Forschungsverbund Marbach Weimar
    Wolfenbüttel, \[2021\]- ; ZDB-ID: 3154630-4 2), S. 1. Online:
    \<https://zfdg.de/wp_2023\>, Stand: 22.07.2024.

[^34]: The original proposal of the WWW, HTMLized,
    \<https://www.w3.org/History/1989/proposal.html\>, Stand:
    25.06.2024.

[^35]: \<https://info.cern.ch/hypertext/WWW/Bibliography.html\> ; auf
    der selben Page: Published in \"Physics World\", Vol.5 No 6, June
    1992. Tim Berners-Lee discusses the impact of global hypertext on
    academic publishing.

[^36]: LaTeX - A document preparation system,
    \<https://www.latex-project.org/\>, Stand: 25.06.2024.

[^37]: SBFI, Staatssekretariat für Bildung, Forschung und Innovation:
    Open Science,
    \<https://www.sbfi.admin.ch/sbfi/de/home/hs/hochschulen/hochschulpolitische-themen/open-science.html\>,
    Stand: 22.07.2024.

[^38]: DOI.org, \<https://www.doi.org/the-foundation/about-us/\>, Stand:
    25.06.2024; DOI (Digital Object Identifier) \| CERN Scientific
    Information Service (SIS),
    \<https://sis.web.cern.ch/submit-and-publish/persistent-identifiers/doi\>,
    Stand: 25.06.2024.

[^39]: ORCID, \<https://orcid.org/\>, Stand: 25.06.2024.

[^40]: Rosa-Clark: You are Crossref, website, Crossref,
    \<https://www.crossref.org/\>, Stand: 25.06.2024.

[^41]: Vierkant, Paul: DataCite -- Connecting Research, Advancing
    Knowledge, DataCite, \<https://datacite.org/\>, Stand: 25.06.2024.

[^42]: Research Organization Registry (ROR), Research Organization
    Registry (ROR), \<https://ror.org/\>, Stand: 24.07.2024.

[^43]: RRID \| Welcome\..., \<https://rrid.site/\>, Stand: 24.07.2024.

[^44]: Research Activity Identifier, Research Activity Identifier,
    \<https://raid.org\>, Stand: 24.07.2024.

[^45]: External References - MyST Markdown,
    \<https://mystmd.org/guide/external-references\>, Stand: 24.07.2024.

[^46]: Data management plans - Research - University of St Andrews,
    \<https://www.st-andrews.ac.uk/research/support/open-research/research-data-management/requirements-for-postgraduate-students/data-management-plans/\>,
    Stand: 24.07.2024.

[^47]: White House Office of Science & Technology Policy Announces Year
    of Open Science Recognition Challenge Winners \| OSTP, The White
    House, 21.03.2024,
    \<https://www.whitehouse.gov/ostp/news-updates/2024/03/21/white-house-office-of-science-technology-policy-announces-year-of-open-science-recognition-challenge-winners/\>,
    Stand: 30.07.2024.

[^48]: Joyeux-Prunel, Béatrice: Digital humanities in the era of digital
    reproducibility: towards a fairest and post-computational framework,
    in: International Journal of Digital Humanities 6 (1), 01.04.2024,
    S. 23--43. Online: \<https://doi.org/10.1007/s42803-023-00079-6\>,
    Stand: 21.06.2024.
