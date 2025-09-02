# **Probability:**

*Probability measures how likely an event is to occur*



* It ranges from 0 to 1.
* 0 = impossible even
* 1 = certain event



**Example:**

Tossing a fair coin:

Probability of heads = 0.5 =1/2

Probability of tails = 0.5 =1/2



### **1.Joint Probability:**

*Joint Probability is the probability of two (or more) events happening at the same time.*



##### **Notation:**

P(A ∩ B) or P(A and B)



**Example:**

A = getting heads on a coin

B = rolling a 3 on a die

P(A ∩ B) = P(getting heads AND rolling 3)

= P(A) × P(B) = 0.5 × (1/6) = 1/12



### **2.Marginal Probability:**

*Marginal Probability is the probability of a single event happening, regardless of other events.*

##### 

##### <b>Notation:</b>

P(A), P(B), etc.



**Example:**

You have a table showing number of boys and girls who like Math and Science:

|       | Math | Science | Total |

| ----- | ---- | ------- | ----- |

| Boys  | 10   | 15      | 25    |

| Girls | 20   | 5       | 25    |

| Total | 30   | 20      | 50    |



P(Math) = 30/50 = 0.6 → this is marginal probability of liking Math.





### **3.Conditional Probability:**

*Conditional Probability is the probability of an event A happening given that event B has already happened.*



##### **Notation:**

P(A | B) → "Probability of A given B"



##### **Formula:**

P(A | B) = P(A ∩ B) / P(B)



**Example:**

P(A ∩ B) = 1/12

P(B) = 1/6

→ P(A | B) = (1/12) ÷ (1/6) = 0.5



# **Probability Distributions:**

### **What is a Probability Distribution?**

*A probability distribution describes how probabilities are distributed over values of a random variable.*



### **Types of Random Variables:**



##### **1.Discrete Random Variable:**

* Takes specific, countable values.
* Examples: 0, 1, 2 heads in coin tosses.



##### **2.Continuous Random Variable:**

* Takes any value in a range.
* Example: height, weight, time (can be 5.2 sec, 5.21 sec, etc).





### **Properties of a Probability Distribution (for discrete):**

* All probabilities must be between 0 and 1.
* Sum of all probabilities = 1.



### **Discrete vs. Continuous Probability Distributions:**



##### **1.Discrete Probability Distribution:**

* Used for countable outcomes
* Example: Tossing 3 coins — number of heads can be 0, 1, 2, 3



**Examples:**

Binomial Distribution: Probability of success/failure in n trials

Poisson Distribution: Probability of a number of events happening in a fixed interval



##### **2. Continuous Probability Distribution:**

* Used for measurable values
* Probability for exact value is always 0
* We calculate probability over an interval, like: P(2 ≤ x ≤ 4)



**Examples:**

Normal Distribution (bell curve)

Exponential Distribution





# **Bayesian Probability:**

### **What is Bayesian Probability?**

*Bayesian probability is a method of updating probabilities based on new information.*

*It’s based on Bayes' Theorem.*



### **Bayes’ Theorem:**

##### **Formula:**

P(A∣B)= P(B∣A)⋅P(A)/P(B)

​

where,

P(A|B): Probability of A given B

P(B|A): Probability of B given A

P(A): Prior probability of A

P(B): Total probability of B



**Example:**

A disease affects 1 in 1000 people.

Test gives a positive result 99% of the time if someone has the disease (true positive).

But also gives a false positive in 5% of healthy people.

If you test positive, what’s the probability you actually have the disease?

so,

P(Disease) = 0.001

P(No Disease) = 0.999

P(Pos | Disease) = 0.99

P(Pos | No Disease) = 0.05



P(Disease∣Pos) =1.94












































































