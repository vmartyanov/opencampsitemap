# How to add an additional language

Lets say we want to add Zulu language as an example. Zulu langage code is
"zu".

1. Add a flag icon named <b>zu.png</b> into the lang directory (25 px height)
   (The flag of South Africa should be your best bet in this case :)
2. Modify the existing index.html.* files to also show your icon
   (would be `<img src="lang/zu.png" title="zulu">` in the Zulu case)
3. Copy index.html.de to index.html.zu and translate into Zulu langage
4. Also change the lang variable insite index.html.zu to "zu"
5. Finaly add Zulu translations into l10n.js and facilities.js

