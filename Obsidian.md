---
tags:
  - Abraham_Sharnoff
---
Oh no! I'm in a weird ass software and don't know how to make my text pretty!
Don't worry, I got docs.

Obsidian accepts markdown, html, and latex syntax.
First tho, obsidian links between notes:
You do \[\[Name of note\]\] and you've got yourself a link.
Like this: [[Obsidian]]
Want to change the name shown?
[[Obsidian|Bam]]
Want to link to something external?
[pow](https://en.wikipedia.org/wiki/Dementia)
Want to link to a specific header of a note?
[[Obsidian#Markdown]]
Congratulations, you now know obsidian link syntax.
# Markdown
\*text\* for *italics*
\*\*text\*\* for **bold**
\--- after a line with text will put that line as a header, while after an empty line, it will put a line across like this:

---
You can have the three headings by starting a line with #, a space, then the text of the heading.
You can get the smaller headings by using multiple #, going all the way to 6.
<pre>
# A large heading for a main section
## A subsection
### A sub-subsection
</pre>
You can also have code blocks with \`\`\`
<pre>
```
Code block
```
</pre>
Which looks like this:
```
Code block
```
However, of course, us nerds do *love* our pretty colo(u)rs, so if the code is in a specific language, put the name of the language here
<pre>
```name
code
```
</pre>
# HTML
It accepts most styling html tags, tf you want?
In all seriousness, I ain't writing all that.

But I am writing some of it.
\<pre> does <pre>this</pre>
\<code> does <code>this</code>
\<sub> does <sub>this</sub>
\<sup> does <sup>this</sup>
# Latex
Fucky shit this is.
\$math\$ for $inline$
\$\$
math
\$\$
for
$$
block
$$
Blocks will make themselves taller if needed, inline will shrink the visual

I also am not going to go into the nitty gritty of this
{} for grouping things because all of the future shit will just take 1 character if you let it
\_ for $_{subscript}$
^ for $^{superscript}$
\frac for $\frac {frac} {tions}$
\sqrt for $\sqrt {square roots}$
\pm for $\pm$
\mp for $\mp$
\infty for $\infty$
\dots for $\dots$
Some of the things modify others, like how if you give \sum \_ or ^, it won't do normal sub or superscript, it'll do this:
$$
\sum_{i=7}^{10}
$$
Same thing happens with \prod (which does exist in math)

---
Congratulations, you now can format shit pretty.