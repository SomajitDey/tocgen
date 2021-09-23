# TOC Generator for Markdown documents

![Bash-only](https://img.shields.io/badge/Made%20with-Bash-green) ![GNU/Linux](https://img.shields.io/badge/Platform-GNU%2FLinux-violet) ![CLI](https://img.shields.io/badge/UI-Command--line-brightgreen)

The below "Table of Contents" has been generated using `tocgen`.

## Table of Contents  
[![tocgen](https://img.shields.io/badge/Generated%20using-tocgen-blue)](https://github.com/SomajitDey/tocgen)  
  - [TOC Generator for Markdown documents](#toc-generator-for-markdown-documents)  
      - [Usage](#usage)  
          - [Step 1](#step-1)  
          - [Step 2](#step-2)  
          - [Step 3](#step-3)  
      - [Known issue(s)](#known-issue(s))  
          - [[Example mess](https://example.com)](#[example-mess](https://example.com))  
      - [Contribute](#contribute)  
#####   

### Usage

##### Step 1

Put the placeholder `[TOC]` **followed by 2 spaces and a new-line** (viz. press Enter key) wherever you want the *Table of Contents* to appear in your markdown file.

##### Step 2

Then simply:

```bash
tocgen <path to the markdown file>
# If path is not provided, tocgen searches its working directory for *.md files
```

It does an in-place edit of the file provided. The injected "Table of Contents" contains a trailing blank level 5 heading. **DO NOT** delete this blank heading as `tocgen` uses it to delimit the "Table of Contents" during subsequent updates (see below).

##### Step 3

Edit your document as necessary - adding, editing and removing headings. When you finish editing, in order to update the "Table of Contents", simply repeat the command given above.

### Known issue(s)

Can't manage headings with links properly, yet. That is to say, headings such as `### [Heading](https://some.link)` would also show the link in the TOC and mess the anchor up. See the demo heading below.

##### [Example mess](https://example.com)

### Contribute

Report [bugs](https://github.com/SomajitDey/tocgen/issues) or [discuss](https://github.com/SomajitDey/tocgen/discussions) ideas and new features. [PR](https://github.com/SomajitDey/tocgen/pulls)s welcome.

[![Sponsor](https://www.buymeacoffee.com/assets/img/custom_images/yellow_img.png)](https://buymeacoffee.com/SomajitDey)
