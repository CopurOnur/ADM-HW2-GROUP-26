# Homework 2 - Soccer analytics

The goal of this assignment is to perform an analysis on the largest open collection of soccer-logs ever released, collected by [Wyscout] (https://wyscout.com/) containing all the spatio-temporal events (passes, shots, fouls, etc.) that occur during all matches of the entire season 2017-2018 of seven competitions (La Liga, Serie A, Bundesliga, Premier League, Ligue 1, FIFA World Cup 2018, UEFA Euro Cup 2016). A match event contains information about its position, time, outcome, player and characteristics.

## The repository consists of the following files:

#### **-main.ipynb:**
  > A Jupyter notebook which provides the solutions to all research questions and to all the core research questions.
  ---

---



```javascript

Research questions:
  1. [RQ1]:Who wants to be a Champion? 
     During a season could happen that a team has bad periods. 
     Let's visualize this trends!  
 	
 	2. [RQ2]:  Is there a home-field advantage?  

 	3. [RQ3]: Which teams have the youngest coaches?

 	4. [RQ4]: Find the top 10 players with the highest ratio between completed passes and attempted passes.  

 	5. [RQ5]: Does being a tall player mean winning more air duels?
  
  6. [RQ6]: Experience and Winning in the Premier League.Is there a relation?

 Core Research Questions 
 	1. [CRQ1]: What are the time slots of the match with more goals? 
  
  The CRQ1 showed an output problem when we merged all the exercise together. The real output should be:
  ['R. Lukaku','H. Kane','R. Sterling','Gabriel Jesus','J. Vardy','Roberto Firmino','Mohamed Salah','\\u00c1lvaro Morata',
  'M. Arnautovi\\u0107','A. Lacazette','W. Zaha','R. Mahrez']
  
 	2. [CRQ2]: Visualize movements and passes on the pitch!
  
             

```

---
#### **-theory.ipynb:**
  >How much running time does it take to execute splitSwap(a, 0, n)? (We want a Big O analysis.)
  >What does this algorithm do? Is it optimal? Describe the mechanism of the algorithm in details, we do not want to know only its final result.
  
---
 
#### **-bonus part:**
>In order not to have a too long and confusing 'main.ipynb' , we decided to show only the outputs of the bonus part(pdf files). The codes are really similar to the exercises with premier league except for the part of filtering the teams database.
- serie A needs a filter that take only 'Italy'
- ligue 1 needs a filter that take only 'France' and 'Monaco'
- bundesliga needs a filter that take only 'Germany'
- liga needs a filter that take only 'Spain'

  
