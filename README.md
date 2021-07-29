# orcidlink
LaTeX package to add an ORCID icon linked to the author's profile.

### Demo
See `example.tex` for a demonstration.
![Example](https://github.com/arpaiva/orcidlink/blob/master/example.png)

### Other approaches
There are a number of other approaches to add these links, such as:
 * [orcidlink in CTAN](https://ctan.org/pkg/orcidlink?lang=en)
 * [StackExchange discussion](https://tex.stackexchange.com/questions/275578/is-there-a-standard-way-to-include-orcid-in-tex-pdf) on different approaches
 * [TikZ and qag fonts approach](https://gugushvili.github.io/blog/2019/08/09/orcid)

These links describe a number of good ways to do this. Unfortunately, the CTAN orcidlink package by Leo Stein uses SVG paths which caused problems with my LaTeX installation so I've created a TikZ pure approach based on the third link.
