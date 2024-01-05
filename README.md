## What is it?

Traité de la *tabula* (a.k.a "``traite``" as its command-line name) is a static
documentation generator written purely in Korn Shell --- more specifically,
[KSH-93](http://www.kornshell.com/doc/ksh93.html). It uses
[Pandoc](https://pandoc.org) for converting from Markdown to HTML and,
indirectly, [XeTeX](https://tug.org/xetex/) as the default (La)TeX engine.  

### TODO

* Multi-language/Translation support (maybe similar to MkDocs?);
* Safer (and possibly more complex) ``nuke`` function, that deals correctly with
  the new translation feature. 

### Hacking

> Although Traité was made just in two days, its code is fairly readable even for
ones who does not actually code in Shell script. After around three years of
experience, I have been able to keep a consistent and sane code-style.
> Good references for learning Korn Shell are O'Reilly's "Learning the Korn Shell,
2nd Edition" and, for Portuguese speakers, "Programação Shell Linux" --- that
tries to cover all the UNIX shells and its differences, from GNU Broken-Again
Shell to even the (crappy) POSIX standard.  
> "Learning the Korn Shell" is a paid book --- but I have heard it from the
grapevine that it can be found for free in some website from Ukraine, the domain
name rhymes with "milk".  
> "Programação Shell Linux" is also a paid book --- but I also have heard that a
fairly older version, from around 2010, can also be found in some website whose
name rhymes with "doceiro" (a Portuguese word for "confectioner").

Luiz Antônio Rangel, [from the original traite](https://github.com/Projeto-Pindorama/traite.old)

### Related projects

* [Silicon Tabula](https://github.com/Projeto-Pindorama/Silicon-Tabula) - All
  the Pindorama project *tabulas* (documentation), compiled in one repository;
* [acme4real](https://github.com/takusuman/acme4real#screenshots-pandoc-port) -
A Vim colorscheme heavly inspired by ``acme``(1) by Rob Pike, but with actual
syntax highlighting (Pandoc port);
* [Pandoc Goodies](https://github.com/tajmone/pandoc-goodies) - A teasure-box of
  resources for Pandoc, PP and Texts word processor;
* [Pandoc](https://pandoc.org) - A universal document converter;
* [XeTeX](http://xetex.sourceforge.net) - Unicode-based TEX;
* [ksh93](http://www.kornshell.com) - The KornShell Command And Programming
Language.

## Licence
The license is written on each file. If there's no license, it's licensed under the MIT license, with an exception to the files at the ``boilerplate/`` directory, which are licenced under Public Domain. 
