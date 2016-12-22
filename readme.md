# spellcheck.py

A transcription of Peter Norvig's spellcheck program [How to Write a Spelling Corrector](http://norvig.com/spell-correct.html)

*error*
```
$ python -i spell.py 
>>> correction('speling')
Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	    File "spell.py", line 14, in correction
	      return max(candidates(word), key=P)
	    File "spell.py", line 18, in candidates
	      return set(w for w in words if w in WORDS)
	  TypeError: 'function' object is not iterable
```      
