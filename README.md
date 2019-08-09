# amarena-template

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


