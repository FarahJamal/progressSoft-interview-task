- Describe in your own words what is z-score and Min-Max scaling and why would we need to use such normalization methods? describe by example, if possible.
```
A z-score describes the position of a raw score in terms of its distance from the mean, when measured in standard deviation units. The z-score is positive if the value lies above the mean, and negative if it lies below the mean.
z = (x – μ) / σ

Z = \frac{x - \mu}{\sigma}
Z	= 	standard score
x	= 	observed value
μ	= 	mean of the sample
σ	= 	standard deviation of the sample

Example problem: In general, the mean height of women is 65″ with a standard deviation of 3.5″. What is the probability of finding a random sample of 50 women with a mean height of 70″, assuming the heights are normally distributed?

    z = (x – μ) / (σ / √n)
    = (70 – 65) / (3.5/√50) = 5 / 0.495 = 10.1


Min-Max is one of the most common ways to normalize data. For every feature, the minimum value of that feature gets transformed into
  a 0, the maximum value gets transformed into a 1, and every other value gets transformed into a decimal between 0 and 1.
  
  For example, if the minimum value of a feature was 20, and the maximum value was 40, then 30 would be transformed to about 0.5 
  since it is halfway between 20 and 40. The formula is as follows:
  
  (value - min) / (max - min)
```
![Z-Score Explain](https://www.simplypsychology.org/standard_normal_distribution.png?ezimgfmt=ng%3Awebp%2Fngcb30%2Frs%3Adevice%2Frscb30-1)
- 
- We used Junit5 in our test cases, describe in your own words why would we use such library? 
what is unit testing and why would we use it?
```
where any given test covers the smallest unit of a program (a function or procedure). 
It may or may not take some input parameters and may or may not return some values.

We write tests to verify the correctness of a program's behaviour.

Unit tests are designed to allow you to quickly run tests on your application using a very large and diverse set of different data inputs. Additionally, the best unit tests also account for boundary cases
, such as the data inputs that lie right on the edge of what is considered valid. 


```
- What is the IDE did you use?
```
IntelliJ IDEA 2021.2.2 [Ultimate Edition]
 ```

- Name the Java APIs you used?

```
import java.io.*;
import java.math.BigDecimal;
import java.math.MathContext;
import java.math.RoundingMode;
import java.nio.file.Files;
import java.nio.file.Path;
import java.nio.file.Paths;
import java.util.*;
```

- Mention down any difficulties or concerns you faced while working on the task. Your feedback is appreciated :D.
```
I have faced a dumb problem xD working with maven dependency because I was working with gradle so it takes a lot time to run the project
In addition to make excutable .jar files
it was hard to read about mathmatices again but it was great to know new stuff
```

- If you implement any of the bonus points, please mentioned it in this file
```
I Provided an executable jar file which allows the evaluator to use the class run through command line.
```

- Did this task enrich technical skills or knowledge? If yes, tell us how: 
```
for sure,
I have learnt new stuff this task was great ,
I have learn more about unit tests and how to use maven as automation tool
```
