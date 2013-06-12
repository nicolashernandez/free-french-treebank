free-french-treebank
====================

Free French Treebank 

Last release : 130612 

Description

The development of this resource is part of a bigger project which aims at 
building a Free French treebank allowing to train statistical systems on common NLP tasks 
such as text segmentation, morphological analysis, chunking, parsing...

Licence 

The current resource (i.e. annotations) is distributed under the terms of this Lesser General 
Public License for Linguistic Resources [1].
This means you can use it in the context you want, you can modify it, and 
distribute it as long as you do the same with your contribution.
If you use this project to support academic research, then please cite the 
following paper as appropriate [2].

Notes on the current release

The current version is based on the  frwikinews-20130110 articles dump [3].
It has 28000 news articles covering a period from January 2005 to now. 
After filtering of sentences with less than 5 tokens the version has 87461 
sentences and 2535396 tokens. Texts are available under Creative Commons 
Attribution 2.5 (CC-BY 2.5) licence. Prior versions from September 2005 are in 
public domain. The text format have been cleaned up by using a Java Wikipedia
 API  [4], then tokenized using a rule-/dictionary-based tokenizer [5], then 
POS tagged by the Stanford tagger [6].

The resource contains
  * xml-bz2 XML source archive
  * txt raw text 
  * txt-tok a sentence per line and whitespace-separated words
  * txt-tok-pos a pos tag is associated with each word and is separated from this one with an underscore

Feel free to contact us nicolas.hernandez @ univ-nantes.fr or to contribute

Download 

Free French Treebank [0]

References

[0] https://docs.google.com/forms/d/1fSiEaAPeq3S4tF1P1vuWJXuDvMUMQvnQILP2b-58m7k/viewform 
[1] http://infolingu.univ-mlv.fr/lgpllr.html
[2] @inproceedings{hernandez:2013:taln,
    title = {{Construction automatique d'un large corpus libre annot{\'e} morpho-syntaxiquement en fran{\c c}ais}},
    author = {Hernandez, Nicolas and Boudin, Florian},
    abstract = {{Cet article {\'e}tudie la possibilit{\'e} de cr{\'e}er un nouveau corpus {\'e}crit en fran{\c c}ais annot{\'e} morpho-syntaxiquement {\`a} partir d'un corpus annot{\'e} existant. Nos objectifs sont de se lib{\'e}rer de la licence d'exploitation contraignante du corpus d'origine et d'obtenir une modernisation perp{\'e}tuelle des textes. Nous montrons qu'un corpus pr{\'e}-annot{\'e} automatiquement peut permettre d'entra{\^\i}ner un {\'e}tiqueteur produisant des performances {\'e}tat-de-l'art, si ce corpus est suffisamment grand.}},
    language = {Fran{\c c}ais},
    affiliation = {Laboratoire d'Informatique de Nantes Atlantique - LINA},
    booktitle = {{Actes de la conf{\'e}rence TALN-RECITAL 2013}},
    address = {Sables d'Olonne, France},
    audience = {nationale },
    year = {2013},
    month = Jun,
    pdf = {http://hal.archives-ouvertes.fr/hal-00816350/PDF/TALN13.pdf},
}
[3] http://dumps.wikimedia.org/legal.html
[4] http://code.google.com/p/gwtwiki
[5] https://github.com/boudinfl/kea
[6] http://nlp.stanford.edu/software/tagger.shtml
