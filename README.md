# In-class assignment week 1
- installed extra packages

# first part 
- original flextable produced a table with grades randomly ordered and mismatching title cases
- changed variables under Gender and Grade variables to title case using mutate()
- releveled the grades in ascending order, with "other" at the end 

# second part 
- aggregated the mean of physically_active_7d by gender and grade 
- created a line plot with Female and Male representing the two lines, Grade as the x-axis and weekly average physical activity as y-axis using ggplot. this plot is under the aggregation command

# third part 
- created a new variable called bmi, which was calculated using the height and weight variable 
- after filtering the data to just females and grade 12 students, BMI was put on the y-axis, number of physically active days on the x-axis (neither are means like the previous part), and the legend represents active days (from fill = physically_active_7d)
- graph represents the relationship between BMI and physical activity among females in grade 12, with BMI as a continuous variable and physical activity as discrete, represented by number of active days 