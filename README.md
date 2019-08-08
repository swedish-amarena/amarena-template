# amarena-template

pandoc templates for slides and documents.

Obviously you will need pandoc. Pandoc is probably in the repository
but if it is not, visit:

https://pandoc.org/installing.html


The folder *scripts* have the scripts I use. Add to path or move to ~/bin

The scripts assume a clone in home directory

To use the scripts just type

```
docArena <file>.md
or
slidesArena <file>.md
```

dependent on what type of document you are compiling

if you need a latex start-file go

```
pandoc -t latex --template \
$HOME/amarena-template/arenamall.latex \
<file>.md >> <file>.tex

```


