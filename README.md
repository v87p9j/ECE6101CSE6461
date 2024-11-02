java c
ECE6101/CSE6461 
Homework 1 Assignment 
Autumn 2024 
Expected Completion Date: September 26, 2024
1.  (Garcia-Widjija 1.2)
•  Describe what step-by-step procedure might be involved inside the network in making a telephone connection.
•  Now consider a personal communication service that provides a user with a personal telephone number. When the number is dialed, the network establishes a connection to wherever the user is located at the given time.  What functions must the network now perform. to implement this service?
2.  (Garcia-Widjija 1.5)Suppose that network addresses are scarce and are assigned so that they are not globally unique; in particular, suppose that the same block of addresses may be assigned to multiple organizations.  How can the organizations use these addresses?   Can users  from two such organizations communicate with each other?
3.  (Garcia-Widjija 1.9)
•  Suppose that an interactive videogame is accessed over a communication network What requirements are imposed on the network if the network is connection-oriented) connec- tionless?
•  Repeat part (a) if the game involves several players located at different sites.
•  Repeat part (b) if one or more of the players is in motion, for example, kids in the back of the van during a summer trip.
4.  (Garcia-Widjija 1.15)
The propagation delay is the time required for the energy of a signal to propagate from one point to another.
The speed of light in cable is 2.3 × 108m/s.  Consider the following networks:
a circuit board 
10 cm 
a room 
10 m 
a building 
100 m 
a metropolitan area 
100 km 
a continent 
5000 km 
up and down a geostationary satellite 
2 x 36000 km Further consider the transmission speeds 10,000 bits/second; 1 megabit/second; 100 megabits/second; 10 gigabits/second.
How long does it take to send an L-byte file and to receive a 1-byte acknowledgment back? Let L = 1, 103 , 106 , and 109  bytes.
5.  Prove that finite  additivity  follows from countable  additivity.
6. From the axioms of probability, prove the following:
(a) For an event A and its complement Ac , prove that Pr{Ac } = 1 − Pr{A}
(b) If A ⊆ B, then Pr{A} ≤ Pr{B}.
7.  Show that if Pr{A|B} > Pr{A} then Pr{B|A} > Pr{B}.
8. A regular die is thrown n times.  What is the probability that “6” comes up n − 1 times in the n throws?
9. Let X be a non-negative random variable with distribution f. Show that

and

10. X and Y are random variables.
(a)  Show that E[X] = E[E[X|Y]].<代 写ECE6101/CSE6461 Computer Communication Networks Homework 1 Assignment Autumn 2024
代做程序编程语言br>(b) If Pr{X ≤ x, Y ≤ y} = Pr{X ≤ x}Pr{Y ≤ y}, then show that E[XY] = E[X]E[Y], i.e. if two random variables are independent, then show that they are uncorrelated.  Is the reverse true? Prove or disprove.
(c)  The moment generating function of a random variable Z is defined as ΨZ(t) := E[etZ ].
Now if X and Y are independent random variables then show that ΨX+Y(t) = ΨX (t)ΨY (t).
Also, if ΨX(t) = (λ-t/λ)n , then determine E[X] and Var  
(d)  Show the conditional variance formula:
Var(X) = E[Var(X|Y)] + Var(E[X|Y]) , 
where Var(X|Y) = E [(X − E[X|Y])2 |Y].
11.  Let X1, X2 , . . . denote a sequence of independent random variables that are identically dis- tributed with moment generating function ΨX (t). Let N denote anon-negative integer-valued random variable that is independent of the sequence X1, X2 , . . .. Further, let

Find the moment generating function of Y. Find the mean and the variance of Y.
12.  An ordinary 52-card deck is thoroughly shuffled. You are dealt five cards. (a) What is the probability that all five cards are sevens.
(b) What is the probability that at least one of the cards is a seven.
(c) What is the probability that none of them are seven.
(d) What is the probability that two out the five cards is a seven.
13.  Let X be a binomial random variable with parameters p ∈ (0, 1) and n = 0, 1, 2, . . .. In other words for k = 0, 1, . . . , n

If n ↑ ∞ and p ↓ 0 such that np → λ, show that the distribution of the random variable X converges to that of a Poisson random variable with mean λ .
14.  Carefully show that definitions I and II given in the notes for a Poisson process are equivalent. Hint: In deriving II from I, set up a differential equation in the following manner. First define P0(t + h) := P({N(t + h) = 0}). Then

Now let h → 0 and set up and solve the appropriate differential equation.  After solving for P0(t) proceed to solve for Pn(t) := P({N(t) = n}) in much the same manner.
15.  After traversing a wireless error filled channel packets arrive at a network node according a Poisson Process with rate λ .  These packets could have corrupted bits due to the wireless channel which has a bit error probability p.  A packet is said to arrive at the node successfully if no bits are in error.  The number of bits in a given packet is Poisson distributed with mean µ .  Assume that packets are not retransmitted.  Find the rate at which successful packets arrive at the network node.







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
