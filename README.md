This repository contains files supporting the paper

> MacKenzie, Laurel, and Mary Robinson. To appear. Spelling out grammatical variation. In *Sociosyntax: Current Approaches*, 
ed. Daniel Duncan and Mary Robinson. Berlin: Mouton De Gruyter.

In addition to this readme, the repository contains:

- LVC_JSlx_gramm_var_database.csv: a database of grammatical variables in published studies in *Language Variation and Change* and 
*Journal of Sociolinguistics* from their first year of publication to the end of 2023, annotated below
- LVC_JSlx_gramm_var_database.Rmd: an R Markdown file analyzing the data

The database can also be browsed at [this link](https://docs.google.com/spreadsheets/d/1VzFpmDeR5bj1UBG5qSeEpZxatuUKQS8EJiTOrf8r-1Y/edit?usp=sharing).

Changes and corrections to the database are welcome: feel free to create a [GitHub issue](https://github.com/laurelmackenzie/grammatical-variation-metastudy/issues),
or submit them to Laurel by email ([laurel.mackenzie@nyu.edu](mailto:laurel.mackenzie@nyu.edu)).

## Database overview

The database contains grammatical variables published in the sociolinguistic literature, specifically from the entire catalog (up to the
end of 2023) of two journals, *Language Variation and Change* and 
*Journal of Sociolinguistics*. We defined "grammatical variables," following Mansfield et al. (2023:234), as
''grammatical meanings or functions that can be expressed in more than one way.'' Each row of the database comprises a single 
grammatical variable in a single language variety. Further information on how variables were selected for the database can be found 
in MacKenzie & Robinson  §3.1 and §4.1.

## Database columns

- **journal**: journal of publication: LVC (*Language Variation and Change*) or JSlx (*Journal of Sociolinguistics*)
- **issue**: volume(number) of publication
- **year**: year of publication
- **author.s.lastnames**: last name(s) of author(s)
- **title**: title of publication
- **link**: link to publication
- **variable**: variable, as named and exemplified by the author(s)
- **variety**: variety in which the variable was studied, as named by the author(s)
- **language**: language in which the variable was studied, as named by the author(s)
- **variation.type**: one or more of the following options, following Mansfield et al. (2023):
  - Form: Variants have the same structure, but are distinguished by the form of a grammatical marker (either affix, clitic, or function word).
  - (b) Order: Variants use the same lexical and grammatical elements, but are distinguished by linear ordering.
  - (c) Omission: Variants are identical except that a grammatical marker is present in one but absent in the other. (Mansfield et al. 2023:246–7)