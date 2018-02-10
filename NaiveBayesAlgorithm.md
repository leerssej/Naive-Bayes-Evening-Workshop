Naive Bayes Algorithm
P(a) - Probability that event a occurs [Prior - a priori]
P(b) - Probability that there is evidence 
P(a,b) - Probability that event a and b occurs [posterior - a posterior]
P(a|b) - Probability that event a occurs GIVEN that event b occurs [likelihood]

P(a,b)  = P(b,a)
P(a,b)  = P(a|b)P(b)   - left to right this is actually a definition
P(a|b) != P(b|a) - not flippable - there is an arrow of causality to keep track of

"All about the Bayes" - YouTube video
"Dr. Strange" - hacked precision by only making one prediction

_________________________________________

    P(a,b) = P(b,a)
P(b|a)P(a) = P(a|b)P(b) 

divide both sides by P(b)

P(a|b) = P(b|a)P(a) / P(b)

Posterior = likelihood * prior / evidence


Class - its bucket
Feature - Asterisks, exclamation points, the word Viagra(tm), large amounts

p(c|F) = p(F|c) * P(c) / P(F)  

Feature / # in the class * #in class / total data points

Naive Assumption of Conditional Dependence
allows us to be spared from calculating all the joint probabilities

underflow - when a number gets too small then you loose the number
log space - you can multiply things in log space by adding them

to do for just yes or no then you can subtract from 1
To do for multiple results then you just do each one.

AND the bonus is that you end up dividing the Total Population by the Total Population

You just count things up.
Just store the data in a database.

memorization and generalization - go beyond what you have seen

learning : preferable that you have a dataset that is new than the one you trained on.
aka: cross-validation

precision: how many of the times did I say something was spam, is it actually spam.
Accuracy is just saying alot of stuff. It may 

recall: how many of the needed classifications that existed did you manage to hit - you want to 

import pdb
pdb.set_trace()
