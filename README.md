# Wikipedia Gender Bias Detector

**Algorithmic bias audit tool for Wikipedia biographies of women.**

## 🚀 Live Tool

> **The tool has moved to Wikimedia Toolforge and is now permanently hosted there.**

### ➡️ [gender-bias-detector.toolforge.org](https://gender-bias-detector.toolforge.org)

The GitHub Pages version at `nethahussain.github.io/wikipedia-gender-bias-detector` redirects automatically to Toolforge.

---

## What it does

The Gender Bias Detector analyses Wikipedia biographies of women for systematic gender bias. It checks articles against 49 algorithmic patterns across six categories:

- **Relational Definition** — defining the subject through her relationships to others
- **Appearance Focus** — unnecessary descriptions of physical appearance
- **Diminutive Language** — language that minimises her identity or achievements
- **Unnecessary Gendering** — adding gender qualifiers to professional titles
- **Achievement Minimisation** — passive voice and domestic framing that reduces her agency
- **Patronising Tone** — words that trivialise assertiveness or frame success as surprising

For each flagged passage, the tool explains the bias, suggests an editorial approach, and provides before/after rewrite examples. It links directly to the Wikipedia section for editing.

It also supports **category mode** — enter a Wikipedia category (e.g. `Category:Women Nobel laureates`) to audit all articles in that category at once, with a summary dashboard and sortable results.

---

## Features

- 49 bias patterns across 6 categories
- Category-level audits (up to 500 articles, including one level of subcategories)
- Section-specific edit links
- Before/after rewrite examples
- No AI, no login, no data sent externally — fully client-side
- Sortable results by bias score or alphabetically

---

## Translating this tool

A full translation guide is available for anyone wishing to adapt the tool to another language. It covers all 49 patterns with explanations and before/after examples, notes on adapting the regular expressions, and instructions for switching the Wikipedia API to a different language edition.

📄 [Download the translation guide (Word document)](https://github.com/nethahussain/wikipedia-gender-bias-detector/blob/main/translation-guide.docx)

---

## Hosting

The tool is hosted on [Wikimedia Toolforge](https://wikitech.wikimedia.org/wiki/Portal:Toolforge) at:

**https://gender-bias-detector.toolforge.org**

Source code is maintained in this GitHub repository. The Toolforge deployment is kept in sync via the [Wikimedia GitLab repository](https://gitlab.wikimedia.org/toolforge-repos/gender-bias-detector).

---

## Licence

Released under [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) — public domain. No permission needed to use, adapt, or redistribute.

---

## Author

Created by [Netha Hussain](https://meta.wikimedia.org/wiki/User:Netha_Hussain) · [nethahussain@gmail.com](mailto:nethahussain@gmail.com)
