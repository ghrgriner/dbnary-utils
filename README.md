# Overview

This is a small repository with example code and comments on DBnary [1,2].

The motivation is that statistics on translations in the English-language
Wiktionary have only been sporadically provided on the Wiktionary website
over the last 10 years. However, during that time, preprocessed datasets
and aggregated counts have been available through the DBnary project either
immediately as bar graphs in
[the online dashboard](https://kaiko.getalp.org/about-dbnary/dashboard/)
or via [SPARQL queries](https://kaiko.getalp.org/about-dbnary/online-access/).

In this repository we provide some example queries for obtaining translation
counts and give comments on these queries and existing counts.

See [LICENSE.txt](LICENSE.txt) for complete license and attribution
details for DBnary and for this repository.

# Files with Example Queries

There are some remarks provided as comments in the files.

1. [translation\_stats\_by\_sel\_lang\_and\_ver.sparql](translation\_stats\_by\_sel\_lang\_and\_ver.sparql):
we think this gives the translation counts for selected languages presented on
the [dashboard](https://kaiko.getalp.org/about-dbnary/dashboard/) in the
'Number of Translations' figures on the General tab (which presents the data
by Wiktionary) and on the tabs for the individual Wiktionaries (which present
the data by extraction date).

2. [translation\_counts\_by\_lang\_in\_en.sparql](translation\_counts\_by\_lang\_in\_en.sparql): This contains three example queries of translation counts:
   (a) counts for all target languages from the current English-language
       Wiktionary;
   (b) counts for selected languages from the same Wiktionary;
   (c) counts for selected languages with output labels manually
       assigned from the same Wiktionary

3. [translation\_counts\_by\_lang.sparql](translation\_counts\_by\_lang.sparql):
This is the same as (2a) above, but presented by Wiktionary and target language
instead of being limited to the English-language Wiktionary.

# Wiki

The repository [wiki](https://github.com/ghrgriner/dbnary-utils/wiki) has some further discussion.

# References

[1] Sérasset G (2014), “DBnary: Wiktionary as a Lemon-Based Multilingual Lexical Resource in RDF”, in _Semantic Web_, volume 0, number 1. http://www.semantic-web-journal.net/system/files/swj648.pdf

[2] DBnary (2026). DBnary - Wiktionary as Linguistic Linked Open Data. https://kaiko.getalp.org/about-dbnary/. Retrieved September 14, 2026.
