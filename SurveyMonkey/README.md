# Survey Monkey Data Manipulation

This exercise is inspired by [Shashank Kalanithi](https://www.youtube.com/channel/UCvZnwzmc3m1Eush-Or8Z6DA) video on real world data cleaning tasks. 

The dataset for this exercise can be found on [Github](https://github.com/kshashank03/Survey-Monkey-Tutorial). 

The following are the I wanted to achieve here : 

1. Convert the human readable wide format to computer readable long format using `pd.melt()`.

2. Replace the column names of Question + Subquestion to the actual Question value using `pd.merge()`. 

3. Group the data and count the number of unique respondents per Question Number. 

4. Group the data and count the number of people that have the same answer to a question. 