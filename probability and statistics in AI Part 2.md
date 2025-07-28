## **Measures of Central Tendency:**

These are statistical measures to identify the center of a data set.



#### **1. Mean (Average):**

Formula: **Mean=∑xi/ n**

* ​Affected by extreme values (outliers).
* Example: For scores \[2, 4, 6], Mean = (2 + 4 + 6) / 3 = 4



#### **2. Median:**

* Middle value when data is ordered.
* Not affected by outliers.
* Example: \[1, 2, 5] → Median = 2
* If even numbers: take average of middle two.
* Example: \[1, 2, 4, 5] → Median = 2+4/2 = 3



#### **3. Mode:**

* The most frequent value.
* Can have: No mode.
* One mode (unimodal).
* Two modes (bimodal).
* More than two (multimodal).





## **WHAT ARE MEASURES OF DISPERSION?**

*"Measures of Dispersion describe how spread out or scattered the data values are around a central value (like mean or median)."*



#### <b>WHY DISPERSION IS IMPORTANT?</b>

1. To understand data consistency or variability.
2. Two datasets can have the same mean, but very different spreads.
3. Helps in comparing stability across different datasets or populations.
4. Essential in risk analysis, quality control, and data modeling.



#### **KEY MEASURES OF DISPERSION:**



##### **1. Range:**

* Formula: Range = Maximum value − Minimum value.
* Shows only the extremes, not the full variation.
* Example: If data = \[2, 5, 8, 10], → Range = 10 − 2 = 8





##### **2. Variance (σ² or s²):**

*"Variance measures the average squared deviation from the mean."*



* Formula: Population Variance:𝜎^2 = ∑(𝑥𝑖−𝜇)2/N
* Formula: Sample Variance: s^2 = ∑(𝑥𝑖−x)2/n-1 

​

&nbsp; 

**Where:**

xi = each data value

&nbsp;    \_

μ or 𝑥  = mean

N = population size

n = sample size





###### **Interpretation:**

* Higher variance = data is more spread out.
* Low variance = data is closer to the mean.





##### **3. Standard Deviation (σ or s):**

*"Standard deviation is the square root of variance."*



Formula: σ= sqrt(σ^2) or s=sqrt(s^2)

&nbsp;

**​Why Take Square Root?**

* So that the units of SD match the original data (not squared).
* More interpretable than variance.



**Example:**

If variance = 25, then standard deviation = √25 = 5



**Interpretation:**

* If SD = 0 → no spread (all values are same)
* SD gives idea of typical distance from the mean



##### **4. Coefficient of Variation (CV):**

*CV is the ratio of standard deviation to the mean, usually expressed as a percentage.*



Formula: CV=( Standard Deviation/Mean)×100



**Purpose:**

* To compare variability between datasets with different units or means.
* The lower the CV, the more consistent the data.



**Example:**

* Data A: Mean = 100, SD = 5 → CV = 5%
* Data B: Mean = 20, SD = 5 → CV = 25%

Even though both have same SD, Data A is more stable.



## **SHAPE OF DISTRIBUTION: Skewness \& Kurtosis:**

*"These don’t measure spread directly, but describe how the data is shaped and distributed around the mean."*



##### <b>1.Skewness:</b>

*"Skewness measures the asymmetry of the distribution."*



###### <b>Types:</b>

1. =0 ---> Symmetric Shape --------->means Bell-shaped like normal distribution.
2. >0 ---> Positively skewed Shape --------->means Tail on the right side.
3. <0 ---> Negatively skewed Shape --------->means Tail on the left side.



**Example:**

* Income distribution is often positively skewed (a few people earn much more).
* Exam scores may be negatively skewed if most students perform well.





##### **2.Kurtosis:**

*"Kurtosis measures the "tailedness" or peakedness of a distribution."*



###### **Types:**

1. Mesokurtic ------> ≈ 3 (normal) Kurtosis Value ----->Normal bell-shaped curve shape.
2. Leptokurtic ------> >3 Kurtosis Value ----->Tall and narrow peak, heavy tails shape.
3. Platykurtic ------> <3 Kurtosis Value ----->Flat and wide peak, light tails shape.



**Interpretation:**

* High kurtosis: More outliers, sharp peak.
* Low kurtosis: Fewer outliers, flatter peak.

































































