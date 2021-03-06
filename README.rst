textacy: NLP, before and after spaCy
====================================

``textacy`` is a Python library for performing a variety of natural language
processing (NLP) tasks, built on the high-performance ``spacy`` library. With the
fundamentals --- tokenization, part-of-speech tagging, dependency parsing, etc. ---
delegated to another library, ``textacy`` focuses on the tasks that come before
and follow after.

.. image:: https://img.shields.io/travis/chartbeat-labs/textacy/master.svg?style=flat-square
    :target: https://travis-ci.org/chartbeat-labs/textacy
    :alt: build status

.. image:: https://img.shields.io/github/release/chartbeat-labs/textacy.svg?style=flat-square
    :target: https://github.com/chartbeat-labs/textacy/releases
    :alt: current release version

.. image:: https://img.shields.io/pypi/v/textacy.svg?style=flat-square
    :target: https://pypi.python.org/pypi/textacy
    :alt: pypi version

.. image:: https://anaconda.org/conda-forge/textacy/badges/version.svg
    :target: https://anaconda.org/conda-forge/textacy
    :alt: conda version

Features
--------

- Provide a convenient entry point and interface to one or many documents, with
  the core processing delegated to spaCy
- Stream text, json, csv, spaCy binary, and other data to and from disk
- Download and explore a variety of included datasets with both text content and
  metadata, from Congressional speeches to historical literature to Reddit comments
- Clean and normalize raw text, before analyzing it
- Access and filter basic linguistic elements, such as words, ngrams, and noun
  chunks; extract named entities, acronyms and their definitions, and key terms
- Flexibly tokenize and vectorize documents and corpora, then train, interpret,
  and visualize topic models using LSA, LDA, or NMF methods
- Compare strings, sets, and documents by a variety of similarity metrics
- Calculate common text statistics, including Flesch-Kincaid Grade Level,
  SMOG Index, and multilingual Flesch Reading Ease

... *and more!*


Links
-----

- `textacy @ PyPi <https://pypi.org/project/textacy/>`_
- `textacy @ GitHub <https://github.com/chartbeat-labs/textacy>`_
- `textacy @ ReadTheDocs <http://textacy.readthedocs.io/en/latest/>`_

**Note:** ReadTheDocs builds have been failing for months, so those docs are
currently out-of-date. *Very sorry*. As a (temporary?) workaround, docs for the
latest version (v0.6.0) have been published via GitHub Pages:

https://chartbeat-labs.github.io/textacy


Maintainer
----------

Howdy, y'all. 👋

- Burton DeWilde (<burton@chartbeat.com>)
