---
layout: post
title: "Make Your Texts Harder To Trace"
date: 2025-10-21
author: "evenblad3"
tags: [obfuscate, cyrillic, homoglyph, unicode, glpyhshift, text]
description: "Make your texts harder to trace with GlpyhShift"
readtime: "1min"
category: privacy
---

So when someone tries to searches for your texts, it shows up, right? It's because you typed them in normal English like everyone else would. And that's what we're going to make it harder to trace. For example:

Normal text in Latin letters:
```
I love my government!
```

Obfuscated homoglyph text:
```
Ι lоvе mу ɡоvеrnmеnt!
``` 

## Using Letters From Different Languages
A lot of letters from other languages are similar to English letters, like the following example.
<table cellspacing="0" cellpadding="0">
	<tr>
		<th>English</th><th>Cyrillic</th><th>Greek</th>
	</tr>
	<tr>
		<th>A</th><th>А</th><th>Α</th>
	</tr>
	<tr>
		<th>B</th><th>В</th><th>Β</th>
	</tr>
	<tr>
		<th>C</th><th>С</th><th><i>N/A</i></th>
	</tr>
</table> 

[[source: Wikipedia]](https://en.wikipedia.org/wiki/Wikipedia:Language_recognition_chart)

## GlyphShift
What if there was a tool to automatically change the given text and obfuscates them? That's why [GlyphShift](https://github.com/evenblad3/GlyphShift) exists! The tool automatically copies the given normal text into the one we want.

Clone the repo:
```bash
git clone https://github.com/evenblad3/GlyphShift
```

Compille with this command:
```bash
g++ main.cpp -o main.exe
```

And finally run:
```bash
main.exe
```

And now it asks for your input, enter your text and the result will be automatically copied to your clipboard.
