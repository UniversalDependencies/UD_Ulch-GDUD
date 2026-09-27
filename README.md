# Summary

UD_Ulch-GDUD is a treebank of Ulch (also called Ulchi), a Southern Tungusic language spoken in the Lower Amur region of the Russian Far East, based on grammatical example sentences derived from a reference grammar.


# Introduction

The Ulch GDUD (Grammar-Derived Universal Dependencies) treebank contains 93 sentences of Ulch (ISO 639-3: ulc), a Southern Tungusic language spoken by the Ulch people along the lower Amur River in the Russian Far East. The data consist of grammatical example sentences drawn from a reference grammar of Ulch, presented in a phonemic Latin-based transcription and accompanied by English translations and interlinear glosses.

All sentences are manually annotated with lemmas, universal part-of-speech tags (UPOS), morphological features, and dependency relations, following the Universal Dependencies (UD) guidelines. The annotation prioritizes UD core morphological features and dependency relations. The language-specific feature `Deixis` (with value `Remt`) is used on demonstrative determiners, following the analysis of the reference grammar. Additional Ulch-specific morphological distinctions that do not correspond to any value in the universal feature inventory are encoded in the MISC column, in accordance with UD conventions.

## Data split

Because the treebank is small (well below the 20K-word threshold), all sentences are provided as test data.

## Morphological annotation

All UD core features used in the treebank take standard universal values. The language-specific feature `Deixis=Remt` is used on demonstrative determiners.

## Dependency annotation

UD core relations are used throughout the treebank.


# Acknowledgments

The Ulch GDUD treebank was created by Wenchao Li and Haitao Liu, based on grammatical example sentences from a reference grammar of Ulch. The annotation of lemmas, part-of-speech tags, morphological features, and dependency relations was carried out manually following the Universal Dependencies guidelines.

We thank Daniel Zeman for his guidance in setting up the treebank repository and for his help with the Universal Dependencies workflow, and the Universal Dependencies community for their support.


# Changelog

* 2026-11-15 v2.19
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.19
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
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
