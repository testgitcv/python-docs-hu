Hungarian Translation of the Python Documentation
=================================================

Documentation Contribution Agreement
------------------------------------

NOTE REGARDING THE LICENSE FOR TRANSLATIONS: Python's documentation is
maintained using a global network of volunteers. By posting this
project on Transifex, Github, and other public places, and inviting
you to participate, we are proposing an agreement that you will
provide your improvements to Python's documentation or the translation
of Python's documentation for the PSF's use under the CC0 license
(available at https://creativecommons.org/publicdomain/zero/1.0/legalcode). In
return, you may publicly claim credit for the portion of the
translation you contributed and if your translation is accepted by the
PSF, you may (but are not required to) submit a patch including an
appropriate annotation in the Misc/ACKS or TRANSLATORS file. Although
nothing in this Documentation Contribution Agreement obligates the PSF
to incorporate your textual contribution, your participation in the
Python community is welcomed and appreciated.

You signify acceptance of this agreement by submitting your work to
the PSF for inclusion in the documentation.

Contributing to the Translation
-------------------------------

Your help is welcome, you can start with easy tasks like reviewing
fuzzy entries to help keeping the documentation up to date.  You can
also proofread already translated entries, and finally translate
untranslated ones.

How to Contribute
-----------------

You can either contribute on [transifex/python-doc/public/](https://www.transifex.com/python-doc/public/),
or by simply openning an
issue on this repository, or by editing the ``po`` files.

To modify those files you first have to fork this project and follow
github instructions to clone it.

Next, to edit the files, you can use an editor of your choice, there's many:

- highly recommended: [poedit](http://www.poedit.net/)
- gted
- gtranslator
- lokalize
- betterpoeditor
- vim or emacs with an appropriate mode
- V?? on Android
- probably many others

Finally, once your contribution is done, do a pull request so we
can review and merge it.

What to translate/not translate
-------------------------------

- Prioritize the higher version, identical strings between version can
  automatically be reused.
- Do not translate content of `:keyword:...`, `:mod:...`, `:class:...`, `:meth:...`, `:func:...`, `:ref:...`
- Put english words, if you have to use them, in *italics* (surrounded
  by stars).

Where to get help
-----------------

The coordinator for this translation is [gbtami](https://github.com/gbtami).

Feel free to ask your questions on [python-hu@python.org](https://mail.python.org/mailman/listinfo/python-hu)
or on [freenode](http://webchat.freenode.net/?channels=python-doc&uio=d4).

Priorities
----------

The `tutorial/` directory has a high priority as translations aim
for newcomers, then here are files most read in the original version:

- library/functions.po
- library/stdtypes.po
- library/string.po
- library/re.po
- library/datetime.po
- library/csv.po
- library/os.po
- library/random.po
- library/json.po
- library/subprocess.po

Glossary
--------

For consistency in our translations, here are some propositions and
reminders for frequent terms you'll have to translate, don't hesitate
to open an issue if you disagree.

|english                     |hungarian                   |
|:---------------------------|:---------------------------|
|argument                    |argumentum                  |
|attribute (class)           |attrib??tum                  |
|backslash                   |vissza perjel               |
|buffer                      |puffer                      |
|built-in (function)         |be??p??tett (f??ggv??ny)        |
|byte                        |b??jt                        |
|bytearray (type)            |bytearray                   |
|bytes (type)                |bytes                       |
|class                       |oszt??ly                     |
|clause                      |??g                          |
|control flow statements     |vez??rl?? utas??t??sok          |
|data attribute              |adatattrib??tum              |
|default                     |alap??rtelmezett             |
|dictionary                  |sz??t??r                      |
|exception                   |kiv??tel                     |
|file                        |f??jl                        |
|handler (exeption)          |kezel??                      |
|immutable                   |nem m??dos??that??             |
|iterable                    |iter??lhat??                  |
|keyword argument            |kulcsszavas argumentum      |
|library reference           |A Python standard k??nyvt??r??nak k??zik??nyve|
|list                        |lista                       |
|list comprehension          |lista??p??t??s                 |
|method                      |met??dus                     |
|mutable                     |m??dos??that??                 |
|object                      |objektum                    |
|package                     |csomag                      |
|positional argument         |hely szerinti argumentum    |
|prompt                      |prompt                      |
|raise an exception          |kiv??telt v??lt ki            |
|right-hand side expression  |jobb oldali kifejez??s       |
|scope                       |hat??sk??r, hat??k??r           |
|sequence                    |sorozat                     |
|sequence unpacking          |sorozat sz??tpakol??sa        |
|set                         |halmaz                      |
|shallow copy, deep copy     |alapszint?? m??solat, teljes k??r?? m??solat|
|slice notation              |szeletjel??l??si m??d          |
|string                      |karakterl??nc, sztring       |
|string-literal              |liter??lis karakterl??nc      |
|token                       |token                       |
|tuple                       |tuple  tuple-t, tuple-nek...|
|Unicode                     |Unicode                     |
