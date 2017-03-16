# Project Design Writeup and Approval Template

Follow this as a guide to completing the project design writeup. The questions for each section are merely there to suggest what the baseline should cover; be sure to use detail as it will make the project much easier to approach as the class moves on.

### Project Problem and Hypothesis
* What's the project about? What problem are you solving
-The project is going to use the Kaggle dataset to predict a characteristic about a respondent.  Initially I wanted to predict how likely a person is to spend money on technology (or gadgets) given their preference in music. However; there are so many variables in the dataset I would be curious to explore what variables have the strongest relationship, ie experiement different target variables and features.

* Where does this seem to reside as a machine learning problem? Are you predicting some continuous number, or predicting a binary value?
-I would be able to use machine learning on this problem in order to identify the strongest features in the data set.  All the variables use survey responses that are ranked on a scale of 1 to 5. This means the outcome will be an ordered discrete variable.

* What kind of impact do you think it could have?
- The outcome will always need to be in relative terms.  I won't be able to predict a tangaible number, like how much someone will spend on technology within a given year.  I will only be able to determine if they are more/less likely to spend money on technology.
    
* What do you think will have the most impact in predicting the value you are interested in solving for?
 -I think perhaps the demographic info will have the most impact.  This is because they are less subjective than peoples self reported ranking in other variables, such as music preference.

### Datasets
* Description of data set available, at the field level (see table)
- As per Kaggles write-up 
      "In 2013, students of the Statistics class at FSEV UK were asked to invite their friends to participate in this survey. The data file (responses.csv) consists of 1010 rows and 150 columns (139 integer and 11 categorical)."


### Domain knowledge
* What experience do you already have around this area?
- I have a small amount of experience with survey science and methodology and the biases that can arise from survey respondents.  

* Does it relate or help inform the project in any way?
- Since the dataset is already clean, it may not have too much help in terms of working through the responses but it is important to note who took the survey, how it was collected and how that may effect that may have on the model. 

* What other research efforts exist?
    - a lot of work has been done on these data. This includes analyses such as gender analysis, dimension reduction, and clustering.
    * Use a quick Google search to see what approaches others have made, or talk with your colleagues if it is work related about previous attempts at similar problems.
    * This could even just be something like "the marketing team put together a forecast in excel that doesn't do well."
    * Include a benchmark, how other models have performed, even if you are unsure what the metric means.

### Project Concerns
* What questions do you have about your project? What are you not sure you quite yet understand? (The more honest you are about this, the easier your instructors can help).
- I'm not sure what the best model is due to the ranking of the dependent variable.  A logit? Or a multivariate logit?  I also saw one of the sample final projects that used a couple different models and compared how well each model did which I would like to do as well.

* What are the assumptions and caveats to the problem?
    - the assumptions include that the data was collected correctly and that it was cleaned correctly. Also, the original questionnaire was in Slovak and later traslated into English. There may be discrepancies on what exactly the questions are asking due to language differences.
    
    * What data do you not have access to but wish you had?
    - For the spending habits, I would have liked "hard" numbers as opposed to a ranking. Also, the same data but on different age groups.
    
    * What is already implied about the observations in your data set? For example, if your primary data set is twitter data, it may not be representative of the whole sample (say, predicting who would win an election)
    - The background info on the data say that the authors asked their friends to partake in the survey so their network may only include certain types of people, ie, the sample is not representative of the population if we were to scale it.  
    
* What are the risks to the project?
    * What's the cost of your model being wrong? (What's the benefit of your model being right?)
    - For this class not much, but if used for actual marketing then it would be the cost of dollars spend on campaigning.
    * Is any of the data incorrect? Could it be incorrect?
    - I will asses this further in the next assignment.  I know there are missing values present which is perplexing. 

### Outcomes
* What do you expect the output to look like?
- I expect to end up with a decision tree output at the end, or a random forest.

* What does your target audience expect the output to look like?
- Target audicence would expect a model or two that is widely applicable to solve business questions.

* What gain do you expect from your most important feature on its own?
- Hmm, not sure what this means...

* How complicated does your model have to be?
- It can be as complex as I want if the data allows

* How successful does your project have to be in order to be considered a "success"?
- I'd like to be able to accurately predict the test set ~85% of the time. Also would consider correctly implementing two or three new models a success.

* What will you do if the project is a bust (this happens! but it shouldn't here)?
- I will be bummed.  But again hopefully can at least take away proper implementation of models.

