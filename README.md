# Probability in Python
Probability 
Probability is a measure of the likelihood of a particular event occurring. It is typically expressed as a number between 0 and 1, where 0 indicates impossibility and 1 indicates certainty. The probability of an event 

A is denoted as 

P(A).

The probability distribution of a random variable is a function that assigns probabilities to the outcomes of a random experiment. It describes the likelihood of each possible outcome.

There are various probability distributions, each with its own formula. Some common probability distributions include:

Discrete Probability Distribution: This type of distribution deals with discrete random variables, where the outcomes are distinct and countable. The probability mass function (PMF) gives the probability of each possible value. The formula is typically denoted as 

P(X=x), where 

X is the random variable and 

x is a specific value.

Continuous Probability Distribution: Continuous distributions deal with continuous random variables, where the outcomes are uncountable and form intervals. Instead of a PMF, continuous distributions have a probability density function (PDF), which represents the likelihood of observing a value within a certain interval. The probability of observing a value within a range is given by the integral of the PDF over that range.

Some common probability distributions include the following:

Normal Distribution (Gaussian Distribution): Described by its mean 

μ and standard deviation 

σ, the PDF of the normal distribution is given by the formula:

2
f(x)= 
σ 
2π
​
 
1
​
 e 
− 
2σ 
2
 
(x−μ) 
2
 
Binomial Distribution: Describes the number of successes in a fixed number of independent Bernoulli trials. The probability mass function of the binomial distribution is given by:

P(X=k)=( 
k
n
​
 )p 
k
 (1−p) 
n−k
 
Poisson Distribution: Models the number of events occurring in a fixed interval of time or space. The probability mass function of the Poisson distribution is given by:

P(X=k)= 
k!
e 
−λ
 λ 
k
 
 
where 

λ is the average rate of occurrence.

These are just a few examples, and there are many other probability distributions used in different contexts. The choice of distribution depends on the nature of the random variable and the specific problem being analyzed
