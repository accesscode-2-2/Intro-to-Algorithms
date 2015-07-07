# Intro-to-Algorithms
## Access Code 2.2 - Algorithms Cheat Sheet
 
Summarization and Examples of algorithms taken from: http://www.scifac.ru.ac.za/javabook/ch02.htm
 
An algorithm is a set of rules that can be obeyed to solve a problem. 
Here are some simple restrictions on algorithms:
 
* The set of rules must be finite.
* The rules must be followed in some definite sequence, until a satisfactory result is achieved.
* The rules must cover any awkward situations that arise.
* Only one rule may be obeyed (that is, only one operation may be performed) at a time.

Now that the fundamentals are out of the way, Let's take a look at an exanple of a basic problem and how we would create an algorithm that solves it using our definition.

###Example Problem: 
*How does one get to see the film "Quantum of Solace"?*

Let's start by creating a list of steps that we would take to solve this sepcific problem.

####Solution:
``` 
	Go to the cinema
	Buy a ticket
	Watch the film
	Go home again
```
We have just created an algorithm to solve our problem.

However, often times when coming up with an algorithm as a solution to a problem, we need to also put in checks that test certain cases that we think might arise frequently. For example, how would our algorithm change if we took into account the possibility that for whatever reason the film "Quantum of Solace" was not showing at the cinema?

Let's take a look at an example of a more complete algorithm, which takes into account a couple of test cases, that can be applied to the same problem.

####Solution with Test Cases
```
begin  // Algorithm for going to see the film "Quantum of Solace"
      if "Quantum of Solace" is not showing
        then
          find something else to do
        else
          go to the cinema
          if there is a queue
            then
              join it at the back
              repeat
                shuffle forward
              until everyone in front of you has been served
          if seats are still available
            then
              buy a ticket
              find the corresponding seat and sit down in it
              repeat
                gaze at the screen and listen to the soundtrack
              until the film is over
            else
              mutter quietly
          leave the cinema
          go home again
    end.
```
