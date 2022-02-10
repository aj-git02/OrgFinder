This is a simple program made to find the most forked repos and of a given organisation. And the oldest forkers of a particular repo.

To run, download and open the file index.html in your browser. Nothing more to download!

View at the screenshots to see the input format in the webpage. 

### Imp : example

amzn  5   5

(result format = amzn/ {repo name})

amzn/alexa-skills-kit-js

(result format = {forker}/{what he named the forked repo})

### Imp : Shortcomings

Due to 3-4 deadlines, 2 quizes and upcoming minors during the time duration provided for the project, there are some shortcomings.

Majors ones first

The organizations that are displayed, are not necessarily the most forked ones. This is because the github api only provides with atmost 100 repos at a time and hence more number of pages must be viewed if all repos are to be taken into account. But this was avoided due to time shortage.

However, the forkers are the oldest, because they were sorted in the api call by sort=oldest. And also one can understand by looking at the code, the max forked repos are selceted out of the 100 that are obtained one the api call.

To evaluators, please consider the extremely packed schedule before the minors and provide mercy for the shortcomings.

It will be tried as soon as possible to overcome these shortcomings