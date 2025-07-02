# Metadatenprofile für Testaufgaben: Deutsch Primar

ID of profile-store: `dep`

Publisher: IQB - Institut zur Qualitätsentwicklung im Bildungswesen

Maintainer: IQB - Institut zur Qualitätsentwicklung im Bildungswesen

2 Profile definiert:

## Profil "IQB Deutsch Primar - Aufgabe"

ID of profile: `https://raw.githubusercontent.com/iqb-vocabs/p12/master/unit.json`

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Entwickler:in | Text |Einzeilig, Sprache(n): de | iqb_author |
| Klassenstufe | [Vokabular](http://w3id.org/openeduhub/vocabs/educationalLevel/) | url: 'http://w3id.org/openeduhub/vocabs/educationalLevel/', Mehrfachauswahl, Nummerierung unterdrückt | f0 |
| Für SPF geeignet | Ja/Nein |Text für WAHR: ja, Text für FALSCH: nein | a1 |
| Kopfhörereinsatz | [Vokabular](https://w3id.org/iqb/v24/kh/) | url: 'https://w3id.org/iqb/v24/kh/', Einmalauswahl, Nummerierung unterdrückt | iqb_phones |
| Kompetenzbereich | [Vokabular](https://w3id.org/iqb/v12/s1/) | url: 'https://w3id.org/iqb/v12/s1/', Einmalauswahl, Zeige nur erste Ebene | w8 |
| Aufgabenzeit | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_unit |
| Quellenangaben | Text |Mehrzeilig, Sprache(n): de | iqb_copyright |
| Textsorte | [Vokabular](https://w3id.org/iqb/v28/ts/) | url: 'https://w3id.org/iqb/v28/ts/', Einmalauswahl, Nummerierung unterdrückt | k8 |
| Wortanzahl | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein | iqb_word_count |
| Stimuluszeit | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_stimulus |
| Hörsequenz Transkript | Text |Mehrzeilig, Sprache(n): de | iqb_transcript |
| Unverträgliche Aufgaben | Text |Einzeilig, Sprache(n): de | iqb_compatibility |

## Profil "IQB Deutsch Primar - Item"

ID of profile: `https://raw.githubusercontent.com/iqb-vocabs/p12/master/item.json`

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Itemformat | [Vokabular](https://w3id.org/iqb/v27/dp/) | url: 'https://w3id.org/iqb/v27/dp/', Einmalauswahl, Nummerierung unterdrückt | s3 |
| Anforderungsbereich | [Vokabular](https://w3id.org/iqb/v12/a1/) | url: 'https://w3id.org/iqb/v12/a1/', Einmalauswahl, Nummerierung unterdrückt | s4 |
| Bildungsstandard primär | [Vokabular](https://w3id.org/iqb/v12/s1/) | url: 'https://w3id.org/iqb/v12/s1/', Einmalauswahl | s5 |
| Bildungsstandards sekundär | [Vokabular](https://w3id.org/iqb/v12/s1/) | url: 'https://w3id.org/iqb/v12/s1/', Mehrfachauswahl | s6 |
| Itemzeit | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_item |
| Geschätzte Schwierigkeit | [Vokabular](https://w3id.org/iqb/v26/ea/) | url: 'https://w3id.org/iqb/v26/ea/', Einmalauswahl | e4 |
| Technische Besonderheiten der Antwortoptionen | [Vokabular](https://w3id.org/iqb/v27/ti/) | url: 'https://w3id.org/iqb/v27/ti/', Mehrfachauswahl | iqb_itemtech |

