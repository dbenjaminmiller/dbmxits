The DBMXITS font project
======================

DBMXITS is a slightly altered version of XITS. The line spacing has been changed.

DBMXITS is a Times-like typeface for mathematical and scientific publishing, based
on [STIX fonts][1]. The main mission of DBMXITS is to provide a version of STIX
fonts enhanced with the OpenType `MATH` table, making it suitable for high
quality mathematic typesetting with OpenType math-capable layout systems, like
Microsoft Office 2007+, XeTeX and LuaTeX.

DBMXITS fonts are distributed under the [Open Font License][2], version 1.1.

Contributing
------------

The preferred way for modifying the fonts is by editing the SFD files under
`sources` directory in the [source repository][5], using [FontForge][3]. When
submitting patches, please make sure they are as clean as possible, avoiding
any unrelated or unnecessary changes.

To build the fonts from source you need GNU Make, [FontForge][3] Python module,
and [FontTools][4].

[1]: https://www.stixfonts.org
[2]: https://scripts.sil.org/OFL
[3]: https://fontforge.github.io
[4]: https://github.com/fonttools/fonttools
[5]: https://github.com/alif-type/xits
