# Python-Projects
Small projects in Python


Spell Checker
-------------------------------------------------------------------------------------------------------------------------------

This is a simple spelling checker. It takes text from standard input and compares it against list of the words given in the dictionary and returns which spelling is correct and which is not.

A demo run is pasted below:

$ cat test.text

This ees just aanother spelling checking routine.

Boo hoo what do eu think i am doeeng?

$ python spellCheck.py spell.words<test.text

 True   this
 False  ees
 True   just
 False  aanother
 True   spelling
 True   checking
 True   routine
 True   boo
 False  hoo
 True   what
 True   do
 False  eu
 True   think
 True   i
 True   am
 False  doeeng
 
 Sudoku
 ------------------------------------------------------------------------------------------------------------------------------
 This generates a simple sudoku game and solves it stepwise.
