Part of [this](https://codegolf.stackexchange.com/q/273179/77736) code golf
challenge, "Decode a Caesar ciphertext with high probability".

Sentences taken from a filtered and cleaned up subset of the MASC 500k corpus
at https://anc.org/data/masc/downloads/data-download/ to which a Caesar cipher
has been applied.

The dialect used for the CSV file uses `""` to mean `"` in a `"`-enclosed string.
This is the default dialect of Python 3.10's
[`csv.DictWriter`](https://docs.python.org/3/library/csv.html#csv.DictWriter).

MASC is distributed without license or other restrictions from the American
National Corpus website. (Public Domain)

The files in this repo are in the Public Domain.
