# Describe my project
 A gamedev startup. In the application, users try to guess the answers to questions.
I want to analyze and understand which direction to develop our startup. Which platform to choose, which segment to focus on, and how to increase user engagement.

**We have two data frames:**
user_data:
 - client – user identification
 - premium – whether the user has a premium status
 - age – user's age

logs:
 - client – user identification
 - success – result of the answer
 - platform – platform
 - time – time in Unix format

**In this project:**
 - I checked the data for further analysis.
 - I determined the ratio of positive and negative responses.
 - I identified the most active users in the app.
 - I found the most popular platform.
 - I compared the premium and standard segments.
 - I identified the age groups that provide the highest number of correct answers.

**Insights**

**Platforms:**
The most popular platform for both categories is phone.

  **Age:**
 - The highest success rates were observed among users aged 20-26, 28,
   30-33, 47-49, 52, 58, 62, and 67-68.
 - We can consider targeting these age groups.

**Segments:**
 - Among premium users, the most popular age group is 25-30, with the
   lowest activity in the 35-45 and 50-60 age ranges.
 - Among standard users, the most popular age group is 25-30 (or 25-35),
   with the lowest activity in the 45-50 and 65+ age ranges.
 - The premium category has a higher rate of unsuccessful answers.

**Answers:**

 - Most users gave only 1-2 correct answers, and only 9 users managed to
   give 41 correct answers.
 - These users are: User IDs - 12179, 28719, 36165, 52870, 61468, 61473,
   78349, 82563, 92584.

**Action Points:**

 - We need to investigate why the correct answer rate is so low.
 - We might consider adapting questions for different age segments or
   analyzing additional user characteristics.
 - To develop the premium segment and optimize monetization, we should
   tailor the difficulty level to specific ages or user attributes.
