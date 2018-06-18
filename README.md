---
key: value
another_key: Another value goes here.
a_number_value: 100
scientific_notation: 1e+12
boolean: true
null_value: null
key with spaces: value
however: 'A string, enclosed in quotes.'
'Keys can be quoted too.': "Useful if you want to put a ':' in your key."
single quotes: 'have ''one'' escape pattern'
double quotes: "have many: \", \0, \t, \u263A, \x0d\x0a == \r\n, and more."
literal_block: |
    This entire block of text will be the value of the 'literal_block' key,
    with line breaks being preserved.

    The literal continues until de-dented, and the leading indentation is
    stripped.

        Any lines that are 'more-indented' keep the rest of their indentation -
        these lines will be indented by 4 spaces.
folded_style: >
    This entire block of text will be the value of 'folded_style', but this
    time, all newlines will be replaced with a single space.

    Blank lines, like above, are converted to a newline character.

        'More-indented' lines keep their newlines, too -
        this text will appear over two lines.
a_nested_map:
  key: value
  another_key: Another Value
  another_nested_map:
    hello: hello
0.25: a float key
? |
  This is a key
  that has multiple lines
: and this is its value
? - Manchester United
  - Real Madrid
: [ 2001-01-01, 2002-02-02 ]
a_sequence:
- Item 1
- Item 2
- 0.5 # sequences can contain disparate types.
- Item 4
- key: value
  another_key: another_value
-
  - This is a sequence
  - inside another sequence
- - - Nested sequence indicators
    - can be collapsed
json_map: {"key": "value"}
json_seq: [3, 2, 1, "takeoff"]
and quotes are optional: {key: [3, 2, 1, takeoff]}
explicit_string: !!str 0.5
python_complex_number: !!python/complex 1+2j
? !!python/tuple [5, 7]
: Fifty Seven
datetime: 2001-12-15T02:59:43.1Z
datetime_with_spaces: 2001-12-14 21:59:43.10 -5
date: 2002-12-14
gif_file: !!binary |
  R0lGODlhDAAMAIQAAP//9/X17unp5WZmZgAAAOfn515eXvPz7Y6OjuDg4J+fn5
  OTk6enp56enmlpaWNjY6Ojo4SEhP/++f/++f/++f/++f/++f/++f/++f/++f/+
  +f/++f/++f/++f/++f/++SH+Dk1hZGUgd2l0aCBHSU1QACwAAAAADAAMAAAFLC
  AgjoEwnuNAFOhpEMTRiggcz4BNJHrv/zCFcLiwMWYNG84BwwEeECcgggoBADs=
set:
  ? item1
  ? item2
  ? item3
or: {item1, item2, item3}
set2:
  item1: null
  item2: null
  item3: null
---
