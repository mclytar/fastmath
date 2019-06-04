# FastMath

This package contains abbreviations and useful definitions for the most common symbols that I use in a math environment.

## Usage

Place anywhere the file `fastmath.sty` and use it in your code:
```
\usepackage{fastmath}
```

All options are disabled by default (i.e. the above code does barely nothing).
You can enable some features using the corresponding option:
```
\usepackage[calfont,scrfont,frakfont]{fastmath}
```
Or you can enable every (non-colliding) feature using the particular option:
```
\usepackage[allfonts]{fastmath}
```

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

### Other

- `everything`: apply all the above options that do not collide (i.e. if `\something` has two different definitions in two different options, then it must be activated manually by specifying one of the two options)

## Naming convention

There are no particular rules to follow at the moment, but I plan to add them later.

## Additional notes

I expand this file/repository while writing my Master Degree Thesis or, more in general, whenever I need new shorthand notations.
Also, this repository contains definitions that I consider useful for myself but can be useless for you, use at your own risk! ;)