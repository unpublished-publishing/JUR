<!-- Editor only
*Journal of Unpublished Research, Volume X, Paper X, DATE* -->

# TITLE

###### AUTHOR ONE<sup>1</sup>, AUTHOR TWO<sup>2</sup>
<sup>1</sup> Affiliation 1
</br>
<sup>2</sup> Affiliation 2

# Abstract
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

This work is licensed under a [Creative Commons Attribution-NoDerivatives 4.0 International License](http://creativecommons.org/licenses/by-nd/4.0/).


##### Keywords
<Keyword 1>, <Keyword 2>

# Introduction

Please write according to [GitHub Markdown conventions](https://github.github.com/gfm/). The most common elements are:
 - item lists

1. numbered item
2. numbered item
1. numbered item (actual number doesn't matter)

[links](www.google.com), _italic_, *italic*, __bold__, **bold**

__Figures and online videos__ such as YouTube can be included the same way:

![Figure 1](http://img.youtube.com/vi/8UfaFnGtCrk/0.jpg)
<p style="font-size:x-small;"><span style="font-weight:bold;">Figure 1</span>: Figure caption.</p>

And videos can be added with poster frames as linked pictures:

[![Figure 2](http://img.youtube.com/vi/8UfaFnGtCrk/0.jpg)](http://www.youtube.com/watch?v=8UfaFnGtCrk "Watch on YouTube")
<p style="font-size:x-small;"><span style="font-weight:bold;">Figure 2</span>: A 30-second introduction to the Model of an idealized Moist Atmosphere (link to YouTube).</p>

As proper figure and citation referencing as we love it from LaTex does not work here, this needs to be done by hand. The way to __add references__ is directly via weblinks, preferrably doi links [[Jucker and Gerber (2017)](http://journals.ametsoc.org/doi/10.1175/JCLI-D-17-0127.1)]. That way, we do not need a separate references section (this is the 21st century!)

| Column 1 | Column 2 | Column 3 |
| :--      | :-:      | ---      |
| Lorem    | 3.4      | True     |
| Ipsum    | 42       | False    |

<p style="font-size:x-small;"><span style="font-weight:bold;">Table 1</span>: Table caption.</p>

# Maths
__Maths__ is another partly missing component here. The _Journal of Unpublished Research_ repository is setup with [TeXify](https://github.com/apps/texify) to render LaTeX commands within markdown. This is why the extension to this template is `.tex.md`. Embed all of the maths in dollar signs, just like in LaTeX. When uploading to JUR, all text between dollar signs will be converted to maths:

Inline equation: <img src="/papers/tex/4be9bdc715d42624aea2a801031dee3f.svg?invert_in_darkmode&sanitize=true" align=middle width=139.00879575pt height=28.26507089999998pt/>. Display equation:
<p align="center"><img src="/papers/tex/a7a17e29d81bf0e27fb93d79395bcf1e.svg?invert_in_darkmode&sanitize=true" align=middle width=145.4081574pt height=42.66009165pt/></p>
Or actual equation:
<p align="center"><img src="/papers/tex/473a15144911f984247f94da8ab0f64b.svg?invert_in_darkmode&sanitize=true" align=middle width=422.8410318pt height=42.66009165pt/></p>

If this sounds too spooky (it's not!), then there are two more options:

1. Use [html ampersand symbols](https://sites.psu.edu/symbolcodes/codehtml/#math) and greek letters, we can emulate a few simple things such as

```
&alpha;, &beta;, &Gamma;, &sum;<sub>i</sub>_x<sub>i</sub>_ &gt; &part;_f_/&part;_y_ + &prod;<sub>i</sub>_z<sub>i</sub>_
```
which renders as &alpha;, &beta;, &Gamma;, &sum;<sub>i</sub>_x<sub>i</sub>_ &gt; &part;_f_/&part;_y_ + &prod;<sub>i</sub>_z<sub>i</sub>_.

2. For more complicated formulae, either use the [CodeCogs online editor](https://www.codecogs.com/latex/eqneditor.php) and then copy-paste the resulting html code into the markdown file like so:

<a href="https://www.codecogs.com/eqnedit.php?latex=x&space;=&space;\frac{-b&space;\pm&space;\sqrt{b^2-4ac}}{2a}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?x&space;=&space;\frac{-b&space;\pm&space;\sqrt{b^2-4ac}}{2a}" title="x = \frac{-b \pm \sqrt{b^2-4ac}}{2a}" /></a>&emsp;(1),

or create an image with any equation editor and embed the image of the equation.

But the best and simplest way to do it is as described above, with simple dollar signs.

# Section title

## Subsection title

**Paragraph title:**
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

# Acknowledgments
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

<!-- Editor only
*Journal of Unpublished Research, Volume X, Paper X, DATE* -->

---

# Comments

<!-- leave blank, this is for post-publication comments -->
