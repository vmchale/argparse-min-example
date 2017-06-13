# argparse-min-example

This is a demonstration of a bug in the python standard library.

To run it yourself:

```bash
 $ pip install argparse_min_example
 $ argparse-min-example --help
```

You should get output something like the following. As you can see, python
calculates the width of 'བོད་སྐད་ལ་' incorrectly, because of the vowel markers.

```bash
usage: argparse-min-example [-h] [--language1 བོད་སྐད་ལ་]
                            [--language2 LANGUAGE]

Process some integers.

optional arguments:
  -h, --help            show this help message and exit
  --language1 བོད་སྐད་ལ་
                        Lanugage for output
  --language2 LANGUAGE  Lanugage for output
```
