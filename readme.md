# Tenforce Report Typesetting

A quick and dirty environment for typesetting TenForce reports in [Pandoc Markdown](http://pandoc.org/MANUAL.html#pandocs-markdown).


## Installation

1. Requires Pandoc and TexLive. For Ubuntu:

```
sudo apt-get install pandoc
sudo apt-get install texlive
```

2. Edit the first line of ./typeset to point to the installation directory.

3. Add ./typeset to your path:

```
export PATH=$PATH:/path/to/tenforce-report-typesetting/typeset 
```

## Usage

To typeset the file `./report.md` (works only in the current directory):

```
typeset report
typeset report docx
typeset report odt
```

By default, uses the templates in this repository. Default templates can be overridden by files with same filenames in the current directory.

