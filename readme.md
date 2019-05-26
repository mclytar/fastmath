# FastMath

This package contains abbreviations and useful definitions for the most common symbols that I use in a math environment.

## Usage

Place anywhere the file `fastmath.sty` and use it in your code:
```
\usepackage{fastmath}
```

All options must be enabled.

## Options

### Font face options

- `calfont`: use the `\cal*` abbreviations.
- `scrfont`: use the `\scr*` abbreviations.
- `frakfont`: use the `\frak*` abbreviations.
- `bbfontcommon`: use the `\**` abbreviations for common letters (i.e. the N, Z, Q, R, C, F fields, the generic field K, the quaternion ring H and the letter P for either probability or projective space).
- `bbfont`: use the `\**` abbreviations for all letters (**Note:** will override the commands `\AA` and `\SS`).
- `bffont`: use the `\bf*` abbreviations.
- `sffont`: use the `\sf*` abbreviations.
- `commonfonts`: use the above abbreviations for common letters (equivalent to `calfont,scrfont,frakfont,bbfontcommon`).
- `allfonts`: use all the above abbreviations.

## Additional notes

I expand this file/repository whenever I need new shorthand notations.
Also, this repository contains definitions that I consider useful for myself, use at your own risk! ;)