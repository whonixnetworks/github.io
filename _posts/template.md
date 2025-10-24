Front Matter
```yaml
---
title: Post Title
description: >
  Brief description for SEO
date: YYYY-MM-DD
categories: [Main, Sub]
tags: [tag1, tag2, tag3]
pin: false
---
```

Hero Image
```yaml
![Hero Image](/assets/img/your-hero-image.jpg){: width="972" height="589" .w-50 .right}

_Title: Short caption_
```

Introduction
```yaml
Write an engaging opening paragraph that captures attention.  
Explain what the reader will learn and why it matters.
```

---

📘 Subheadings & Structure

## Section Heading
### Subsection Heading
**Bold Inline Statement** <u>Optional Underlined Label</u>
```

Statement Under Subheadings
```yaml
> **Problem Statement**
> Describe the main issue, topic, or challenge being addressed in this post.  
> Use this section to clarify the context and why it’s relevant.

```

Key Points
```yaml
## Key Points

- **Point one**: Explain briefly  
- **Point two**: Add supporting detail  
- **Point three**: Include examples or data

Example Point
```bash
# Example Point
sudo apt update && sudo apt install your-package
```

Safe Code Example
```yaml
{% raw %}{{ site.url }}{% endraw %}
```

Prompt Boxes
```yaml
> WARNING: Describe a potential risk, limitation, or issue users should be aware of.
{:.prompt-warning}

> DANGER: Mention any critical operation or irreversible action.
{:.prompt-danger}

> TIP: Provide a helpful shortcut, alternative command, or optimization idea.
{:.prompt-tip}

> INFO: Add context, extra notes, or background information relevant to this section.
{:.prompt-info}
```

Supporting Images
```yaml
![Example Image](/assets/img/example.jpg){: width="800" height="400" .w-50 .right}

_Add supporting visuals, screenshots, or diagrams here._

Position: `.left` `.right` `.normal`  
Size: `.w-50` `.w-75`  
Effects: `.shadow` `.light` `.dark`
```

Text Formatting Reference
```yaml
**Bold text** – for emphasis  
*Italic text* – for definitions or quotes  
<u>Underlined</u> – for labels  
`inline code` – for commands or file paths  
[Link](#) – for internal links  
[External Link](#){:target="_blank"} – for new tab links
```yaml

Comparison Section
```yaml
## Comparison

**vs Alternative A**  
> *Their method:* *Explain their approach*  
>> Your method: Explain how yours differs or improves  

**vs Alternative B**  
> *Their feature:* *Describe limitation*  
>> *Your feature:* *Describe advantage*
```

Final Thoughts
```yaml
## Final Thoughts

Summarize the post in one or two paragraphs.  
Reinforce key takeaways or benefits.  
Encourage readers to take action or try your solution.

> TIP: Add a call to action here — e.g.,  
> “Try this method today and share your results in the comments!”
{:.prompt-tip}
```
