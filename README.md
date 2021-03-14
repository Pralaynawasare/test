This the Information ongithub analysis:
When companies want to recruit employees for their company on basis of Githubdata. This the small project created using python skills.
•	Collecting of data by implementing pre-processing techniques like “API calls and converting data to JSON flies”.
•	Data mining the programming Languages used in the developing of projects through “WebScrapping”. So that we can know the coding standards of an individual. 
•	Presenting the Users Data based on company requirements through “Pandas DataFrame”.
Firstly we have accessed the users data through API available to get Githubusers. 
We have created access token to get sufficient API calls per day to get single user data on repos, login, followers etc.,
We have created access token through these steps:
1.	Register a Github profile.
2.	Click on user profile photo on top right hand side and go setting 
3.	In settings click on Developer settingsand then click on personal access token.
4.	On top right side click on “Generate NewToken”.
5.	Select the scopes for access token to get the information of desired data by giving permission
6.	In here we have selected the scopes for Users and Repos.
7.	And click the “Generate Token” at bottom
8.	The Code for token gets generated.
After token generation to use the Github methods in your project “Install Python Github library”. By running the command
•	!pip install pygithub
To run our project we have this command in the developed code

Get the through understanding ofgithub methods. So that we can easily access data through github python methods.
We have collected the information of followers, repos data and main languageused in each repo, etc., through access token and github methods
After that we have used web scrapping to get all the languages in each repo used by the user and collected data of users based on company criteria and for better visualization we have used data frames.
