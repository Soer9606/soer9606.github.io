# The Textbook

The Textbook is an attempt to make a free online textbook of high quality.

The project is still in its early phase, and ideas like open-source (to heavily populate the textbook with theory), design (should the textbook work with MathJax, or be pre-compiled to .pdf), and many other things are flying around the room.

Currently though, the focus is on filling the pages with knowledge, and the knowledge at the moment, is heavily focused on mathematics, as that is what I, the creator, am studying. I have started just writing the textbook in ordinary tex, but this may change, and it may in fact be stupid to start like this, when I might have to change to MathJax, and the two formats aren't entirely compatible.

## For collaborators

We are currently working on making this a collaborative project. This means getting an open source license, developing how the project should be developed, and some ground rules for developers.

If you want to help write the textbook, there are some rules (or guidelines) to follow:
1. Please, do not add more files. As we do not want the project to be crowded with half-finished small parts, and it is easier for us to proof-read small parts, we recommend that you work on or edit existing files. If you do however want to add new files etc. please ask the creator (Søren).
2. One of the goals of this textbook, is to, as far as possible, standardize notation. We know, that often standardizing something just adds a new way of doing something to the long list of existing ones. Therefore we will use existing notation, and most importantly we will as far as possible use the same notation throughout the textbook. This means that we for example will be using the same typeface for letters denoting a σ-algebra. Therefore, if you want a σ-algebra called A, you simply write `\sa{A}` where `\sa` referres to it being a **S**igma **A**lgebra. At the moment, `\sa` makes the A written in the mathcal font, but as this might change, it is very useful to have a command to standardize this notion.
What follows are some of these commands. All of them can be found in the mystyle.sty file.
  * `\pow{X}` is the powerset of X.
  * `\card{X}` is the cardinality of the set X.
  * `\N,\Z,\Q,\R,\C` are the natural numbers, the integers, the rationals, the reals, and the complex numbers respectively.
3. For cross-references always use `\label{desc: labelname}` and `\cref{desc: labelname}`. It is important to use the descriptors (here denoted `desc` and then a `:` followed by a space). Since the textbook is going to grow quite quickly in size, more guidelines should be added, but at the moment these are all. The descriptors are as follows:

| desc:   | Description
|---------|----------------|
| ch:     | Chapter        |
| sec:    | Section        |
| subsec: | Subsection     |
| fig:    | Figure         |
| tab:    | Table          |
| eq:     | Equation       |
| lst:    | Code listing   |
| itm:    | Itemize list   |
| enum:   | Enumerate list |
| alg:    | Algorithm      |
| app:    | Appendix       |
