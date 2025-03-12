- Name: Janssen Benedict
- Class: Pemrograman Lanjut A
- NPM: 2306152102


# Module 5 - Java Profiling

## JMeter Test Plan Result Screenshots (GUI, Pre-Profiling)
(Each test had been run twice, that is why it appears as if there are twice as many results as there should be. Apologies for the confusion)

### For endpoint /all-student-name:
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_2_res1a.png)
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_2_res2.png)
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_2_res3.png)
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_2_res4.png)

### For endpoint /highest-gpa:
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_3_res1a.png)
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_3_res2.png)
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_3_res3.png)
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_3_res4.png)

## JMeter Test Plan Result Screenshots (CMD, Pre-Profiling)

### For endpoint /all-student-name:
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_results_2.png)

### For endpoint /highest-gpa:
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_results_3.png)


## JMeter Test Plan Result Screenshots (GUI, Post-Profiling)
(Each test had been run once)

### For endpoint /all-student-name:
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_2_res1a_after_profiling.png)
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_2_res2_after_profiling.png)
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_2_res3_after_profiling.png)
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_2_res4_after_profiling.png)

### For endpoint /highest-gpa:
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_3_res1a_after_profiling.png)
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_3_res2_after_profiling.png)
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_3_res3_after_profiling.png)
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_3_res4_after_profiling.png)

## JMeter Test Plan Result Screenshots (CMD, Post-Profiling)

### For endpoint /all-student-name:
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_results_2_after_profiling.png)

### For endpoint /highest-gpa:
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_results_3_after_profiling.png)


## JMeter Measurement Comparison (Pre-Profiling & Post-Profiling)
After executing proper refactoring, there is a significant improvement in the speed of the tests being executed. After proper profiling was done, the requests became quicker to run, with shorter runtimes for the endpoints that were accessed.
For the test plan accessing the /all-student-name endpoint, the test results displayed an average runtime of 556 ms before refactoring. After the refactoring process, the results now show an average runtime of 68 ms, an improvement by 87.8%.
For the test plan accessing the /highest-gpa endpoint, the test results displayed an average runtime of 56 ms before refactoring. After the refactoring process, the results now show an average runtime of 35 ms, an improvement by 37.5%.


## Reflection

### What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?

### How does the profiling process help you in identifying and understanding the weak points in your application?

### Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?

### What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?

### What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?

### How do you handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing using JMeter?

### What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?
