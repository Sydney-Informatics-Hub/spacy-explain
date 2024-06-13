# SpaCy Explainer

This is an explainer notebook for SpaCy Part-of-Speech, Part-of-Speech (fine-grained), and Dependency tags. When SpaCy processes text, it applies a tokenization process first. From there, each token is assigned various tags to categorise it. Below is a list of identifiers for each tag.

[![Binder](https://binderhub.atap-binder.cloud.edu.au/badge_logo.svg)](https://binderhub.atap-binder.cloud.edu.au/v2/gh/Sydney-Informatics-Hub/spacy-explain/main?labpath=spacy-demo.ipynb)

## Identifiers

### Part-of-Speech tags (simple)

| Identifier | Description               |
|------------|---------------------------|
| ADJ        | adjective                 |
| ADP        | adposition                |
| ADV        | adverb                    |
| AUX        | auxiliary                 |
| CCONJ      | coordinating conjunction  |
| DET        | determiner                |
| INTJ       | interjection              |
| NOUN       | noun                      |
| NUM        | numeral                   |
| PART       | particle                  |
| PRON       | pronoun                   |
| PROPN      | proper noun               |
| PUNCT      | punctuation               |
| SCONJ      | subordinating conjunction |
| SYM        | symbol                    |
| VERB       | verb                      |
| X          | other                     |


### Part-of-Speech tags (fine-grained)

| Identifier | Description                                        |
|------------|----------------------------------------------------|
| $          | symbol, currency                                   |
| ''         | closing quotation mark                             |
| ,          | punctuation mark, comma                            |
| -LRB-      | left round bracket                                 |
| -RRB-      | right round bracket                                |
| .          | punctuation mark, sentence closer                  |
| :          | punctuation mark, colon or ellipsis                |
| ADD        | email                                              |
| AFX        | affix                                              |
| CC         | conjunction, coordinating                          |
| CD         | cardinal number                                    |
| DT         | determiner                                         |
| EX         | existential there                                  |
| FW         | foreign word                                       |
| HYPH       | punctuation mark, hyphen                           |
| IN         | conjunction, subordinating or preposition          |
| JJ         | adjective (English), other noun-modifier (Chinese) |
| JJR        | adjective, comparative                             |
| JJS        | adjective, superlative                             |
| LS         | list item marker                                   |
| MD         | verb, modal auxiliary                              |
| NFP        | superfluous punctuation                            |
| NN         | noun, singular or mass                             |
| NNP        | noun, proper singular                              |
| NNPS       | noun, proper plural                                |
| NNS        | noun, plural                                       |
| PDT        | predeterminer                                      |
| POS        | possessive ending                                  |
| PRP        | pronoun, personal                                  |
| PRP$       | pronoun, possessive                                |
| RB         | adverb                                             |
| RBR        | adverb, comparative                                |
| RBS        | adverb, superlative                                |
| RP         | adverb, particle                                   |
| SYM        | symbol                                             |
| TO         | infinitival "to"                                   |
| UH         | interjection                                       |
| VB         | verb, base form                                    |
| VBD        | verb, past tense                                   |
| VBG        | verb, gerund or present participle                 |
| VBN        | verb, past participle                              |
| VBP        | verb, non-3rd person singular present              |
| VBZ        | verb, 3rd person singular present                  |
| WDT        | wh-determiner                                      |
| WP         | wh-pronoun, personal                               |
| WP$        | wh-pronoun, possessive                             |
| WRB        | wh-adverb                                          |
| XX         | unknown                                            |
| _SP        | whitespace                                         |
| ``         | opening quotation mark                             |


### Dependency tags

| Identifier | Description                                  |
|------------|----------------------------------------------|
| acl        | clausal modifier of noun (adjectival clause) |
| acomp      | adjectival complement                        |
| advcl      | adverbial clause modifier                    |
| advmod     | adverbial modifier                           |
| agent      | agent                                        |
| amod       | adjectival modifier                          |
| appos      | appositional modifier                        |
| attr       | attribute                                    |
| aux        | auxiliary                                    |
| auxpass    | auxiliary (passive)                          |
| case       | case marking                                 |
| cc         | coordinating conjunction                     |
| ccomp      | clausal complement                           |
| compound   | compound                                     |
| conj       | conjunct                                     |
| csubj      | clausal subject                              |
| csubjpass  | clausal subject (passive)                    |
| dative     | dative                                       |
| dep        | unclassified dependent                       |
| det        | determiner                                   |
| dobj       | direct object                                |
| expl       | expletive                                    |
| intj       | interjection                                 |
| mark       | marker                                       |
| meta       | meta modifier                                |
| neg        | negation modifier                            |
| nmod       | modifier of nominal                          |
| npadvmod   | noun phrase as adverbial modifier            |
| nsubj      | nominal subject                              |
| nsubjpass  | nominal subject (passive)                    |
| nummod     | numeric modifier                             |
| oprd       | object predicate                             |
| parataxis  | parataxis                                    |
| pcomp      | complement of preposition                    |
| pobj       | object of preposition                        |
| poss       | possession modifier                          |
| preconj    | pre-correlative conjunction                  |
| predet     | None                                         |
| prep       | prepositional modifier                       |
| prt        | particle                                     |
| punct      | punctuation                                  |
| quantmod   | modifier of quantifier                       |
| relcl      | relative clause modifier                     |
| xcomp      | open clausal complement                      |
