This repository contains files supporting the paper

> MacKenzie, Laurel, and Mary Robinson. To appear. Spelling out grammatical variation. In *Sociosyntax: Current Approaches*, 
ed. Daniel Duncan and Mary Robinson. Berlin: Mouton De Gruyter.

In addition to this readme, the repository contains:

- LVC_JSlx_gramm_var_database.csv: a database of grammatical variables in published studies in *Language Variation and Change* and 
*Journal of Sociolinguistics* from their first year of publication to the end of 2023
- LVC_JSlx_gramm_var_database.Rmd: an R Markdown file analyzing the data

The database can also be browsed at [this link](https://docs.google.com/spreadsheets/d/1VzFpmDeR5bj1UBG5qSeEpZxatuUKQS8EJiTOrf8r-1Y/edit?usp=sharing).

Changes and corrections to the database are welcome: feel free to create a [GitHub issue](https://github.com/laurelmackenzie/grammatical-variation-metastudy/issues),
or submit them to Laurel by email ([laurel.mackenzie@nyu.edu](mailto:laurel.mackenzie@nyu.edu)).

## Database overview

The database contains grammatical variables published in the sociolinguistic literature, specifically from the entire catalog (up to the
end of 2023) of two journals, *Language Variation and Change* and  *Journal of Sociolinguistics*. We defined "grammatical variables,"
following Mansfield et al. (2023:234), as ''grammatical meanings or functions that can be expressed in more than one way.'' 
Each row of the database contains a single grammatical variable in a single language variety. Further information on how variables 
were identified for the database can be found in MacKenzie & Robinson §3.1 and §4.1.

Each variable is coded for whether it comprises variation in **form**, variation in **omission**, variation in **order**, or some
combination, following Mansfield et al.'s (2023:246–7) definitions of these variation types (elaborated below).

Each variable is also coded for whether its social significance was analyzed, and whether its social significance was found, across
three domains of sociolinguistic evidence: patterns of **production**, perceptual judgments (**perception**), and 
**metalinguistic behaviors**.

Each variable is also coded for the **language and variety** it was studied in, and for whether it was explicitly mentioned as being
the target of **overt prestige/overt stigma**.

Detailed descriptions of the database columns follow.


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
- **variation.type**: one or more of the following options, as applicable, following Mansfield et al. (2023):
  - **form**: variants have the same structure, but are distinguished by the form of a grammatical marker (either affix, clitic, or function word).
  - **omission**: variants are identical except that a grammatical marker is present in one but absent in the other.
  - **order**: variants use the same lexical and grammatical elements, but are distinguished by linear ordering. (Mansfield et al. 2023:246–7)
- **social.significance**: the extent to which social significance was analyzed for the variable:
  - **not analyzed**: social significance was not analyzed for the variable in any domain
  - **null**: social significance was analyzed for the variable in some domain(s), but not found (i.e. the paper reported only 
  [a] null social result[s] for the variable)
  - **x**: social significance was analyzed for the variable in some domain(s) and found
- **production**: the extent to which social significance was analyzed for the variable in the domain of production:
  - **not analyzed**: social significance was not analyzed for the variable in any domain
  - **null**: social significance was analyzed for the variable in some domain(s), but not found (i.e. the paper reported only 
  [a] null social result[s] for the variable)
  - **x**: social significance was analyzed for the variable in some domain(s) and found
