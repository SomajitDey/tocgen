# TOC Generator for Markdown documents

The below "Table of Contents" has been generated using `tocgen`.

## Table of Contents  
[![tocgen](https://img.shields.io/badge/Generated%20using-tocgen-blue)](https://github.com/SomajitDey/tocgen)  
  - [TOC Generator for Markdown documents](#toc-generator-for-markdown-documents)  
      - [Usage](#usage)  
          - [Step 1](#step-1)  
          - [Step 2](#step-2)  
          - [Step 3](#step-3)  
      - [Contribute](#contribute)  
#####   

### Usage

##### Step 1

Put the placeholder `[TOC]` followed by 2 spaces and a new-line (viz. press Enter key) wherever you want the Table of Contents to appear in your markdown file.

##### Step 2

Then simply:

```bash
tocgen <path to the markdown file>
```

If path is not provided, `tocgen` searches its working directory for `*.md` files

It does an in-place edit of the file provided. The injected "Table of Contents" contains a trailing, blank, level 5 heading. **DO NOT** delete this blank heading as `tocgen` uses it to delimit the "Table of Contents" during subsequent updates (see below).

##### Step 3

Edit your document as necessary - adding, editing and removing headings. When you finish editing, in order to update the "Table of Contents", simply repeat the command given above.

### Contribute

Report [bugs](https://github.com/SomajitDey/tocgen/issues) or [discuss](https://github.com/SomajitDey/tocgen/discussions) ideas and new features. [PR](https://github.com/SomajitDey/tocgen/pulls)s welcome.

[![Sponsor](https://www.buymeacoffee.com/assets/img/custom_images/yellow_img.png)](https://buymeacoffee.com/SomajitDey)
