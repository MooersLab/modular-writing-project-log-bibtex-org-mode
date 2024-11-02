![Version](https://img.shields.io/static/v1?label=modular-writing-project-log-bibtex-org-mode&message=0.1&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)


# Template for the modular form of the writing project log file with BibTeX for use in org-mode

## Problem addressed
This is a tool for planning and managing a specific writing project.
This tool can be applied to any kind of project that requires effort over multiple days: e.g., lecture and talk preparation.

The primary purpose of this tool is to improve the clarity of thinking about a writing project and thereby accelerate its completion and improve its impact.
Its secondary purpose is to enable the speedy resumption of an interrupted project.
A side effect of using this template is the easing of the fear of forgetting (FoF) where you left off on a project and the fear of the loss of momentum (FoLM).
The side effects grow proportionately with the use of the template.


## Why org-mode?
Org-mode greatly eases the assembly and manipulation of the lists that are used in various aspects of a writing project.
Org-mode interfaces with several other tools in the org ecosystem that aid time management and knowledge management, like org-agenda and org-roam.
It has interfaces with \LaTeX and Pandoc that enable the exporting of org files to many formats.

The drawback to org-mode to some is that it is best utilized in Emacs.
However, over the past decade, the power of org-mode has drawn many young users to Emacs.

## Why this variant?
This modular template has the added feature of enabling the import of select workflows, protocols, and guidelines from a central folder.
This enables customization of the log file for the project at hand and a reduction of the clutter in the org-mode document.
While this clutter can be hidden in drawers, drawers can confuse beginners.

The protocols can be updated in a central location so that they are updated in all projects that source the protocol file.
Variant protocols to meet the needs of a specific project or subgroups of projects can be substituted for the standard protocols.
A protocol folder with the workflow protocols is included for inspiration.

The org-mode `#+INCLUDE:` command or the LaTeX `\input` commands are used.
The included files can be written in LaTeX or org-mode.
These files can be viewed in other buffers by double-clicking on their file paths.

## Releated variants

- An org-mode variant that uses BibLaTeX instead of BibTeX
- Variants that use LaTeX, R Markdown, and Typst.

## Cautions
The downside of this modular approach is the texts from the imports are only visible inside the main document after export from org-mode to HTML, PDF, MS Word, or whatever.
Most people will spend most of their time interacting with the org file rather than the output file.
If you wish, you can always copy and paste select protocols into the appropriate locations in the org file to improve access. 

Alternately, as mentioned above, you can use the file path in the include or input statement to open the file of interest in another buffer in Emacs.
The latter flexibility is part of the joys of using org-mode and Emacs.


## Update history

|Version        | Changes                                                                                                                                         | Date                      |
|:----------------|:------------------------------------------------------------------------------------------------------------------------------|:-------------------------|
| Version 0.1 |   Added badges, funding, and update table. Initial commit.                                                            | 2024 November 2 |

## Sources of funding

- NIH: R01 CA242845
- NIH: R01 AI088011
- NIH: P30 CA225520 (PI: R. Mannel)
- NIH: P20 GM103640 and P30 GM145423 (PI: A. West)# modular-writing-project-log-org-mode-bibtex