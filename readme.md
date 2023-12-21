# 留学生日常作业/课程设计/代码辅导/CS/DS/商科，仅为漂洋过海的你❥
标签：Computer Science、Data Science、Business Administration，留学生编程作业代写&&辅导

## 个人介绍:
本人是一名资深码农，酷爱投资。

为您提供 CS , DS , 商科 编程作业代写

<img src="design2023866.jpg"  width="200" />


# EBIS 3103 Introduction to Business Data Analytics -
# Individual Assignment 1 (Total 100 Marks, 3 pages)
This assignment is designed to walk you through data
manipulation and basic visualization techniques for given
research questions. You will be also asked to answer several
questions about data distribution using the real-world
donorchoose.org data.
Now, suppose we are interested in the characteristics of projects
proposed on the donorschoose.org platform. Specifically, we
have two research interests: (a) whether teachers get better at
completing their projects as they repeatedly create donation
projects over time, and (b) whether teachers get better at
attracting more numbers of donors when the poverty level of
their schools is high.
Here are the steps you should follow:
1. Load projects.csv data into a dataframe or tibble named “dt”.
[5 marks]
2. Before analyzing the data, you need to create new variables
that are needed for the analysis. [5 marks per each, total 20
marks]
(1) Change the data type of the *date_posted* column into date,
and store these changed values in a new column named
*date_started*. (Hint use lubridate package).
(2) Remove projects from the dataset if the value of their
*funding_status* column is *live*. Then recode *NA* in the
*total_donations* and *num_donors* to 0. In other words, after
the manipulation, the *funding_status* column should not
contain *live* as a part of its values, and *total_donations* and
*num_donors* columns should not contain any missing values
(NA).
Tips:
- for this step, you may use ifelse() in mutate () to recode the
values.
- is.na() returns TRUE if the function finds NA among values.
(3) Create a new column called *project_no* that shows how
many projects a teacher has created in the dataset. For example,
the first project created by teacher A should have 1 as the value
of this column, his/her second project should have 2, etc.
Naturally, this column starts with 1 for every teacher.
(4) Finally, create a new column called *recv_prop_ratio* that
contains a ratio (in terms of %) of the actual amount of donation
from donors to the donation goal proposed by a teacher. Use
“total_donations” for the former, and
“total_price_including_optional_support” for the latter.
3. Graph the density of the *recv_prop_ratio* column for
project_no==2, project_no ==5, and project_no ==15. If you use
ggplot2 library, you can use the *geom_density* function.
- Do you think they are close to normal density?
- Interpret any difference you notice from these three densities.
[A correct visualization: 10 marks / Interpretation: 10 marks]
Tips:
- %in% can be used for matching values and returns a vector of
the positions of matches of its first argument in its second.
- xlim(0,150) can be used to set a limit of x-axis, up to 150 for
visualization. This action does not remove large values in the
variable.
4. Now using the *dt* data frame (or tibble), it is time to create a
new data set that you will name *ts*. This table should have two
columns for each teacher. [10 marks per each, total 20 marks]
(a) *avg_donors*: the average number of donors donated to the
completed projects created by each teacher.
(b) *poverty_level*: the poverty level of the area where the
teachers are located.
5. Using the new “ts” table, graph the densities of *avg_donors*
only for poverty_level==high and poverty_level==low.
- Do you think they are close to normal density?
- Interpret any difference you notice among these densities.
[A correct visualization: 10 marks / Interpretation: 10 marks]
Tips:
- %in% can be used for matching values and returns a vector of
the positions of matches of its first argument in its second.
- xlim(0,10) can be used to set a limit of x-axis, up to 10 for
visualization. This action does not remove large values in the
variable.
6. Now, interpret the differences between outputs of step 3 and
outputs of step 6. What would you conclude concerning the
given the two research interests presented at the beginning of
this assignment? Please try to explain why. [7.5 marks per each,
total 15 marks]
# Instructions:
1. Use R.
You do not have to use tidyverse, but it is recommended. If you
are to use tidyverse, here’s a useful online resource that has most
of what you need to finish this assignment:
https://r4ds.had.co.nz/transform.html
2. Use Rmarkdown, and compile your codes, results, and
explanations into an HTML or a PDF file. You should submit
only one final compiled report file (other formats will NOT be
graded).
3. Do not include more than twenty lines of output of your code.
For example, if you want to show that your code successfully
transforms the entire table, only shows, say, the first ten rows of
the table.
4. Do not create a new data frame unless you are instructed to do
so. When you create a new column, use the instructed column
name. If you have to make your own, you need to justify

## 作业代写价格:

|类型|美元|人民币|
|-----:|-----:|-----:|
|Assignment|$60-$120|¥400-¥800|

### 为了方便快速定价和确定是否代做，麻烦提供私聊的时候提供以下信息：
如果是作业，提供本次作业要求文档；如果是考试，提供考试范围和考试时间
一两句话概括一下作业任务或者考试任务，比如”可以帮忙实现一个决策树算法吗？”、”网络安全选择题考试，范围是内网横向移动知识点”
### 作业定价有两种方式：
    - 根据定价标准进行
    - 通过微信我们一起协商
## 联系方式

微信（WeChat）：design2023866

<img src="design2023866.jpg"  width="200" />
