[pikalang] [1]
========
A [brainfuck] [2] derivative based off the vocabulary of [Pikachu] [3] from [Pokémon] [4].

![pikachu](images/pikachu.gif)


Syntax
------
| pikalang  | brainfuck | description                                    |
|-----------|-----------|------------------------------------------------|
| `pi`      | +         | increment the byte at pointer                  |
| `ka`      | -         | decrement the byte at pointer                  |
| `pika`    | [         | if pointer is zero, jump to matching `chu`     |
| `chu`     | ]         | if pointer is nonzero, jump to matching `pika` |
| `pipi`    | >         | increment the data pointer                     |
| `pichu`   | <         | decrement the data pointer                     |
| `pikapi`  | ,         | input of one byte into pointer                 |
| `pikachu` | .         | output the byte at pointer                     |


Installation
------------
stable:
```shell
	pip install pikalang
```

or bleeding edge...
```shell
	git clone https://github.com/skj3gg/pikalang.git
	cd pikalang

	python setup.py install
```


Usage
-----
```shell
	pikalang path/to/file.pokeball
```


File Extention
--------------
A pikalang program must be stored in a file with a `.pokeball` extention


Disclaimer
----------
This is a fan-based parody of themes from [Pokémon] [3]. The language,
as well as its author, is in no way associated with the Pokémon francise
and its creators, nor is this project, in any way, for-profit.

[1]: http://esolangs.org/wiki/Pikalang
[2]: http://en.wikipedia.org/wiki/Brainfuck "Brainfuck"
[3]: https://www.google.com/search?q=pikachu&tbm=isch "Pikachu"
[4]: http://www.pokemon.com/ "Pokémon"
