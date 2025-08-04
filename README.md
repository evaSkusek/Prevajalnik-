Ovoj API-ja v jeziku Python za prevajalsko storitev deepl.com.

Installation


.. code:: python

    pip install pydeepl



.. code:: python

    import pydeepl

    sentence = 'I like turtles.'
    from_language = 'EN'
    to_language = 'ES'

    translation = pydeepl.translate(sentence, to_language, from_lang=from_language)
    print(translation)

    # Uporaba samodejnega zaznavanja
    translation = pydeepl.translate(sentence, to_language)
    print(translation)

Podprti jeziki
-------------------

Pydeepl podpira te jezike:

+--------+-----------------+
| Code   | Language        |
+========+=================+
| auto   | *Auto detect*   |
+--------+-----------------+
| DE     | German          |
+--------+-----------------+
| EN     | English         |
+--------+-----------------+
| FR     | French          |
+--------+-----------------+
| ES     | Spanish         |
+--------+-----------------+
| IT     | Italian         |
+--------+-----------------+
| NL     | Dutch           |
+--------+-----------------+
| PL     | Polish          |
+--------+-----------------+



Disclaimer
----------

DeepL je izdelek podjetja DeepL GmbH. Več informacij:
`deepl.com/publisher.html <https://www.deepl.com/publisher.html>`__

Ta projekt je bil močno navdihnjen iz
`node-deepls <https://github.com/pbrln/node-deepl>`__ in
`DeepLy <https://github.com/chriskonnertz/DeepLy>`__.

