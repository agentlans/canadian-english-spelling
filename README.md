# Canadian English Spelling Dataset

A clean, curated dataset mapping non-Canadian English spellings to their standard Canadian equivalents.

## 📄 Overview

This repository contains a single CSV file designed to help with spelling conversion, Natural Language Processing (NLP) tasks, and localization.

* **Column 1:** U.S., British, Australian, or general non-Canadian spellings.
* **Column 2:** The corresponding spelling according to standard Canadian style conventions.

### Methodology

* **Source:** The base words were sourced from the [English Speller Database](https://wordlist.aspell.net/).
* **Generation & Verification:** Canadian spellings were generated using well-established orthographic rules and verified manually.
* **Selection:** Where multiple spelling variants are permitted, the most popular or traditional spelling in Canadian publishing was chosen.

## ⚠️ Limitations

* **Conservative Approach:** The dataset is built for consistency rather than exhaustive conversion. It does not attempt to flag or convert every single word to Canadian spelling.
* **Descriptive, Not Prescriptive:** This is not a strict style guide. In many cases, American and British spellings remain acceptable in Canada.
* **Syntax vs. Semantics:** Pure spelling transformations do not account for semantic nuances or contextual shifts (e.g., noun vs. verb forms like *licence* vs. *licensing*).

## 📜 Licence

This work is licensed under **Creative Commons Attribution-ShareAlike (CC BY-SA)**.

> **Note:** Any modifications or improvements made to the dataset must be shared back to help improve the list for everyone.
