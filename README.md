Python 3.11.0 (main, Oct 24 2022, 18:26:48) [MSC v.1933 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>>  conda activate base
  File "<stdin>", line 1
    conda activate base
IndentationError: unexpected indent
>>> cd /mnt/d/funguilds/
  File "<stdin>", line 1
    cd /mnt/d/funguilds/
                        ^
SyntaxError: invalid syntax
>>> python FUNGuild.py  taxa -otu otu_table_example.txt -format tsv   -column taxonomy -classifier unite
  File "<stdin>", line 1
    python FUNGuild.py  taxa -otu otu_table_example.txt -format tsv   -column taxonomy -classifier unite
           ^^^^^^^^
SyntaxError: invalid syntax
>>>  python FUNGuild.py  guild -taxa otu_table_example.taxa.txt
  File "<stdin>", line 1
    python FUNGuild.py  guild -taxa otu_table_example.taxa.txt
IndentationError: unexpected indent
>>> python Guilds_v1.1.py  -otu otu_table_example.txt -db fungi
  File "<stdin>", line 1
    python Guilds_v1.1.py  -otu otu_table_example.txt -db fungi
           ^^^^^^^^^
SyntaxError: invalid syntax
>>> history
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'history' is not defined
>>>  history  > command2.txt
  File "<stdin>", line 1
    history  > command2.txt
IndentationError: unexpected indent
