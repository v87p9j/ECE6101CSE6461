java c
ECE6101/CSE6461 
Homework 2 Assignment 
Autumn 2024
Expected Completion Date: October 11, 2024
1. Let {N1(t), t ≥ 0} be a Poisson Process with rate λ .  Can Z(t) = αN1(t) + βN2 (t) ever be a Poisson Process, where α and β are some non-zero constants.  In other words, are there any values of α , β, and N2(t) such that {Z(t)t ≥ 0} is a Poisson Process.  Please note that {N2(t), t ≥ 0} is not allowed to be either a Poisson Process, and is also not allowed to be a trivial random process (e.g., it is not a constant over all time). Carefully prove or disprove.
2. Let τ1  and τ2  be two exponentially distributed,  independent random variables with means 1/λ1  and  1/λ2 ,  respectively.   Show  that  the random variable min(τ1 ,τ2 ) is exponentially distributed with mean 1/(λ1 + λ2 ). Also show that P({τ1  < τ2 }) = λ 1 /(λ1 + λ2 ). Use these facts to show that an M/M/1 queue can be described by a continuous-time Markov chain with transition rates qn,n+1 = λ and qn,n−1  = µ,n = 0, 1, 2, . . ..
3.  A telephone company establishes a direct connection between two cities expecting Poisson traffic with rate 30 calls/min.   The  durations  of calls  are independent and exponentially distributed with mean 3 min. Interarrival times are independent of call durations.  How many circuits should the company provide to ensure that an attempted call is blocked (because all circuits are busy) with probability less than 0.01?  It is assumed that blocked calls are lost (i.e., a blocked call is not attempted again).
4. A switchboard has two outgoing lines and is concerned only with servicing the outgoing calls of three customers who never call each other. When a customer is not on a line, each potential caller generates calls at a Poisson rate λ .  Call lengths are exponentially distributed, with a mean call length of  .  If a caller finds the switchboard blocked, he never tries to retry that particular call. All call initiations and durations are independent of each other.
(a)  Determine the fraction of time that the switchboard is saturated.
(b)  Determine the fraction of outgoing calls which encounter a saturated switchboard.
5.  Show that the blocking probability PB  of the finite M/M/1/Nqueue PB  = pn can be obtained by equating the net arrival rate λ(1−PB) to the average departure rate µ(1−P0) and solving for PB .
6.  Consider an M/M/N/N queuing system with the arrival rate λn   =  λ and the dependent departure rate of µn  = nµ for 1 ≤ n ≤ N.
(a)  Show that the probability the system is in state n is an Erlang distribution. (b)  Compute the average number in the system.
(c)  Show that the average throughput is γ = µE[n] in two ways:
i. Use γ = εn(N)=0 µnPn
ii. γ = λ(1 − PB), where PB  is the blocking probability.
(d)  Little ’s theorem says that E [T] = γE[n] = µ/1 here.  Explain this result, i.e., there is no waiting time.
7. Find the mean, variance, and moment generating function 代 写ECE6101/CSE6461 Computer Communication Networks Homework 2 Assignment Autumn 2024Web
代做程序编程语言of a Poisson, Erlang, exponential, and Gaussian random variables.
8.  (Schwartz 2-3)
Calculate and plot the Poison distribution given by
p(k) = (λT)ke−λT/k!       k = 0, 1, 2, ···for the three cases λT = 0.1, 1, 10.  In the third case try to carry the calculation and plot out to at least A  = 20.   (Stirling’s  approximation  for  the  factorial  may be useful here.) Does the distribution begin to crowd in  and peak  about E(k)  as predicted by the ratio σk/E(k) = 1/√λT? 
9.  (Schwartz 2-5)
Refer to the time-dependent equation (2-12a) below
pn(t + ∆t) = [1 − (λ + µ)∆t]pn(t) + λ∆tpn−1(t) + µ∆tpn+1(t)governing the operation of the M/M/1 queue.   Start at time t= 0 with the queue empty. (What are then the values pn(0)?)  Let λ/µ = 0.5 for simplicity, take ∆t = 1, and pick λ∆t and µ∆t very small so that terms of (∆t)2  and higher can be ignored. Write a program that calculates pn(t + ∆t) recursively as t is incremented by ∆t and show that pn(t) does settle down eventually to the steady-state set of probabilities {pn)}.  Pick the maximum value of n to be 5.  The set of steady-state probabilities obtained should then agree with Eq.  (2-20) below
pn = (1 − ρ)ρn /(1 − ρN+1 ).
Note:  Eq.  (2-12a) must be modified slightly in calculating p0 (t + ∆t) and p5 (t + ∆t).  You may want to set the problem up in matrix. vector form.
10.  (Schwartz 2-9)Show that the blocking probability PB  of the finite M/M/1 queue is given by PB  = pN  by equating the net arrival rate λ(1 − PB) to the average departure rate µ(1 − P0) and solving for PB .
11.  (Schwartz 2-11)
Consider a finite M/M/1 queue capable of accommodating N packets (customers). Calculate the values of N required for the following situations:
(a) ρ = 0.5,    PB  = 10−3 ,    10−6
(b) ρ = 0.8,    PB  = 10−3 ,    10−6 Compare the results obtained.
12.  (Schwartz 2-17)
Consider the M/M/2 queue discussed. Derive Eq.  (2-43) below

the expression for the probability of state occupancy, and Eq.  (2-44), below

the equation for the average queue occupancy.  Plot µE(T) (normalized time delay) versus λ , the average arrival rate (load on the system) for the M/M/2 queue, and compare with two single-server cases: an M/M/1 queue with service rate µ and an M/M/1 queue with service rate 2µ . Check Fig. 2-27 below.

13.  (Schwartz 2-18)Refer to the multiple (or ample) server and queue with discouragement examples discussed in the text.  Show that the state probability distribution and the average queue occupancy are given, in both examples, by Eq.  (2-47) with Eq.  (2-48) below
pn/p0 = (λ/µ)n /n!
p0 = e−ρ                                                                     ρ = λ/µ,
and Eq.  (2-49) below
∞ 

respectively. However, the average time delay and throughput are different in the two cases. Calculate these two quantities in both cases and compare.





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
