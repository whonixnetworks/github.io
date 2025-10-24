---

# Jekyll Chirpy Post Template Reference

---

## Frontmatter

```yaml
---
title: Your Post Title
description: >
  Multi-line description for SEO.
  Use `>` for multi-line.
date: YYYY-MM-DD
categories: [Primary, Secondary]
tags: [tag1, tag2, tag3]
pin: false
---


---

Hero Image

![Hero Image](/assets/img/sample.jpg){: width="972" height="589" .w-50 .right}


---

Custom Intro Section

Write an engaging intro paragraph that summarizes the post’s value and draws readers in.


---

Headers

Centered H1 Title

Regular H2 Section

H3 Subsection

Bold Inline Header <u>Underlined Label</u>


---

Lists in Blockquotes

> Category Title

Feature name: Description text

Another feature: More details

Third item: Additional info




Alternative Style:

Item one

Item two



---

Code Blocks

Standard code:

#!/bin/bash
command here

With filename:

print("Hello World")

{: file="script.py"}

No line numbers:

simple command

{: .nolineno}

Inline filepath:
/path/to/file{: .filepath}

Display Liquid/Template Code:

{% raw %}{{ .Variable }}{% endraw %}


---

Prompt Boxes

> WARNING: Warning message here.
{:.prompt-warning}



> DANGER: Critical danger message.
{:.prompt-danger}



> TIP: Helpful tip or call to action.
{:.prompt-tip}



> INFO: Informational note.
{:.prompt-info}




---

Image Classes

Example:

![Example Image](/assets/img/example.png){: width="800" height="400" .w-50 .right}

Position: .left .right .normal
Size: .w-50 .w-75
Effects: .shadow .light .dark


---

Text Formatting

Bold text – emphasis

Italic text – definitions

<u>Underlined</u> – section labels

inline code – commands/files

Link – standard

External Link{:target="_blank"} – opens new tab



---

Standard Section Pattern

Section Header

Intro paragraph.

Subsection Label

Point one: Description

Point two: More details


Explanation paragraph.

# Code example
command --flag

> TIP: Related tip here.
{:.prompt-tip}




---

Comparison Layout

vs Alternative A

Their approach: Description

Your approach: Counter-description


vs Alternative B

Their feature: Explanation

Your feature: Your explanation



---

Horizontal Rules

Use --- or *** to separate sections visually.


---

Final Structure

1. Frontmatter


2. Hero image


3. Intro section (flexbox + centered text)


4. Problem Statement


5. Problem explanation + lists


6. What Solution Does


7. Features in blockquote lists


8. Technical Details


9. Code examples + prompt boxes


10. Installation (prerequisites + commands)


11. Usage (step-by-step with code)


12. Troubleshooting (common issues + fixes)


13. Final Thoughts (summary paragraph)



> TIP: Call to action.
{:.prompt-tip}