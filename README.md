Biometrics template and layout for LyX
======================================

Exactly what it says: a `.layout` file and template for the journal Biometrics, based on the LaTeX template [available here](http://www.biometrics.tibs.org/latexdocumentclass.htm).

All things that belong to TIBS remain their property!


## Getting it to work

1. Download the package here.
2. Install the `biom.cls`, `biom.bst` where ever is appropriate for your LaTeX distribution (see [here for more information](https://en.wikibooks.org/wiki/LaTeX/Installing_Extra_Packages)).
3. Install the `biom.layout` file by copying it to the `layouts` folder of your user directory (see [info here](https://wiki.lyx.org/LyX/UserDir) on user directories).
4. Copy `biomtemplate.lyx` and `endrotfloat.sty` to where you want to write your paper and start editing!

## Other stuff

- Adding authors happens in the preamble `Document > Settings... > LaTex Preamble`
- If you want to use `referee` mode for the document (probably yes?) then set `Document > Settings... > Local Layout`

```
ClassOptions
  Other referee
```

