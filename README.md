# Summary

UD_Kalmyk-GDUD is a treebank of Kalmyk, a Mongolic language spoken by the Kalmyk people in the Republic of Kalmykia (southwestern Russia), based on grammatical example sentences derived from a reference grammar.


# Introduction

The Kalmyk GDUD (Grammar-Derived Universal Dependencies) treebank contains 92 sentences of Kalmyk (ISO 639-3: xal), a Mongolic language of the Oirat branch, spoken primarily in the Republic of Kalmykia in the Russian Federation, with smaller diaspora communities elsewhere. Kalmyk is closely related to the Oirat varieties spoken in Xinjiang and Mongolia. The data consist of grammatical example sentences drawn from a reference grammar of Kalmyk, presented in Latin transliteration and accompanied by English translations.

All sentences are manually annotated with lemmas, universal part-of-speech tags (UPOS), morphological features, and dependency relations, following the Universal Dependencies (UD) guidelines. The annotation prioritizes UD core morphological features and dependency relations. The language-specific features `Deixis` (with value `Remt`) and `ExtPos` are used in a small number of cases, following the analysis of the reference grammar. Additional Kalmyk-specific morphological distinctions that do not correspond to any value in the universal feature inventory are encoded in the MISC column, in accordance with UD conventions.

## Data split

Because the treebank is small (well below the 20K-word threshold), all sentences are provided as test data.

## Morphological annotation

All UD core features used in the treebank take standard universal values. The language-specific feature `Deixis=Remt` is used on demonstrative determiners, and `ExtPos=ADV` is used to mark the external part-of-speech function of certain expressions.

## Dependency annotation

UD core relations are used throughout the treebank.


# Acknowledgments

The Kalmyk GDUD treebank was created by Wenchao Li and Haitao Liu, based on grammatical example sentences from a reference grammar of Kalmyk. The annotation of lemmas, part-of-speech tags, morphological features, and dependency relations was carried out manually following the Universal Dependencies guidelines.

We thank Daniel Zeman for his guidance in setting up the treebank repository and for his help with the Universal Dependencies workflow, and the Universal Dependencies community for their support.


# Changelog

* 2026-11-15 v2.19
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.19
License: CC BY-SA 4.0
Includes text: yes
Genre: grammar-examples
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Li, Wenchao; Liu, Haitao
Contributing: here
Contact: widelia@zju.edu.cn
===============================================================================
</pre>
