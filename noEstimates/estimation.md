---
title: All estimates are wrong! Some are useful 
---

Many software organizations struggle to deliver what they have promised on 
time and there is significant amount of effort being spent on producing 
and improving estimates. This has been going on for a few decades now and no 
approach to date has really managed to improve it significantly.   
**Why is that?**


1. **Estimated hours are not real hours:** We all know this but we still use techniques
to try and make them into real hours by applying anecdotal conversion factors. 

2. **Humans are lousy at estimating time:** When humans estimate time what they 
do is come up with a wishful thinking best case scenario. This is a well researched
bias that goes by the name [_Planning fallacy_](https://en.wikipedia.org/wiki/Planning_fallacy).
Planning fallacy also includes our tendency to over estimate benefits of doing the work at hand.
This has been very beneficial for us during the evolution as it has made it easier for us to 
justify starting to work on something we want to achieve but it can be problematic in modern
economic context.

2. **Software development is exploratory work:** In software development we seldom do
straight forward repetitive work and even if we do it is almost impossible to know how
the solution will work in the hands of the user. Our understanding on what we  are 
expected to build grows along the way so what we end up delivering is more or less never 
what we estimated in the beginning.

3. **We only estimate a small part of the work:** In general what we estimate is only a 
small part of the work namely Implementation and testing. And we assume that all other 
work is linearly proportional to that estimate but that is rarely the case. Things that 
are not taken into the estimates are Organisational complexity, technical debt, runtime disturbances ,refactoring, 
task switching, bug corrections, performance tuning etc. And these are often static and
often dominate the actual development work in determining the capacity of the organization.

4. **Different people take different amount of time to solve the same thing:** 

5. **Work is pushed into the organization:** Often organizations start initiatives without 
taking into consideration how much work the organization has capacity to finish and this 
generates multitasking and make previously started initiatives complete later than expected
even if the estimates in them self was ok.

5. **You can not add estimates:** It has generally been assumed that se can break down the 
problems into its parts and add them up. This works fine as long as the complidations of 
the individual parts are not interacting. If they are interacting multiplication 
of the estimates are more appropiate.

6. ** Estimates are misused:** 
![](estimatesDeadlines.png)  
Estimates are guesses made with limited information and should 
be used with care. Often the estimates are converted into commitments and time plans 
that is used to make promises to stakeholders that are hard to change. Often the person/team 
that has given the estimate is lower in the power hirarchy and thus are in a bad position when 
complications arise.   
  
    
  

### So what to do about it?

Organizations that focus on estimates and particularly works on improving estimates usually 
has a delivery problem that they probably would be more benefitted by solving. And it is well 
researched that spending more time estimating do not generate better estimates.   

Agile methods focuses on  has mechanisms to give good enough results with minimal estimation. 
In general it is built on three principles.

* **Disconnecting estimates from time**
* **Yesterdays weather **
* **Pull**

#### Disconnect estimates from time

Disconnecting estimates from time makes it easier to come up with estimates. Often this is done by 
relative estimations with story points. Story points is a comparative estimation technique where 
work is compared to other work. Story points also has the uncertainty built into 
the estimate by applying a discrete scale (1,2,3,5,8,13,21) which is very helpful. This has worked 
fine for a long time but more and more data suggests that you can get as good result for forecasting 
just counting the number of stories completed as you would taking their individual estimates into the 
forecast as long as you are good at dividing your scope into small individually deliverable 
chunks.

#### Yesterdays weather

The basis for yesterdays weather is that whatever happened in the near past is likely to be 
similar to what will happen in the near future so if a team can complete 5 stories/sprint on 
average then it is likely to continue to do so the upcoming sprints. Then the project duration 
is remaining stories divided by 5 and the cost for a story on 
average is the sprint cost divided by 5. This way is extremely powerful as it uses real data
of our current capacity in our forecasts. And as all forecasts they should be updated constantly to have an understanding on how things are going right now so that we can use the information to take action.

#### Pull

By only pulling in new work when old work has been completed and at the same rate as work is completed you
get a steady flow of done work to deliver and a stable work environment where variability is limited. It is 
also helpful to have a zero bug policy making sure that we do not pile up bugs to further reduce variance.
This will increase the understanding of the true delivery capacity and give a good foundation for realistic expectations

## Summary.
It is important to understand that estimates are guesses that we use to take decisions in an 
uncertain world they are wrong but still could be valuable if used the right way. Our understanding of the problem at hand will inevitably change and that is natural. So estimates are a snapshot of the understanding of the problem at hand and has a very short expiration 
date. When using estimates do not estimate things in hours and try to fit them into the schedule based on 
the available working hours of the team. Instead use estimation techniques to do quick and quite rough estimates with relative estimation rough estimates are often giving as good or better information than detailed estimates at a fraction of the effort. Plan / Track progress / generate forecasts based on the rate/cost of finishing deliverable stories. 
