## Front Matter -- for LaTeX
author:
  - Dean's Report
#  - Danny Quah `\\\\`{=latex} Lee Kuan Yew School of Public Policy, NUS `\\\\`{=latex} D.Quah@nus.edu.sg
#  - My Coauthor `\\\\`{=latex} Economics Department, NUS `\\\\`{=latex} ecsdqlsh@nus.edu.sg
#author:
#  - name: Danny Quah
#    affiliation: Lee Kuan Yew School of Public Policy, NUS
#    email: D.Quah@nus.edu.sg
#    number: 1
#  - name: My Coauthor
#    affiliation: Economics Department, NUS
#    email: DannyQuah@u.nus.edu
#    number: 2
date: Dec 2020
# abstract:
# keywords:
# thanks:

## Formatting -- for LaTeX
fontsize: 12pt
# mainfont: "gentium" # See https://fonts.google.com/ for fonts
# sansfont: "Raleway"
# monofont: "IBM Plex Mono"
mathfont: ccmath
# fontfamily: concrete | gentium | libertine
# documentclass: article | scrartcl
fontfamily: concrete
documentclass: article
classoption:
 - notitlepage
 - onecolumn
fontenc: T1
geometry:
 - a4paper
 - top=35mm
 - left=30mm
 - heightrounded
colorlinks: true
urlcolor: blue
header-includes:
 - \usepackage{amsmath,amsfonts,euscript}
 - \usepackage{tikz,float}
 - \floatplacement{figure}{H}
 - \usepackage{fancyhdr}
 - \setlength{\headheight}{15pt}
 - \pagestyle{fancy}
 - \fancyhf{}
 - \renewcommand{\headrulewidth}{0.2pt}
 - \renewcommand{\footrulewidth}{0.2pt}
 - \fancyfoot[C]{\thepage}
---
\thispagestyle{empty}% Put this at the start of the text contents
