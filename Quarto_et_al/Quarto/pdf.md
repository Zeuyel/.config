---
title: "My Document"
author:
  - "吴彦祖"
date: "2023.12.4"
date-format: "YYYY.MM.DD"
toc: true
number-sections: true
shift-heading-level-by: -1
monofont: "Consolas"
crossref:
  chapters: true
  fig-title: 图    # (default is "Figure")
  tbl-title: 表     # (default is "Table")
  title-delim: "-"  # (default is ":"), not for pdf
  fig-prefix: 图  # (default is "Figure")
  tbl-prefix: 表    # (default is "Table")
format: 
  pdf:
    # toc
    toc-depth: 3
    toc-title: Contents
    # cite
    cite-method: biblatex # biblatex,citeproc
    bibliography: "C:\\Users\\Epictus\\Documents\\Quarto\\ref.bib"
    biblio-title: References
    # output
    documentclass: article # scrartcl，article, report or book
    papersize: a4 # a4, letter
    colorlinks: true
    #classoption: [twocolumn,landscape] 
    keep-tex: true
    fig-pos: 'H'
    tbl-cap-location: top
    fig-cap-location: bottom
    listings: false
    code-block-bg: '#f6f8fa'
    highlight-style: github
    code-block-border-left: false
    geometry:
      - top=30mm
      - left=20mm
      - heightrounded
    include-in-header:
      text: |
        \usepackage{ctex}    % CJK 包
        \usepackage[backend=biber,style=gb7714-2015,gbnamefmt=lowercase]{biblatex}
        \usepackage[dvipsnames]{xcolor}
        \setCJKmainfont[AutoFakeBold = {2.25}]{宋体}
        \setmainfont{Times New Roman} %英文字體調整
        \usepackage{caption}
        \captionsetup[figure]{labelformat=simple, labelsep=period}
        \captionsetup[table]{labelformat=simple, labelsep=period}        

---