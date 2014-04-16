# Information Extraction aus natürlichsprachlichen Phrasen am Beispiel von Hotelsuchanfragen

Abschlussarbeit zur Erlangung des akademischen Grades Master of Science
(M.Sc.) vorgelegt von Timm Heuss

# Abstract (Deutsch)

Information Extraction aus natürlichsprachlichen Phrasen am Beispiel von
Hotelsuchanfragen

Google setzt heutzutage mit seiner Freitextsuche Maßstäbe, wie
Informationen benutzerfreundlich aufgefunden werden können. Dieser
Realität sehen sich auch die Anbieter von Touristikportalen
konfrontiert, die bisher vor allem auf formularbasierte Eingabeformen
und Suchen setzten.

Als Grundlage für eine Freitextsuche für derartige Portale wird in
dieser Arbeit eine Lösung für die Information Extraction aus
natürlichsprachlichen Hotelsuchanfragen konzipiert und implementiert.
Das Fundament dieser Anwendung besteht aus der standardisierten
Architektur Apache UIMA, sowie der beiden entwicklernahen Aufsätze
uimaFIT und DKPro.

In Anwendung üblicher Verfahren des Natural Language Processings werden
die Benutzereingaben in englischer Sprache zunächst korrigiert, zerlegt
und syntaktisch analysiert. Die so erzeugten Analyseergebnisse werden
anschließend im Kern der Anwendung durch die Rule Engine JBoss Drools
verarbeitet und mit Hilfe deskriptiver, prägnanter Regeln eine Named
Entity Recognition von Hotel- und Zimmerausstattungsmerkmalen
durchgeführt. Neben Erweiterbarkeit und Performance stellen auch
semantische Features der Erkennung einen Mehrwert der Lösung dar, wie
etwa Verneinungen, welche durch die Auswertung der Satzstruktur möglich
sind.

Alle entwickelten Komponenten wurden dabei gemäß geltender
Design-Prinzipien und Paradigmen zugrundeliegender Architekturen
entwickelt. So weist insbesondere die Integrationskomponente, um
Drools-Regeln innerhalb von UIMA einzusetzen, eine hohe Flexibilität
auf. Zusammen mit der Software, die für die systematische Auswertung der
Erkennungsleistung ergänzend zu UIMA-Werkzeugen entwickelt wurde, wird
durch diese Arbeit auch ein wichtiger Grundstein für künftige
Weiterentwicklungen gelegt.

# Abstract (English)

With its free text search, Google nowadays sets a high standard on how
to find information in a convenient and easy way. Even the vendors of
tourism portals are faced with the fact that their primal, form-based
input- and search-functionalities are no longer the users first choice.

To create the foundation for a free text search for such a tourism
portal, this paper is about the design and development of an Information
Extraction solution which is able to process natural-language hotel
search requests. It is based on the standardized architecture Apache
UIMA as well as its developer-friendly derivatives uimaFIT and DKPro.

Applying basic techniques of Natural Language Processing, the English
user input is first corrected, tokenized and syntactically analyzed.
Processing of the analysis results then continues with the Rule Engine
JBoss Drools. In combination with descriptive, concise rules a Named
Entity Recognition for hotel and room amenities is realized. The
resulting solution has significant benefits in terms of its
extensibility and performance. Another great feature is the semantic
support of natural language negations.

Every developed components follows the design principles and paradigms
of the according, underlying architectures. Therefore, especially the
integration component which enables the execution of Drools rules within
UIMA features a high flexibility. Taking also the several enhancements
of the UIMA developer tooling and a developed measuring framework into
account, this paper also lays a essential foundation of future
developments.
