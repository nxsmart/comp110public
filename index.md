---
# Do not edit the text between these lines!
layout: default
---

# COMP110 Data Analysis: Does Note-Taking Affect Understanding and Difficulty of Course Content?

<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->
<img src="<comp110public>/static/imgs/logo.png" alt="Image of Comp110 rainbow logo. "  width="500"/>

## My Idea

The course should teach note-taking skills for computer science because it will help students who are both CS and non CS majors understand course content better. I wanted to see if students who take their own notes and create their own code examples actually report higher understanding and lower difficulty in COMP110.

## Methods

Through using the anonymous survey that students filled out in COMP110, I focused on 4 columns: 
  - "own_notes", which is how often students take their own notes 
  - "own_examples", which is how often a student writes their own code examples 
  - "understanding", which is how well the student feels like they understand the course  content
  - "difficulty", which is how difficult the student believes the course to be.

## Analysis
The following figures display different relationships between the four variables. 

Figure 1. Note-taking vs Understanding
<img src="{{ site.baseurl }}/static/imgs/output.png" width="500"/>
This figure shows the relationship between students who take notes and self-reported understanding of course content. The spread is fairly uniform, and there isn't much of a trend.

Figure 2. Note-taking vs Difficulty
<img src="{{ site.baseurl }}/static/imgs/output1.png" width="500"/>
This figure shows the relationship between students who take notes and self-reported difficulty of course content. The darkest squares are concentrated around note-taking scores of 5-7 and difficulty scores of 4-5, meaning most active note-takers still find the course moderately difficult.

Figure 3. Average Understanding by Note-Taking Frequency
<img src="{{ site.baseurl }}/static/imgs/output2.png" width="500"/>
This figure shows the average understanding by note-taking frequency reported. Students who rated themselves as 1, or never taking notes, had an average of around 5.0 reported understanding of course content, and students who rated themselves as 7, or always taking notes, had an average of around 4.3 reported understanding

Figure 4. Own Examples by Understanding
<img src="{{ site.baseurl }}/static/imgs/output3.png" alt="Scatterplot of own_examples vs understanding" width="500"/>
This figure shows the relationship between students making their own examples and their understanding of course content. There appears to be no strong trend, whether positive or negative, between writing own examples and self-reported understanding. 

## Conclusion
y data analysis results were very surprising. This analysis tested if a student taking their own notes and making their own examples was correlated with their percieved understanding of course materials and lower perceived difficulty. The results were actually somewhat surprising. The bar chart from the third visualization was quite surprising- there seemed to be a downward trend, where students who took their own notes reported slightly less understanding of course content on average. Students who rated themselves as 1, or never taking notes, had an average of around 5.0 reported understanding of course content, and students who rated themselves as 7, or always taking notes, had an average of around 4.3 reported understanding. This visualization shows that note taking alone doesn't predict higher understanding of course content.

The histplot heatmap from visual 2 of note-taking vs. difficulty showed that the darkest cells, which represents the most students, were concentrated around students taking their own notes scores of 5-7 and difficulty scores of 4-5. This tells us that  most students who take notes frequently still find the course moderately difficult, with no clear reduction in perceived difficulty for active note-takers. Along with the other scatterplots, which do not show clear correlations between the two variables, the overall conclusion is that active notetaking or creating own examples doesn't correlate with creating own notes or examples.

Overall, the data doesn't clearly support my original idea that students who take their own notes or make their own examples have higher understanding of the course content and lower percieved course difficulty. The data doesn't show a strong correlation, so it is inconclusive with the data that we currently have.

Adorting my idea of having dedicated classtime to teach students to take their own comp notes may not actually lead to learning outcomes that we hope to see, as we see in this data. Students who are already note-takers may find this lesson redundant. Teachers would have to develop stronger learning materials which could be helpful to students who aren't already note takers, but will take away time from teachers to develop this content when they could be developing computer science content- therefore, teachers may be negatively impacted, while students may not receive very helpful content.

Next steps could be cross referencing students who took notes or have percieved higher understanding with their quiz scores, to see how they truly performed. Sometimes self-reported scores may not align with testing scores, so assessing a correlation may be worth looking into. Students who do not take notes may not need to take notes since they understand course content more, so this relationship may have different effects depending on the student.

# Thank you for reading :D