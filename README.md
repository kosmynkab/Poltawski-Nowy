# Poltawski-Nowy
The repository for the Półtawski Nowy typeface

<h1>Półtawski Nowy</h1>

<h5>Description</h5>
Półtawski Nowy is a digitisation project the Antykwa Półtawskiego typeface. A key aspect of the design of the digital version of the typeface from 1928 was the approach to the issue of developing the shape of characters from sources. Historical research was carried out in parallel with the preparation of the computer version, which allowed us to learn about the unique story of this most recognizable Polish font design. The Półtawski Nowy type family is intended for typesetting in sizes from 10 to 18 pt. It includes 6 instances (3 upright and 3 italic weights) and is available for download under an open font license. The project is implemented thanks to the support of the Digital Culture 2020 program of the Ministry of Culture and National Heritage.

<h5>Expansion</h5>
In the Półtawski Nowy digitisation, the source of the study were scans of a type specimen book from the Idźkowski i S-ka foundry, a set of drawings, punch patterns and punches made by Monotype in Salfords, Great Britain in 1934-1955. They were made available to us by the Type Archive London. Thanks to the standardization of characters and the balancing of the typographic rhythm, in the digital version, the typeface retains its ornamental character, while working well in smaller text sizes. The basic character set available in the sources has been extended with further variants of diacritics, small caps, subscript and superscript, variants of numbers (tabular, proportional, nautical) and a set of OpenType features.

The typeface is brought up to the Google Latin Plus character set thanks to the support of Google Fonts.

<h5>Build the fonts</h5>
  
When you push modifications in the sources directory on the main branch, github will perform some actions on these changes: It builds the fonts for you and check with Fontbakery if the builds pass Google Fonts Quality Assurance Checks. If you want to download the package containing the fonts and the report, go to the [Action tab](https://github.com/kosmynkab/Poltawski-Nowy/actions), click on the last action (which carries the name of your last commit) and there you will find a package to download (PoltawskiNowy_Fonts) in the "Artifacts" section.

If you want to build the font locally. First, install `gftools` in a virtual environment (anywhere but preferably in your local repo, and not in icloud):

```
$ python3 -m venv env
$ source env/bin/activate
$ pip install gftools
```

Then, you can build the fonts with this command:
```
$ cd path/to/sources
$ gftools builder config.yaml
```

Make sure you always activate the virtual env beforehand, each time you want to build (`$ source env/bin/activate`)

<h5>Designers involved</h5>
Półtawski Nowy was a collaborative project of Mateusz Machalski, Borys Kosmynka, and Ania Wieluńska.

Copyright
Copyright 2020 Mateusz Machalski (info@machalski.wtf), Borys Kosmynka (info@kosmynka.com), Przemysław Hoffer, Ania Wieluńska.

<h5>License</h5>
This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is copied below, and is also available with a FAQ at: https://scripts.sil.org/OFL
