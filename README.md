# Where will we go?
*A recommendation engine for travel in England, UK.*

## Context
For my capstone project in the Digital Futures Academy (Data Science stream), I worked on a recommendation engine. Tourism is an interest area of mine and I thought about making travel easier. Because of the pandemic, people have not been able to travel overseas easily so I wanted to create a way to pick travel destinations locally.

## Data
It was difficult to find a data set with information that I wanted and so I keyed this in manually. I took the list of cities in England from the National Statistics website and paired this with names, decriptions and ratings of 9 attractions. Attraction data was taken from the Google Travel website. Ultimately I only used the names an descriptions in the model as the ratings were not useful.

## Model
The engine uses a similarity score to provide recommendations. It uses the attraction data for the place specified and compares it to the attraction data for all of the places in the data set. It then returns the 5 places most like the input as a recommendation.

## Going Further
Things that might make this engine even better:

- Natural language processing tools like lemmatization and stemming
- Further data cleaning to remove nulls
- More data eg. more attractions for each city or ratings for each attraction or city
- Data from other parts of the United Kingdom (Scotland, Wales & Northern Ireland)
- Use of geo data so that distance can be used as a parameter
- More choices for when no keyword is specified eg. 'na', 'N/a' and ''