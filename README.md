# Calendar Assignment: How do I spend my time?

# Introduction

For Amherst students and many college students across the country, COVID 19 marked a fundamental change in our lives. We have been studying remotely for the past two semesters, but we still find it challenging to manage our time during our remote learning. Thus, this project is dedicated to answering the fundamental question: “How do I spend my time?”

**Research Question:**

- How much do I procrastinate?--difference in time I have for studying and the actual time I spend on it.
- How does my sleep schedule affect productivity?
- How much time do I spend on cooking and eating meals? Does spending time on cooking affect my studying time?

---

# Data

For 32 days, I used Google Calendar to explore how I spend my time. I only kept track of a few activities that take up most of my time during the day--studying, class, eating and sleeping. At the end of approximately one month period, I collected my data for data wrangling and analysis.

## Variables

Among the variables in the original data set, I focused on the summary, which is converted to lower case letters for the ease of analysis, date of an activity, its starting time and date, ending time and date and length of time converted to hours. I also added the day variable which expresses day of the week of each date.

# Results

## Visualization 1

![Image](https://github.com/hailinkim/stat231_Calendar/blob/main/images/barplot.png)

The bar plot compares the average amount of time I have for studying and the average amount of time I allot on studying over the week. I tend to spend more time studying on Wednesdays and Thursdays. This is presumably because all my classes have problem sets due on Fridays and I spend more time working on them especially on Thursdays.

---

## Visualization 2

![Image](https://github.com/hailinkim/stat231_Calendar/blob/main/images/boxplot.png)

In this boxplot, I plotted the ratio of studying time to time I actually have over two meal types—whether I cooked at home or ate out. It appears that I tend to allot more time on studying when I eat outside than when I cook. The median ratio of studying time for eating outside is 0.358 and 0.263 for cooking. This result is quite intuitive as it takes more time to cook and prep for meals than to eat outside and I would have less time to study if I cook.

---

## Visualization 3

![Image](https://github.com/hailinkim/stat231_Calendar/blob/main/images/table.png)

I created this table to explore how my sleep schedule affects productivity. The table contains average sleeping time and average ratio of studying time to time I actually have over the week. I expected that sleeping more would enhance my productivity. However, the table shows that I studied the most when I slept the least. It is also notable that I sleep the most and study the least on Fridays. Again, this is possibly because I have most of my homework due on Fridays; I dedicated more time to sleeping than any other days of the week after submitting all the homework.

---

# Answering my questions of interest

1. How much do I procrastinate?--difference in time I have for studying and the actual time I spend on it.

   > I spend way less time on studying than time I have for studying. I spend time on studying the most on Wednesdays and Thursdays.

2. How much time do I spend on cooking and eating meals? Does spending time on cooking affect my studying time?

   > I spend more time on on studying when I eat outside than when I cook for my own meals.

3. How does my sleep schedule affect productivity?
   > I tend to study more when I sleep less. On Thursdays, I sleep the least, 5.75 hours on average, and study the most, dedicating 45% of my time to studying.

---

# Reflection

This project provided valuable insight into how I spend my time. Realistically, however, it was hard to keep a detailed track of how I spend time. When collecting the data, I focused only on a few activities—classes, sleeping, eating, and studying, so the data would not provide accurate representation of how I spend time every day. Also, the data recognizes the length of time spent on a schedule that lasts overnight as if it is spent only on the start date. When calculating the amount of time I actually have on a certain day, I had to either perform a very complicated data wrangling or assign the length of time spent manually to each day in the data collection process. For future projects, I would use a different code for reading the data set into R so that it assigns the length of time spent on an overnight activity to each day automatically.

I collected the data set for 32 days, but it was not sufficient to establish the relationship between how I spent time on two different activities. I would have to collect the data for at least six months to discover meaningful relationships.

## Ethical Consideration

As someone who provides data, I expect that my data is treated with ethical considerations. I expect that my data is kept confidential and anonymous so that it cannot be traced to its provider. In order to ensure privacy of my data, I hope that data usage and any information gathered in the data analysis procedure are clearly communicated to me.

As someone who analyzes others’ data, I think it is imperative to be aware of ethical implications of my analysis, given the privacy and sensitivity of the data. It is important to communicate the use of data and obtain informed consent from the data provider. Data collectors must constrain unrestricted, unauthorized access to data. Also, they must not let their preconceptions or personal opinions interfere with the data collection process.
