# ſajnos
## ('sajnos' for technical github reasons)

Replaces 's' characters with long s 'ſ' according to the 18th-century rules described [on Wikipedia](https://en.wikipedia.org/wiki/Long_s#Rules).

Replace s with ſ except:

- always round s at the end of a word (except abbreviations, but not handling this)
- always round s before an apostrophe within a word (that is, an apostrophe followed by a letter)
- always round s adjacent to f

Usage: download sajnos.py and run in the command line. Specify a source file, e.g. ``example.txt``, to be converted:
```
$ python sajnos.py example.txt
```
Output: a new file ``example_long.txt`` in the same directory as the input file.
