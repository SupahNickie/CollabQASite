October 17, 2013 - Collaborative Q&A Site App

This app covers three important topics that we discussed recently in the Code Fellows: Nested Resources (Answers within Questions), the Devise gem for login authentication (the website breaks if you try to post a question or answer without logging in), and the has_and_belongs_to_many relationship between author and question (and in this case, answer also belonging to author).

Screen 1 - This shows the questions index page, highlighting that Rails properly accepts valid author ids into the questions params and pulls the email address out for rendering.

![Screencap](/public/images/screenshot1.png "Screencap of Questions with Authors")

Screen 2 - This shows the answers index page (for question 1), again proving the code works and the associations between user, question, and answer has been properly set. The same is true for question 2 as well, so it's not just a fluke and that it worked only with question 1.

![Screencap](/public/images/screenshot2.png "Screencap of Answers with Different Authors")
