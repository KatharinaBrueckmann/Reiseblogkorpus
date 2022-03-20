# Dokumentation des Korpus
Das vorliegende Korpus wurde im Kontext der Masterarbeit „Erstellung eines Korpus deutschsprachiger Reiseblogbeiträge mittels Python“ im Fach Digital Humanities an der Universität Trier erzeugt. Alle eingestellten Texte wurden von den Rechteinhaber:innen gemäß der [CC-BY-NC-SA-Lizenz](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode) lizensiert und stehen als TEI-XML im Rahmen der Lizenzbedingungen zur freien Verfügung. Die Texte enthalten auf Token-Ebene Lemma- und POS-Informationen gemäß Stuttgart-Tübingen-Tagset, die automatisiert mittels des [TreeTaggers](https://www.cis.uni-muenchen.de/~schmid/tools/TreeTagger/) erzeugt wurden.


## Vorstellung der aufgenommenen Reiseblogs
Es wurden die Beiträge aus insgesamt 6 Reiseblogs aufgenommen. Zur Erleichterung der Attribution werden die Autor:innen hier kurz aufgeführt:
- [„Abenteuer unterwegs“](https://abenteuer-unterwegs.de/): Nima Ashoff
- [„Biketour global“](https://www.biketour-global.de/): Martin Moschek
- [„Lieschenradieschen reist“](https://lieschenradieschen-reist.com/): Lynn Benda
- [„Meso-Berlin“](https://www.meso-berlin.de/reiseblog/): Geschäftsführer Stefan Finke als Vertreter der Meso-Reisen GmbH; Laura Ahrens, Sebastian Keller, Kerstin Wöge als Autor:innen der aufgenommenen Beiträge
- [„Planetenreiter“](https://planetenreiter.de/): Dirk Loew
- [„Reisegeheimnisse“](https://urlaubs-welt.de/): Christine Fröhling

## Kennzahlen des Korpus
Insgesamt umfasst das Korpus über 1.3 Millionen Token, die sich auf 1.287 Beiträge verteilen.


## Datenmodell
Die zur Auszeichnung verwendeten Elemente sind ein echtes Subset der [TEI-P5-Richtlinien](https://www.tei-c.org/release/doc/tei-p5-doc/en/html/index.html). Das Datenmodell wurde in einem RNG-Schema formalisiert; alle eingestellten XML-Dateien sind gegenüber diesem Schema valide.

Bestimmte Eigenschaften der Reiseblogbeiträge wurden nicht in das Datenmodell aufgenommen. Dazu zählen insbesondere folgende:
- Abbildungen und zugehörige Bildunterschriften
- Verlinkungen (der Ankertext bleibt bestehen) 

Zudem konnten nicht alle Strukturinformationen der Autor:innen in bestehender Form übernommen werden, da logisch übergeordnete Elemente (z.B. div) in TEI-XML nicht Kindelement eines logisch untergeordneten Elements (z.B. p) sein dürfen. 

Texthervorhebungen (Kursivierung, Fettung, Durch- und Unterstreichung, Hervorhebung mittels der Elemente strong und emph) sind als Attribut des rend-Elementes erhalten geblieben.


## Kontakt
Bei Fragen, Anmerkungen und Verbesserungsvorschlägen stehe ich unter dieser E-Mail-Adresse gerne zur Verfügung: reiseblogkorpus(@)mailbox(Punkt)org. 
