# GENETIC ALGORITHM APPLY ON GENERATING LEARNING CALENDAR
> The algorithm I use to automatically generated learning calendar for college/university using credit system.

## Table of contents
* [References](#references)  
* [How I apply](#how-i-apply)  
* [Result](#result)  
* [Note](#note)

## References
1. [Wikipedia](https://en.wikipedia.org/wiki/Genetic_algorithm)
2. [Youtube MIT](https://www.youtube.com/watch?v=kHyNqSnzP8Y&t=1688s)
## How I apply
1. Determine algorithm conditions based on college/university. In my case, I run the algorithm with following conditions and corresponding adaption point:  
![](https://raw.githubusercontent.com/nmtri881994/Genetic-Algorithm-apply-on-generating-learning-calendar/master/images/AlgorithmConditions.PNG)

2. I devide all classes of college/university into smaller groups following faculty-course-major-group

3. Apply Genetic Algorithm to each group  
3.1 Generate random calendar for each class at the very start.  
3.2 Set the adaption point for each class by counting from all conditions.  
3.3 Sort the class group grow up by adaption point.  
3.4 Check succeed if the first class of group has adaption point less than optimal adaption point we set before.  
3.4.1 If succeed, go through next class group  
3.4.2 If not, make a loop, execute selecting, mutating, cross-over-ing phase. Break out of the loop till succeed or current generation > number of maximum generation.  

## Result
Following table showing you an overview how the algorithm process executes.
![](https://raw.githubusercontent.com/nmtri881994/Genetic-Algorithm-apply-on-generating-learning-calendar/master/images/Result.PNG)

And here are full calendar generated for each faculty-course-major-group  
** The lessons with name label colored by white are philosophy an the others are practice

Faculty: Cơ khí - Course: 2015 - Major: Cơ khí 1 - Group: 15  
![](https://raw.githubusercontent.com/nmtri881994/Genetic-Algorithm-apply-on-generating-learning-calendar/master/images/2015-ck1-15.png)

Faculty: Cơ khí - Course: 2015 - Major: Cơ khí 1 - Group: 16  
![](https://raw.githubusercontent.com/nmtri881994/Genetic-Algorithm-apply-on-generating-learning-calendar/master/images/2015-ck1-16.png)

Faculty: Cơ khí - Course: 2016 - Major: Cơ khí 1 - Group: 15  
![](https://raw.githubusercontent.com/nmtri881994/Genetic-Algorithm-apply-on-generating-learning-calendar/master/images/2016-ck1-15.png)

Faculty: Cơ khí - Course: 2016 - Major: Cơ khí 1 - Group: 16  
![](https://raw.githubusercontent.com/nmtri881994/Genetic-Algorithm-apply-on-generating-learning-calendar/master/images/2016-ck1-16.png)

Faculty: Cơ khí - Course: 2016 - Major: Cơ khí 6 - Group: 13  
![](https://raw.githubusercontent.com/nmtri881994/Genetic-Algorithm-apply-on-generating-learning-calendar/master/images/2016-ck6-13.png)

Faculty: Cơ khí - Course: 2016 - Major: Cơ khí 6 - Group: 14  
![](https://raw.githubusercontent.com/nmtri881994/Genetic-Algorithm-apply-on-generating-learning-calendar/master/images/2016-ck6-14.png)

## Note
  
[⬆ back to top](#table-of-contents)