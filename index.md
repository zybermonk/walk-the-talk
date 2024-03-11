---
layout: default
---

![Banner](assets/biscuit.png)


## Walk-the-Talk: LLM driven pedestrian motion generation

In the field of autonomous vehicles, a key chal-lenge is the “reality gap”: transferring knowledge gained insimulation to real-world settings. Despite various approachesto mitigate this gap, there’s a notable absence of solutionstargeting agent behavior generation, crucial for mimickingspontaneous, erratic, and realistic actions of traffic partici-pants. Recent advancements in Generative AI have enabledthe representation of human activities in semantic space andgenerate real human motion from textual descriptions. Despitecurrent limitations such as modality constraints, motion se-quence length, resource demands, and data specificity, there’san opportunity to innovate and use these techniques in theintelligent vehicles domain. We propose Walk-the-Talk, a motiongenerator utilizing Large Language Models (LLMs) to producereliable pedestrian motions for high-fidelity simulators likeCARLA. Thus, we contribute to autonomous driving simu-lations by aiming to scale realistic, diverse long-tail agentmotion data - currently a gap in training datasets. We employMotion Capture (MoCap) techniques to develop the Walk-the-Talk dataset, which illustrates a broad spectrum of pedestrianbehaviors in street-crossing scenarios, ranging from standardwalking patterns to extreme behaviors such as drunk walkingand near-crash incidents. By utilizing this new dataset withina LLM, we facilitate the creation of realistic pedestrian motionsequences, a capability previously unattainable (cf. Figure 1).Additionally, our findings demonstrate that leveraging theWalk-the-Talk dataset enhances cross-domain generalization andsignificantly improves the Fr ́echet Inception Distance (FID)score by approximately 18% on the HumanML3D dataset.

### Workflow

![workflow](assets/workflow.png)

Walk-the-Talk framework: Using domain-specific data to generate realistic agent behaviours and motions for autonomous driving simulations
utilizing Large Language Models. 

### Files

* `_config.yml`            : Main configuration file.
* `index.md`               : Website page (for now, this page).
* `_includes/head.html`    : File to add custom code to `<head>` section.
* `_includes/scripts.html` : File to add custom code before `</body>`. You can change footer at here.
* `_sass` folder           : Related scss files can be found at this folder.
* `css/main.csss`          : Main scss file.
* `README.md`              : A simple readme file.

## Example tag usage

## Header 1
### Header 2
#### Header 3
**bold**
*italic*

> blockquotes

~~~python
import os,time
print ("Biscuit")
~~~

## Licence and Author Information

Biscuit is derived from currently deprecated theme [Solo](http://github.com/chibicode/solo). The development of Biscuit is maintained by [Sefer Bora Lisesivdin](https://lrgresearch.org/bora).

Biscuit and the previous code where Biscuit is derived are distributed with [MIT license](https://github.com/sblisesivdin/biscuit/blob/gh-pages/LICENSE).
