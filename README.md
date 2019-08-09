# amarena-template

The templates in this repository are used for 
the **Swedish Arena for Additive Manufacturing of Metals**
(description below). 

These templates are made within the umbrella of the 
**Swedish Arena for Additive Manufacturing of Metals**
and are for their documents, but hopefully someone else can have use
for the templates and files outside of the arena.

All templates and files are licensed by the Creative Commons **CC BY-NC**
license except those that are based on the pandoc orig. templates:
description in LICENSE.md


## pandoc templates for slides and documents.

Obviously you will need pandoc. Pandoc is probably in the repository
but if it is not, visit:

https://pandoc.org/installing.html


The folder *scripts* have the scripts I use. Add to path or move to ~/bin

The scripts assume a clone in home directory ($HOME)

### To use the scripts just type

```
docArena <file>.md
or
slidesArena <file>.md
or
slidesArenadocx <file>.md
```

dependent on what type of document you are compiling. The first two
gives pdf:s as output whereas the second one gives a docx.

**Note**. The docx formatting is not complete because of the secret
character of the docx fileformat.

### Check out the sample.md file

extra for presentations: Easy collumn making:

```
\bco

\co

\co

\eco
```

### if you need a latex start-file go

```
pandoc -t latex --template \
$HOME/amarena-template/arenamall.latex \
<file>.md >> <file>.tex

```


# Swedish Arena for Additive Manufacturing of Metals

The Arena is a membership programme for Swedish actors in the field of
Additive Manufacturing of Metals. The Arena's ambition is to be a
meeting point for all key players and together develop the future 
of metal-AM in Sweden.

The aim of the Swedish Arena for Additive Manufacturing of Metals is
to:

- Develop a strong network in metal-AM between the participating partners
- Monitor and contribute to the development of technology and knowledge
- Provide easy access to test and demo platforms in metal-AM
- Support and accelerate industrialization of metal-AM

The objective of the Arena is to create a vehicle for open innovation to enable innovative
product development and manufacturing to support applied R&D in industrial metal additive
manufacturing.

**Url: http://www.am-arena.se**
