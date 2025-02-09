CHANGELOG
=========

## v1.0.7 (2021-04-26)

* :sparkles: Add fullwidth punctuation to support CJK [23](https://github.com/aresa7796/sentences/pull/23)

## v1.0.6 (2017-03-05)

* :package: Ignore command line dependencies from go vendoring

## v1.0.5 (2017-03-05)

* :bug: Sentence tokenizer would incorrectly parse a spaced ellipsis ". . ." as multiple sentences [16](https://github.com/aresa7796/sentences/pull/16)

## v1.0.4 (2017-03-04)

* :bug: Fixed regression that caused text that didn't end in punctuation to get cropped [75af2bb](https://github.com/aresa7796/sentences/commit/75af2bb14a9aed96680f37972d594bb1693d8454)

## v1.0.3 (2017-03-04)

* :bug: Fixed issue where the WordTokenizer would crop off the last word [15](https://github.com/aresa7796/sentences/pull/15)

## v1.0.2

* Word Tokenizer: iterate over string by runes in word tokenizer
* Use gopkg.in instead of github package for the english package
* Added a few more tests

## v1.0.1

* Caching all regular expression compilations for performance optimizations
* Updated documentation to satisfy `go lint`
* A+ score on goreportcard: https://goreportcard.com/report/github.com/aresa7796/sentences

## v1.0.0

* Initial release
