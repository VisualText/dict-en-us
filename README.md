# American English Dictionary
The purpose of this repository is to store the current version of the English Dictionary. It was first generated in the early 2000s using Wordnet which is somewhat outdated but represents the current version with only parts of speech. This version is now found in the file all.dict using the new dict format for NLP++.

A new project involving parsing the English Wiktionary is underway with hopes to generate a comprehensive dictionary with parts of speech and other information such as roots, 

## Current Version
The current version of the English dictionary (originally from Wordnet) can be found here. It was generated by the [parse-attrs](https://github.com/VisualText/dict-en-us/tree/main/parse-attrs) analyzer which parses the attr1.kb, attr2.kb, etc. into [dict-check/input/all.dict](https://github.com/VisualText/dict-en-us/blob/main/dict-check/input/all.dict)

## History

The current dictionary what is used in the NLP Engine and by VisualText comes from [WordNet from Princeton](https://wordnet.princeton.edu/). It hasn't been updated since 2012 or there about.

## Short Term Goals
Short term goals for the English US dictionary:
- update and enhance the vocabulary of English and its parts of speech
- Parse the English Wiktionary into a comprehensive dictionary which can be updated monthly (Wiktionary files are dumped monthly)
- include other features such as numbers, gender, etc. if they are not found in Wiktionary.
