# Sprint_5_Project

*My first Integrated Project, meaning that there weren't extensive lessons in this sprint, rather the project was utilizing numerous techniques and knowledge from previous lessons. Sprint length was 2 weeks.*

***Instructions provided by TripleTen Program:***

# Integrated Project

Congratulations! You’ve officially completed the first part of the course on the interactive platform. Now it's time to bring together all you've learned so far in your first integrated project, a real-life analytical case study.

When you finish the project, send your work to the project reviewer for assessment. They’ll give you feedback within 24 hours. Use the feedback to make changes, then send the new version back to the project reviewer.

You might get further feedback on the new version. This is completely normal. It’s not uncommon to go through several cycles of feedback and revision.

Your project will be considered complete once the project reviewer approves it.

# Project description

You work for the online store Ice, which sells video games all over the world. User and expert reviews, genres, platforms (e.g. Xbox or PlayStation), and historical data on game sales are available from open sources. You need to identify patterns that determine whether a game succeeds or not. This will allow you to spot potential big winners and plan advertising campaigns.

In front of you is data going back to 2016. Let’s imagine that it’s December 2016 and you’re planning a campaign for 2017.
(The important thing is to get experience working with data. It doesn't really matter whether you're forecasting 2017 sales based on data from 2016 or 2017 sales based on data from 2016.)

The dataset contains the abbreviation ESRB. The Entertainment Software Rating Board evaluates a game's content and assigns an age rating such as Teen or Mature.

# Instructions for completing the project

## Step 1. Open the data file and study the general information

File path:

[/datasets/games.csv](https://drive.google.com/file/d/1xDGP_dQaLSzvON9FFHl-Mc8ZktQxWmrT/view)

## Step 2. Prepare the data

- Replace the column names (make them lowercase).
- Convert the data to the required types.
- Describe the columns where the data types have been changed and why.
- If necessary, decide how to deal with missing values:
    - Explain why you filled in the missing values as you did or why you decided to leave them blank.
    - Why do you think the values are missing? Give possible reasons.
    - Pay attention to the abbreviation TBD (to be determined). Specify how you intend to handle such cases.
- Calculate the total sales (the sum of sales in all regions) for each game and put these values in a separate column.

## Step 3. Analyze the data

- Look at how many games were released in different years. Is the data for every period significant?
- Look at how sales varied from platform to platform. Choose the platforms with the greatest total sales and build a distribution based on data for each year. Find platforms that used to be popular but now have zero sales. How long does it generally take for new platforms to appear and old ones to fade?
- Determine what period you should take data for. To do so, look at your answers to the previous questions. The data should allow you to build a prognosis for 2017.
- Work only with the data that you've decided is relevant. Disregard the data for previous years.
- Which platforms are leading in sales? Which ones are growing or shrinking? Select several potentially profitable platforms.
- Build a box plot for the global sales of all games, broken down by platform. Are the differences in sales significant? What about average sales on various platforms? Describe your findings.
- Take a look at how user and professional reviews affect sales for one popular platform (you choose). Build a scatter plot and calculate the correlation between reviews and sales. Draw conclusions.
- Keeping your conclusions in mind, compare the sales of the same games on other platforms.
- Take a look at the general distribution of games by genre. What can we say about the most profitable genres? Can you generalize about genres with high and low sales?

## Step 4. Create a user profile for each region

For each region (NA, EU, JP), determine:
- The top five platforms. Describe variations in their market shares from region to region.
- The top five genres. Explain the difference.
- Do ESRB ratings affect sales in individual regions?

## Step 5. Test the following hypotheses:

- Average user ratings of the Xbox One and PC platforms are the same.
- Average user ratings for the Action and Sports genres are different.

Set the *alpha* threshold value yourself.

Explain:

- How you formulated the null and alternative hypotheses
- What significance level you chose to test the hypotheses, and why

## Step 6. Write a general conclusion

**Format:** Complete the task in the Jupyter Notebook. Insert the programming code in the code cells and text explanations in the markdown cells. Apply formatting and add headings.

## Data description

- *Name*
- *Platform*
- *Year_of_Release*
- *Genre*
- *NA_sales* (North American sales in USD million)
- *EU_sales* (sales in Europe in USD million)
- *JP_sales* (sales in Japan in USD million)
- *Other_sales* (sales in other countries in USD million)
- *Critic_Score* (maximum of 100)
- *User_Score* (maximum of 10)
- *Rating* (ESRB)

Data for 2016 may be incomplete.

## How will my project be evaluated?

Read these project assessment criteria carefully before you get to work.

Here’s what project reviewers will be looking at when evaluating your project:
- How do you describe the problems you identify in the data?
- How do you prepare a dataset for analysis?
- How do you build distribution graphs and how do you explain them?
- How do you calculate standard deviation and variance?
- Do you formulate alternative and null hypotheses?
- What methods do you apply when testing them?
- Do you explain the results of your hypothesis tests?
- Do you follow the project structure and keep your code neat and comprehensible?
- Which conclusions do you reach?
- Did you leave clear, relevant comments at each step?

Everything you need to complete this project is in the takeaway sheets and summaries from previous chapters.

Good luck!
