# oldfrisian-kinship

This repository contains the transformation logic for the dataset _Old Frisian: Kinship_.

The transformation process made available here transforms linguistic data (i.e., lexical entries, senses, and concepts) captured in Excel spreadsheets to Linguistic Linked Data. This process makes use of the open-source software [Open Refine](https://openrefine.org/) and its RDF plugin. Each of the JSON files contained in this repository contains an operation history that can be applied to an Open Refine project with the appropriate content. Afterwards, due to a limitation of the RDF plugin (which is unable to work with URNs), the Turtle files resulting from the transformation still have to be adjusted manually by replacing the pattern "http://urn:" with "urn:".

For more details on the transformation process and the dataset _Old Frisian: Kinship_, please see the following open access article:
* Rita van de Poel and Sander Stolk, “A Case of Kinship: Onomasiological Explorations of Kinship in Old Frisian and Old English”, in Exploring Early Medieval English Eloquence: A Digital Humanities Approach with A Thesaurus of Old English and Evoke, eds. Thijs Porck and Sander Stolk, special issue of Amsterdamer Beiträge zur älteren Germanistik 81: 3-4 (2021), 457–492. doi: 10.1163/18756719-12340239

The original Excel spreadsheet and its resulting Linguistic Linked Data form have been published on DataverseNL [here](https://doi.org/10.34894/SOLVNU). 
Moreover, the dataset can be browsed in the web application Evoke [here](http://evoke.ullet.net/content/ofris-kinship).
