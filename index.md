---
layout: default
---

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).


# Prediction of medical students' performance in summative assessment using machine learning algorithms

## Background: 
Primary purpose of assessment for learning is to identify the students who require extra motivation to achieve academic goals. Objective of this study was early prediction of medical students’ grade in summative assessment from demographic and curriculum data using Artificial Intelligence. 
## Methods: 
Information regarding 2nd Professional MBBS students’ age, sex, reservation category, attendance, marks in departmental internal assessments throughout the year and their score in Pharmacology university examination of four years were collected (2015 to 2018). Machine Learning algorithms were built using data of first 3 years and their prediction accuracy was tested using last 1 year data. The models tried to identify three groups of students - pass, fail, and distinction (more than 75%) in the final university examination. Analysis was performed using R statistical software (Language) and RStudio platform (R foundation). 

## Results: 
The XGBoost model showed highest accuracy (96.05%) to predict the students who passed in the final examination with sensitivity of 80% and specificity of 98.5%. Naïve Bayes and Random Forest algorithms also performed very well with accuracy of 94.74% and correctly detecting all the possible failures (Sensitivity 100%, Specificity 93.9%). Naïve Bayes performed best while predicting the students likely to get distinction (accuracy 92.11%, Sensitivity 50%, Specificity 95.71%). 

## Conclusion: 
Machine Learning algorithms can be used for accurate prediction of student performance and this can enable teachers to adjust their Teaching-Learning sessions and take timely measures to support them.


















# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
