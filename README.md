# A Very Simple Collection of LaTeX snippets

This repository contains a number of snippets that can be used for added functionality in (Xe)LaTeX documents. All file names are comprised of (i) a prefix that indicates the general category and then (ii) a description of the contained code. To make use of them, I simply add `input{<../directory/snippet.tex>}` to my preamble (the path here is relative; depending on your folder structure an absolute path may be the more sensible option). 

I claim no ownership over any of these snippets. Most are likely the result of digging through forums and package documentations.

## The Prefixes

| Prefix    | Description                                                                |
| --------- | -------------------------------------------------------------------------- |
| fnc       | Added functionality by (re)defining commands                               |
| fonts     | Font settings (includes serif, sans serif, math, and mono)                 |
| lang-cite | Combination of document language (polyglossia) and citation format (biber) |
| pkg       | various `\usepackage{...}` statements with some initial setup code         |