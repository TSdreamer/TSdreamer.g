---
title: DMEEA-WP1MS1.3-Annual Review
date: 2024-02-26 01:13:00 +0000
<author_id>:
  name: <Haotian MA>
  github: <TSdreamer>
  url: <tsdreamer.github.io>
categories: [PhD Life]
tags: [weekly updates]     # TAG names should always be lowercase
comments: true
math: true
mermaid: true
image:
  path: /images/Feb-2024/M-L-A.png
  alt: Machine learning algorithms 
---

## Key Achievements of this Week:(Working hours:50)

| Task                         | Time Investment  | Status  |
|:-----------------------------|:-----------------|--------:|
| 1st Year Annual Review       | 35/40            | 87.5%   |
|  Carbon Calculation Training (City-level Database Provided) | 3/40 | 7.5%    |
| Preparation of 4th Version of TSu BP     | 2/40 | 5%      |
| Personal Website Construction| 10 hours more    | +25%    |


### Research Progress
The progress report focuses on multi-scale electrolysis energy system modeling,emphasizing two main areas: system level operational dynamics optimization using Generative Adversarial Networks (GANs) and cell level descriptor database analysis. 
\\
\\
Annual Review : Paper 1
![Desktop View](/images/Feb-2024/system-outline-modified.png){: width="972" height="589" .w-50 .right}
: The first part of Chapter 3 introduces an innovative approach to optimizing the operational dynamics of electrolysis energy systems using Generative Adversarial Networks (GANs). This section delves into the challenges of small dataset sizes in the field of renewable energy research, particularly in the context of electrolysis for hydrogen production. The researchers employed GANs to generate synthetic data, thus augmenting the existing datasets and overcoming the limitations imposed by scarce data. This process not only enhances the robustness of the model training but also preserves the statistical integrity of the original dataset, expanding it five-fold to over 2,000 data points. The preliminary evaluation of this synthetic data, conducted using a deep neural network (DNN) architecture, showed an increase in prediction accuracy, as evidenced by improvements in mean squared error (MSE) and R-squared (R²) metrics. This innovative approach signifies a leap forward in the predictive modeling of electrolysis system dynamics, paving the way for more efficient and reliable hydrogen production.
\\
\\
Annual Review : Paper 2
: The second part of Chapter 3 focuses on the cell level descriptor database analysis for Proton Exchange Membrane Water Electrolysis (PEMWE). The section outlines the development of a comprehensive database aimed at reducing the power-specific cost and increasing the efficiency, reliability, and durability of PEMWE systems. By leveraging artificial intelligence and machine learning, the research introduces a novel method of data augmentation using GANs and Gaussian blur techniques to address the challenge of limited dataset sizes commonly encountered in laboratory settings. The database, consisting of over one thousand datasets and nearly forty thousand data points, allows for the prediction of membrane electrode assembly performance with remarkable accuracy. This approach not only enhances the understanding and optimization of PEMWEs but also exemplifies the potential of data science in revolutionizing renewable energy technologies.
<p align="center">
  <img src="/images/Feb-2024/cell-outline-modified.png" width="760" height="420" alt="Desktop View">
</p>






# H1 - heading
{: .mt-4 .mb-0 }

## H2 - heading
{: data-toc-skip='' .mt-4 .mb-0 }

### H3 - heading
{: data-toc-skip='' .mt-4 .mb-0 }

#### H4 - heading
{: data-toc-skip='' .mt-4 }

## Paragraph

Quisque egestas convallis ipsum, ut sollicitudin risus tincidunt a. Maecenas interdum malesuada egestas. Duis consectetur porta risus, sit amet vulputate urna facilisis ac. Phasellus semper dui non purus ultrices sodales. Aliquam ante lorem, ornare a feugiat ac, finibus nec mauris. Vivamus ut tristique nisi. Sed vel leo vulputate, efficitur risus non, posuere mi. Nullam tincidunt bibendum rutrum. Proin commodo ornare sapien. Vivamus interdum diam sed sapien blandit, sit amet aliquam risus mattis. Nullam arcu turpis, mollis quis laoreet at, placerat id nibh. Suspendisse venenatis eros eros.

## Lists

### Ordered list

1. Firstly
2. Secondly
3. Thirdly

### Unordered list

- Chapter
  + Section
    * Paragraph

### ToDo list

- [ ] Job
  + [x] Step 1
  + [x] Step 2
  + [ ] Step 3

### Description list

Sun
: the star around which the earth orbits

Moon
: the natural satellite of the earth, visible by reflected light from the sun

## Block Quote

> This line shows the _block quote_.

## Prompts

> An example showing the `tip` type prompt.
{: .prompt-tip }

> An example showing the `info` type prompt.
{: .prompt-info }

> An example showing the `warning` type prompt.
{: .prompt-warning }

> An example showing the `danger` type prompt.
{: .prompt-danger }

## Tables

| University                   | Reference        | Country |
|:-----------------------------|:-----------------|--------:|
| Massachusetts Institute of Technology| Pulkit Agrawal| US |
| University of Warwick        | Sai Gu           | UK      |
| University of Birmingham     | Leandro Minku    | UK      |
| University of Nottingham     | Gavin Walker     | UK      |
| Southeast University         | Mingchun Wang    | China   |

## Links

<http://127.0.0.1:4000>

## Footnote

Click the hook will locate the footnote[^footnote], and here is another footnote[^fn-nth-2].

## Inline code

This is an example of `Inline Code`.

## Filepath

Here is the `/path/to/the/file.extend`{: .filepath}.

## Code blocks

### Common

```
This is a common code snippet, without syntax highlight and line number.
```

### Specific Language

```bash
if [ $? -ne 0 ]; then
  echo "The command was not successful.";
  #do the needful / exit
fi;
```

### Specific filename

```sass
@import
  "colors/light-typography",
  "colors/dark-typography";
```
{: file='_sass/jekyll-theme-chirpy.scss'}

## Mathematics

The mathematics powered by [**MathJax**](https://www.mathjax.org/):

$$ \sum_{n=1}^\infty 1/n^2 = \frac{\pi^2}{6} $$

When $a \ne 0$, there are two solutions to $ax^2 + bx + c = 0$ and they are

$$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$

## Mermaid SVG

```mermaid
 gantt
  title  Adding GANTT diagram functionality to mermaid
  apple :a, 2017-07-20, 1w
  banana :crit, b, 2017-07-23, 1d
  cherry :active, c, after b a, 1d
```


## Video

{% include embed/youtube.html id='Balreaj8Yqs' %}

## Reverse Footnote

[^footnote]: The footnote source
[^fn-nth-2]: The 2nd footnote source


