# Python-LaTex-IPA
If you are looking for a Python script for generating a LaTex command(s) for the given International Phonetic Alphabet (IPA), then you are at the right place. `Python-LaTex-IPA` is a small Python script for doing such work neatly.

If you have ever considered looking up a dictionary, regardless of it is type: paper dictionary or online, you came up with some special characters appearing beside the word (for example word: _excellent_, /ˈɛks(ə)l(ə)nt/). These special characters (i.e., enclosed in obliques) are the International Phonetic Alphabets (IPA), which corresponds to a sound for each letter. Thus, with the help of the IPA sequence, you can identify the correct pronunciation of the word.

It is a very tedious task for the researchers and authors of scientific papers with LaTex typesetting to write IPAs for the words which are not in the English language. In this regard, `Python-LaTex-IPA` helps them to generate the (almost) correct LaTex commands to produce IPA.

#### Requirements
 - Python (preferably 3.X)
 
#### LaTex Packages
 - `tipa`
 - `phonetic`
 - `semtrans`
 - `upgreek`
 
 You can add these module in LaTex preamble as: 
```
\usepackage{tipa}
\usepackage{phonetic}
\usepackage{semtrans}
\usepackage{upgreek}
 ```
