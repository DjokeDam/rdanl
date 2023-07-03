# Work



| uri | naam | opm. | range | vastlegging [^1] | verpl.? [^2] | max. | waarde |
| --- | --- | --- | --- | --- | --- | --- | --- |
||||||||| 
|| **Appellation:** | elementen om de entiteit te benoemen ||| M | >1 ||
| [rdaw:P10088](http://rdaregistry.info/Elements/w/P10088) | 	**titleOfWork** | oorspronkelijke titel | `Nomen` | U | M | 1 |
| [rdaw:P10223](http://rdaregistry.info/Elements/w/P10223)	 | 	**preferredTitleOfWork** | meest bekende titel, alleen indien anders dan **titleOfWork** | `Nomen` | U | MA | 1 |
| [rdaw:P10086](http://rdaregistry.info/Elements/w/P10086) | **variantTitleOfWork** || `Nomen` | U| MA | >1 | 
||
| **Coherence:** | **primaire relaties tussen entiteiten** |||| M | >1 |
| [rdaw:P10078](http://rdaregistry.info/Elements/w/P10078) | 	**expressionOfWork**	|| `Expression` |  S / Id / IRI | M | >1 |
| [rdaw:P10072](http://rdaregistry.info/Elements/w/P10072) | **manifestationOfWork** || `Manifestation` | S / Id / IRI | O | >1 |
||
| **General description:**	| **algemene beschrijving (basistoepassingsprofiel)** |
| rdaw:P10004 | "*category of work*"	| voor o.a. genre | - | U / S / Id / IRI | M | >1 | Brinkman Trefwoorden thesaurus, Thema [^1] |
| rdaw:P10365	| "*extension plan*" || - | S / Id / IRI | M | 1 | RDA Extension Plan http://www.rdaregistry.info/termList/RDAExtensionPlan/?language=nl | 
| rdaw:P10330	 | 	"*note on work*"	|| 	- | unstructured | O | >1 |
| rdaw:P10256	 | "*subject*"	 | 	gebruik waar nodig subproperties met een specifieke range, als Person en Place ||| O	| >1 | 
| rdaw:P10353	 | 	"*language of representative expression*" | oorspronkelijke taal (vertalingen), gebruik als representatieve expressie niet aanwijsbaar || S | O | >1 | ISO 639-2 |
||
| **General relationships:** | 	Algemene elementen die worden gebruikt om relaties van de entiteit te beschrijven (basistoepassingsprofiel) |
| rdaw:P10219	 | 	"*date of work*" || `Timespan` |  U / S / Id / IRI | O | 1 | ISO 8601-1:2019 | 
| rdaw:P10065	 | 	"creator agent of work"	 | gebruik een zo specifiek mogelijke narrow element. Zie tabblad Agent. | `Agent` | S / Id / IRI | M | >1 || NTA, NACO, Corporatiethesaurus | 
| rdaw:P10198	 | 	"related work of work"	| Gebruik een zo specifiek mogelijke narrow element || structured/identifier/iri	 | O | >1 |
| rdaw:P10346	 | 	"representative expression" || `Expression` | structured/identifier/iri | O | >1 | 


[^1]: Vastlegging / *Recording method* volgens **U**: "unstructured", **S**: "structured", **Id**: "identifier", **IRI**: IRI.
[^2]: **M**: "*Must* / Verplicht", **MA**: "*Must if applicable* / Verplicht indien van toepassing", **O**: "*Optional* / Optioneel" 
[^3]: [Thema](https://ns.editeur.org/thema/nl)