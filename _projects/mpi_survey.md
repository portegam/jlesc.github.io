---
layout: page_project
title: International MPI Survey
date: 2019-02-15
updated:
navbar: Research
subnavbar: Projects
project_url: https://github.com/bosilca/MPIsurvey
status: running
topics:
  - prog_lang
keywords:
head: hori_a
members:
  - bosilca_g
  - jeannot_e
  - ogura_t
---
{% comment %}
================================
=== HOW TO USE THIS TEMPLATE ===
================================

Copy this file to `_projects` and rename it to a very short version of your project's title, e.g.
the project "Scalability Enhancements to FMM for Molecular Dynamics Simulations" chooses
"fmm_project.md".

Also copy the file `_templates/project.bib` to `_bibliography/external` and name it exactly as this
one, but the file extension, e.g. "fmm_project.bib".

For citing references, use the Liquid citing syntax as explained in the wiki:
https://github.com/JLESC/jlesc.github.io/wiki/Markup-Language#cite-and-list-publications

!IMPORTANT!
Remember to adjust the file name of the BibTeX file at the very bottom of this file!!

Then fill in the YAML header variables above.

  title            (required)
                   the full title of the project
                   WARNING: do not use quotation marks, colons and the likes

  date             (required)
                   the date this page was created in the format: YYYY-MM-DD; this will get displayed
                   at the very bottom of the generated website

  updated          (optional)
                   in case you or somebody else came back later and edited significant parts of the
                   page, put in the date (format: YYYY-MM-DD) of that change;
                   if present, this will get displayed at the very bottom of the generated website

  project_url      (optional)
                   optional URL to some external website of the project.

  status           (optional)
                   the current status of the project;
                   you have to use one of the keys defined in '_data/project_states.yml'

  topics           (required)
                   a YAML list of topic keys (as defined in '_data/topics.yml') for this project;
                   each topic on a new line with a leading dash

  keywords         (optional)
                   a YAML list of keywords for this project;
                   each topic on a new line with a leading dash.

  head             (required)
                   the dedicated project leader;
                   this is the identifier of a person as found in '_data/people.yml'

  members          (optional)
                   a YAML list of members of this project excluding the head;
                   each member must be listed as its identifier as found in '_data/people.yml'

Now, fill in the details for the current report below. Please do not change headings, headings level
or order.
Read the comments carefully!

{% endcomment %}

## Research topic and goals

As part of a wide effort to understand the current usage of the Message Passing
Interface (MPI) in the development of parallel applications and drive future
additions to the MPI standard, the objective of this project is to get feedback
from the largest MPI audience (past, current and potential users) to get a
better understanding of their needs, and the impact of different MPI
capabilities on the process of developing distributed applications. Since this
questionnaire survey will be distributed worldwide, it is also expected to
reveal country/region differences on the above aspects.

We believe this kind of international survey is suitable for the vision of
JLESC. This kind of International MPI survey would be another type of
collaboration in JLESC to obtain the insights into Exascale computing. This
survey will be a touchstone of following JLESC survey projects.

## Results for 2018/2019

As of 02.2019 the design of the questionnaire survey is almost done. It will be
distributed and collected by the end of February 2019. The first draft report
will be presented in JLESC workshop in Knoxville, 2019.


## Visits and meetings


## Impact and publications

<!--
{% comment %}
=============================
== CITING OWN PUBLICATIONS ==
=============================

You can list your own publications below in case you did not cite them in the text
(which you should do, though).
Use the Liquid citing syntax as explained in the wiki:
https://github.com/JLESC/jlesc.github.io/wiki/Markup-Language#cite-and-list-publications
Remember to use the `--file jlesc.bib` with the `cite` tag.

=====================================
== START HERE WITH YOUR ADDITIONAL REFERENCES ==
{% endcomment %}



{% comment %}
== NO MORE BELOW THIS ==
========================
{% endcomment %}
-->

{% bibliography --cited --file jlesc.bib %}


## Future plans


## References

{% comment %}
=================
=== IMPORTANT ===
=================

Replace 'YOUR_BIBTEX_FILE_NAME_HERE' with the name of the BibTeX file with the external references!
{% endcomment %}

{% bibliography --cited --file jlesc.bib %}
