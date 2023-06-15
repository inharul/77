

"This course will teach you statistical thinking concepts that are essential for learning from data and communicating insights."
okay? Basically to learn from data and communicating insights, we need statistical thinking.

By the end of this course, you should be able to perform\
- exploratory analysis
- understand the key principles of sampling and
- select appropriate tests of significance for multiple concepts.
It gives the basic principles to pursue higher statistical thinking topics in machine learning too wow!

Instructor: Guenther Walther, PhD, Prof. of Statistics, Stanford University


**Statistics**: Science of learning from data.
	"As we are producing amount of information everyday, it has been essential to learn from that data and so is the need to understand it."

## Descriptive Statistics
Ways of summarizing data using numbers and graphs. Visualizing information. Communicate with figures because humans are visual learns and prefers to learn from visual figures.

The two most important functions of descriptive statistics are:
1. Communicate information
2. Support reasoning about data

When data is larger, it's essential to use summaries.
Graphical summaries of data It is best to use a graphical summary to communicate information, because people prefer to look at pictures rather than at numbers. There are many ways to visualize data. 1. <u>The nature of the data</u> and 2. <u>the goal of the visualization</u> determine which method to choose.

## Pie chart and dot plot 
When the data is qualitative (e.g. colors, car types etc.), Pie chart or dot plot is used.
![[Pasted image 20230615155134.png]]
The dot plot makes it easier to compare frequencies of various categories, while the pie chart allows more easily to eyeball what fraction of the total a category corresponds to.

- Pie charts are a good visualization technique to show percentages, not numbers of cases.

## Bar graph
When the data are quantitative (i.e. numbers), then they should be put on a number line. This is because the ordering and the distance between the numbers convey important information.
![[Pasted image 20230615155905.png]]

## Histogram
![[Pasted image 20230615160128.png]]
The histogram allows to use blocks with different widths. 
**Key point: The areas of the blocks are proportional to frequency.**
The area corresponds to 100%, so the percentage can be figured out without needing of a vertical scale (density scale).
```css
#totalwidth {
width: 100vw;
}
.boxes {
width: 100%;
// according to their relative space taken in the totalwidth
}

#box60-80 {
width: 20%;
}
```

It gives 2 kinds of information:
1. **Density (crowding)**: The height of the bar tells how many subjects there are for one unit on the horizontal scale. For example, the highest density is around age 19 as .04 = 4% of all subjects are age 19. In contrast, only about 0.7% of subjects fall into each one year range for ages 60–80.
2. **Percentages (relative frequencies)**: Those are given by $$ area = height * width $$For example, about 14% of all subjects fall into the age range 60–80, because the corresponding area is (20 years) x (0.7 % per year)=14 %. Alternatively, you can find this answer by eyeballing that this area makes up roughly 1/7 of the total area of the histogram, so roughly 1/7=14% of all subjects fall in that range

## Box plot (box and whisker plot)
![[newplot.png]]
The boxplot conveys less information than a histogram, but it takes up less space and so is well suited to compare several datasets: