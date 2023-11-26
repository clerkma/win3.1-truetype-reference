
It is a very early version of TrueType Reference (Microsoft Windows 3.1+).
I found it in a software archive.

Clerk Ma, 2023/11/26.

# Contents

* `DOC/*`, *TrueType Reference* in `.doc` format
* `HLP/TTFHELP.HLP`, *TrueType Font Specifications Help*
* `TXT/EMBEDDIN.TXT`, *Technical Information for ISVs Implementing TrueType Font Embedding under Microsoft Windows 3.1 and Windows NT*
* `TXT/LUCIDA.TXT`, *LUCIDA FAMILY OVERVIEW*
* `TXT/TT1.TXT`, *TrueType Technical Talk #1: An Introduction to Digital Typography using TrueType*
* `TXT/TT2.TXT`, *TrueType Technical Talk #2: Linear vs. Non-Linear Scaling*
* `EXE/TTFDUMP.EXE`, *TrueType v1.0 Dump Program*
* `EXE/TTFNAME.EXE`, *TrueType Parsing Demo*
* `TTFNAME/*`, source of `EXE/TTFNAME.EXE`

# Programs

## `EXE/TTFDUMP.EXE`

```
TrueType v1.0 Dump Program - v1.42, 10/9/91, rrt, dra
Copyright (C) 1991 ZSoft Corporation. All rights reserved.
Portions Copyright (C) 1991 Microsoft Corporation. All rights reserved.

Usage: TTFDUMP <filename> [-nNNNN] [-tCCCC] [-h]
	<filename>  - TrueType .TTF (or .T2 or .ROY) filename
	-nNNNN      - NNNN = glyph index number to dump (decimal value)
	                     (may also be 'x' to suppress glyph dumping).
	-tCCCC      - CCCC = table name (1-4 characters) to dump.
	-h          - Supress the font file header information.
```

## `EXE/TTFNAME.EXE`

```
usage: ttfname *.ttf
```