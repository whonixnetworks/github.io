# Jekyll Chirpy Post Template Reference

## Frontmattertitle: Your Post Title
description: >
Multi-line description for SEO.
Use > for multi-line.
date: YYYY-MM-DD
categories: [Primary, Secondary]
tags: [tag1, tag2, tag3]
pin: false
## Hero Image{: width="972" height="589" .w-50 .right}
## Custom Intro Section
## HeadersCentered H1 TitleRegular H2 SectionH3 SubsectionBold Inline HeaderUnderlined Label
## Lists in BlockquotesCategory TitleFeature name: Description textAnother feature: More detailsThird item: Additional infoAlternative StyleItem oneItem two
## Code BlocksStandard code:
bash #!/bin/bash command here With filename:
python code here 
{: file="script.py"}No line numbers:
shell simple command 
{: .nolineno}Inline filepath: /path/to/file{: .filepath}Display liquid/template code:
bash {% raw %}{{.Variable}}{% endraw %} 
## Prompt BoxesWARNING: Warning message here.
{:.prompt-warning}DANGER: Critical danger message.
{:.prompt-danger}TIP: Helpful tip or call to action.
{:.prompt-tip}INFO: Informational note.
{:.prompt-info}
## Image Classes{: width="800" height="400" .w-50 .right}Position: .left .right .normal
Size: .w-50 .w-75
Effects: .shadow .light .dark
## Text FormattingBold text - emphasis
Italic text - definitions
Underlined - section labels
inline code - commands/files
Link - standard
Link{:target="_blank"} - external
## Standard Section PatternSection HeaderIntro paragraph.Subsection LabelPoint one: DescriptionPoint two: More detailsExplanation paragraph.```bashCode examplecommand --flag
```TIP: Related tip here.
{:.prompt-tip}
## Comparison Layoutvs Alternative ATheir approach: DescriptionYour approach: Counter-descriptionvs Alternative BTheir feature: ExplanationYour feature: Your explanation
## Horizontal Rules
## Final StructurefrontmatterHero imageIntro section (flexbox + centered text)Problem StatementProblem explanation + listsWhat Solution DoesFeatures in blockquote listsTechnical DetailsCode examples + prompt boxesInstallationPrerequisites + commandsUsageStep-by-step with codeTroubleshootingCommon issues + fixesFinal ThoughtsSummary paragraphTIP: Call to action.
{:.prompt-tip}