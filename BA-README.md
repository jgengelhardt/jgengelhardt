<!--
**jgengelhardt/jgengelhardt** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile. 

Here are some ideas:

### Hi there, I'm Joseph!

- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- 🎯 Goals:
- ⚡ Fun fact: ... -->

## Professional Business Data Analysis Work
I led an impactful project where I analyzed 7 years of sales data to determine that a significant amount of our summer revenue comes from customers who register for multiple programs to experience multiple themes and don't seem to be landlocked as previously suspected. I also produced insights into ideal scheduling and location strategies. I recommended actions to management from these findings, which ensured a strong ROI during the COVID-19 pandemic. While most of the data is proprietary, I share some scripting I wrote here.
### Gathering & Cleaning
The database doesn't allow us to pull all of the required records at once, so [this Python script](https://github.com/jgengelhardt/work-stuff/blob/main/combine_all2.py) combines and normalizes many compatible Excel spreadsheets into a single record that can be analyzed.
### Analysis
[This Python script](https://github.com/jgengelhardt/work-stuff/blob/main/multiregistration_campers.ipynb) demonstrates some of the analysis that revealed actionable insights regarding what our customers want out of our summer operations, and how much revenue is attributable to those customer desires.

## Sports Data Analysis
You'll also find some personal projects that showcase additional tools and techniques, including web scraping and data visualization. Documentation and more detailed explanations of each project are available through the links below.
### How well do final season standings represent sports team skill, rather than chance? 
In my project ["Win Percentage vs. Skill"](https://github.com/jgengelhardt/wpct-vs-chance), I explore the above question for a number of sports leagues through their recorded history, from their founding to the most recent available season. For the source data, I gathered sports statistics from various sources---scraping from HTML webpages and querying the official NHL API---each with their own quirks and challenges. I then transformed and plotted the data, while performing linear regression for easy interpretation.
### Estimating Exponent for Pythagorean Method of Expected Win Percentage in Various Leagues
If you've read *Moneyball* or seen the movie starring Brad Pitt and Jonah Hill, then you might know that there's a simple formula analysts used to predict a baseball team's future performance. In [this project](https://github.com/jgengelhardt/sports-pythagorean-exponent), I query data from the official NHL API and perform linear regression and other analysis to empirically estimate the equivalent formula for North American ice hockey.
