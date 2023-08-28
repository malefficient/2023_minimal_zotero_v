This is a running explanation of the changes we make to our 
* Tinkering around with the "Import output paths..." 
Check out the  [what is an export format documentation ](https://github.com/mgmeyers/obsidian-zotero-integration/blob/main/docs/Export%20Settings.md)


## All About {{CiteKey}}
Okay, so if you are convinced you need some sort of unique (enough) citation hash generator, what would to do about it? 
Something like this
![[IMG-CiteKeySetting]]
![[IMG-citekey-generation.png]]

According to the documentation, we can actually do a lot with these citekeys.

And given how critical they are going to be in the functioning of the rest of our obsidian setup, lets take a moment to think about our own locate site key generation

### Sea-lab lab cite-key format-
It's not written in stone or anything (In fact i'd like to prepend a 4-byte SLRC header, but:)
```
authEtal2(sep='_').upper + '_' + year
```
![[IMG-citekey-custom.png]]


## Contenders
I think i would like
APRC-YYYY-MM-DD
## examples
`APRC-2020-03
`APRC-2020-00` <-- the 00 means not present
`APRC-0000-00`


Getting there:
Well, we have  the len() function at our disposal, lets start with that
``` python
ARPC-libraryID-
if (len(date)) >
```






# JCRET2HERE
## import output path
For now, this is[set to](https://github.com/malefficient/2023_minimal_zotero_v/blob/8adcd5b36a3c634fc78240ed59401cac2d867b78/.obsidian/plugins/obsidian-zotero-desktop-connector/data.json) `from_Z` in the plugin settings



