---
layout: home
---

# COMP110 Data Analysis: Does Note-Taking Affect Understanding?

## The Idea

The course should teach note-taking skills for computer science because it will help students who are not CS majors understand course content better. I wanted to see if students who take their own notes and create their own code examples actually report higher understanding and lower difficulty in COMP110.

## The Data

I used an anonymized survey filled out by students in COMP110 this semester. The columns I focused on were:

- `own_notes` — how often a student takes their own notes (1=Never, 7=Always)
- `own_examples` — how often a student writes their own code examples when confused (1=Never, 7=Always)
- `understanding` — how well the student feels they understand course content (1=Lost, 7=Understand Everything)
- `difficulty` — how difficult the student finds the course (1=Very Easy, 7=Very Difficult)

## Analysis

**Chart 1: Note-Taking Frequency vs. Understanding**

![Chart 1](static/output.png)

This scatterplot shows every student's note-taking frequency on the x-axis and their self-reported understanding on the y-axis. The spread is fairly uniform with no obvious upward trend, meaning higher note-taking frequency doesn't clearly predict higher understanding on its own.

**Chart 2: Note-Taking vs. Difficulty Heatmap**

![Chart 2](static/output1.png)

This heatmap shows where most students are concentrated. The darkest squares are around note-taking scores of 5-7 and difficulty scores of 4-5, meaning most active note-takers still find the course moderately difficult with no clear shift toward lower difficulty.

**Chart 3: Average Understanding by Note-Taking Frequency**

![Chart 3](static/output2.png)

This was the most surprising chart. Students who rated themselves as 1 (never taking notes) had the highest average understanding score around 5.0, while students who always take notes (7) averaged around 4.3. Note-taking frequency alone does not predict higher understanding.

**Chart 4: Self-Generated Examples vs. Understanding**

![Chart 4](static/output3.png)

This scatterplot checks whether students who write their own code examples when confused report higher understanding. Similar to Chart 1, the spread is uniform with no strong positive trend.

## Conclusion

The data does not clearly support the idea that students who take more notes or write more of their own examples report higher understanding or lower difficulty. The bar chart actually showed a slight negative trend, and the other charts showed no strong correlation either way.

This doesn't mean note-taking is useless — students who already understand the material well may simply not need to take notes as much, which could explain the trend. Future analysis should cross-reference note-taking habits with actual quiz and exercise scores rather than self-reported understanding to get a clearer picture.

Adding a dedicated lesson on CS note-taking strategies could still be worth trying, but this data alone doesn't make a strong case for it. Teachers would spend time developing that content at the cost of actual CS material, and students who already take good notes wouldn't benefit much from it.