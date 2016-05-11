#Machine Learning

## Supervised 

- Value prediction 
- Needs training data

## Unsupervised

- Identifies clusters of like data
- Data does not contain cluster membership

## Machine learning overview

An orchertated and repeatable pattern which systemattically transforms and processes information to create prediction solutions.

Asking the right question -> Prepare data -> Selecting the algorithm -> Training the model -> Testing the model with new data

The early steps are most important

Each step depends on the previous step, Expect to go backwards, Data is never as you need it, 
More data is better (better results), Don't pursue a bad solution (Reevaluate)

## Asking the right question

"Predict if a flight will be on time"

Need a statement to direct and validate work. It needs to be more than just a one line quote. 

** We needs a solution statement that will define the scope, target performance, context for usage, and how the soltuion will 
be created. **
## Scope

- US Flights only
- Flights between US airports only
- DOT database is a good source

"Using DOT data, predict if a flight would be on time."

## Data
- Preliminary data review, delays are tracked not on time

"Using DOT data, predict if a flight would be delayed."

## Target performance

- Binary result 
- 70% Accuracy is common target
 
"Using DOT data, predict with 70%+ accuracy if a flight would be delayed."

## Context 

- "Delayed" is greater than 15 minutes after scheduled

"Using DOT data, predict with 70%+ accuracy if a flight would arrive 15+ minutes after the scheduled arrival time."

Machine Learning workflow

- Process DOT data
- Transform data as required 

"Using the machine learning workflow to process and transform DOT data to create a prediction model. This model must
predict whether a flight would arrive 15+ mintues after the scheduled arrival time with 70+% accuracy"

## Data Prep

- Find the data
- Inspect and clean the data
- Explore the data
- Mold the data to tidy data

## Tidy data

Tidy datasets are eay to manipulate model and visualize, and have a specifc structure 
each variable is a column
each observation is a row
each type of observational unit is a table

50-80% of a machine learning project is obtaining, cleaning and organizing data so buckle up.