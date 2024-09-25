# Projekt "Genderdarstellungen im Wandel der Zeit - vom 17. bis 20. Jahrhundert"

Das Projekt untersucht mögliche Genderdarstellungen und Zuschreibungen von Genderentitäten in narrativen Texten. Das Genderkorpus beihaltet 92 narrative Texte aus dem 17. bis 21. Jahrhundert.

Die Zuschreibungen sowie mögliche Rollenbilder wurde mithilfe der computerlinguisitschen und visuellen Tools Stanford NER und Genderclassifier, CATMA, AntConc, Visàvis, Word2vec und ChatGPT untersucht.

Dieses Repository enthält die im Projekt verwendeten Daten: 

'AntConc Kollokationen': Hier sind einerseits die aus AntConc exportierten Kollokationslisten für die 20 bzw. 10 häufigsten Named Entities enthalten. Für jede Genderkategorie wurde ein Ordner "Ergebnisse im TXT-Format" angelegt. Außerdem befinden sich hier im Ordner "Ergebnistabellen im XLSX-Format" drei Tabellen. Für jede Genderkategorie sind in einer Tabelle jeweils alle gefundenen Kollokationen zusammengefasst. 

'Gephi Netzwerkanalyse': In diesem Ordner befinden sich die Datentabellen für das mit Gephi erstellte Netzwerk der im Textkorpus häufigsten Adjektive.
Die Datei "MFAdjektive_Gendernetzwerk" enthält eine Visualisierung des Netzwerks.

'Narrative Texte': Hier ist einerseits das Genderkorpus mit den Texten im TXT-Format vorhanden. Im Ordner "XML-Format" befinden sich hier auch alle Texte, wie sie für die Analyse mit Catma verwendet wurden.

'Word Embeddings mit word2vec': Dieser Ordner enthält im Unterordner "Abfrageergebnisse im XLSX-Format" in drei Tabellen, je eine für eine Genderkategorie, die mit word2vec extrahierten semantisch ähnlichsten Wörter zu den 20 bzw. 10 häufigsten Named Entities. 
Im Unterordner "verwendete Notebooks" befinden sich in der Arbeit verwendete, von Mareike Schumacher bereitgestellte, Jupyter-Notebooks. 
Daneben befindet sich hier die DOCX-Datei "Verteilung Ähnlichste Wörter" mit einer tabellarischen Übersicht zu den Genderverhältnissen innerhalb der häufigsten Wörter. 
Im Ordner 'Word Embeddings mit word2vec' ist außerdem eine Grafik zu den semantischen Feldern der Begriffe Mann, Frau und Mensch enthalten.

'vis-à-vis': Hier findet sich in 'Charts' zu jedem narrativen Text eine mit vis-à-vis erstellte Visualisierung zu den jeweiligen Gender-Verteilungen. Eine Grafik für die Häufigkeiten der einzelnen Gender im gesamten Korpus befindet sich in der Datei "Kuchendiagramm_Genderverteilung".

Die Datei 'Ergebnistabelle ChatGPT' enthält eine tabellarische Übersicht über die von ChatGPT getroffene Kategorisierung der Named Entities.

In 'Liste der MFNE des Genderkorpus' sind die häufigsten Named Entities der drei Genderkategorien festgehalten.
