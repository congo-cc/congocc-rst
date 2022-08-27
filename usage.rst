Usage
=====

Command line options
--------------------

How CongoCC processes a grammar
-------------------------------

How a grammar file is structured
--------------------------------

Grammar elements
^^^^^^^^^^^^^^^^

Comments
........

Reserved words
..............

Punctuation
...........

Literals
........

Regular expressions
...................

Grammar options
^^^^^^^^^^^^^^^

Top-level directives
^^^^^^^^^^^^^^^^^^^^

The preprocessor
................

INCLUDE
.......


INJECT
......

Lexer rules
^^^^^^^^^^^

Lexical states
^^^^^^^^^^^^^^

Context-sensitive tokenization
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

SKIP
....

MORE
....

Parser rules
^^^^^^^^^^^^

Lookahead and parsing phases
............................

Choice points
.............

SCAN
....

Contextual predicates
*********************

=> and =>||
...........

Semantic lookahead
..................

LOOKAHEAD (legacy)
..................

ASSERT
......

FAIL
....

ACTIVATE_TOKENS and DEACTIVATE_TOKENS
.....................................

ATTEMPT and RECOVER
...................

Semantic actions (code blocks)
..............................

Fault-tolerant parsing
......................

CongoCC output
--------------

How CongoCC generates the lexer and parser
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Special tokens in the grammar - LEXER_CLASS, PARSER_CLASS etc.
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Fine-tuning AST node generation in the grammar
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Fine-tuning tree building in the grammar
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

