# Bitcoin Trivia App
Community Repo for the Bitcoin Trivia App

## Inspiration
The Bitcoin Trivia App was born as way for me to practice React on my way to becoming a Web 3 developer.  I built a version of the populr Quizzical app, and populated it one night with some Bitcoin-related questions.  That effort snowballed into the app we see today.

Really, the Bitcoin Trivia App is a way for me to contribute to the larger Bitcoin community, connect with other developers and Bitcoiners, and help grow Bitcoin's influence around the world.  Trivia is fun. Maybe someday some of these questions will make their way into local bar trivia nights or even onto a popular trivia-like game show!

## FAQ
*1. Why only three questions per day?*

Well, I'd like the project to grow slowly. It seems if all the questions were available, all at once, at a global scale, then the traivia game would burn out really quickly. This is also my first major deployment as a developer, so I want to slowly study the analytics, understand API loads and get community feedback before going too fast.
    
*2.  Ten mintues to try again, really?*

It's a way to pay hommage to Bitcoin's block time. lol. Plus, it's another way to slow down the distribution of the questions. Call it scaling or scale-throttling if you will.
    
*3. How many questions are there in the database?*
 
A lot. :)

## Known Issues and Bug Reporting
To report bugs, please send me a message on Github or Twitter [@enjoywithouthey](https://twitter.com/enjoywithouthey) or send an email to admin@bitcointrivia.app

*Known Issue #1 - Potential duplication of questions* <br>
The MongoDB $sample data aggregator selects three random questions from the database. It is possible for a question to repeat. Each question has a probability of under 1% for being selected. The probability that two questions match is less than 0.01%.
