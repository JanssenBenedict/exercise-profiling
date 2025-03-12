- Name: Janssen Benedict
- Class: Pemrograman Lanjut A
- NPM: 2306152102


# Module 5 - Java Profiling

## JMeter Test Plan Result Screenshots (GUI, Pre-Profiling)

### 1. For endpoint /all-student-name:
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_2_res1a.png)
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_2_res2.png)
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_2_res3.png)
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_2_res4.png)

### 2. For endpoint /highest-gpa:
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_3_res1a.png)
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_3_res2.png)
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_3_res3.png)
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_3_res4.png)

## JMeter Test Plan Result Screenshots (CMD, Pre-Profiling)

### 1. For endpoint /all-student-name:
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_results_2.png)

### 2. For endpoint /highest-gpa:
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_results_3.png)


## JMeter Test Plan Result Screenshots (GUI, Post-Profiling)

### 1. For endpoint /all-student-name:
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_2_res1a_after_profiling.png)
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_2_res2_after_profiling.png)
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_2_res3_after_profiling.png)
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_2_res4_after_profiling.png)

### 2. For endpoint /highest-gpa:
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_3_res1a_after_profiling.png)
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_3_res2_after_profiling.png)
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_3_res3_after_profiling.png)
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_plan_3_res4_after_profiling.png)

## JMeter Test Plan Result Screenshots (CMD, Post-Profiling)

### 1. For endpoint /all-student-name:
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_results_2_after_profiling.png)

### 2. For endpoint /highest-gpa:
![](https://github.com/JanssenBenedict/exercise-profiling/blob/main/images/Module%205/test_results_3_after_profiling.png)


## JMeter Measurement Comparison (Pre-Profiling & Post-Profiling)
After executing proper refactoring, there is a significant improvement in the speed of the tests being executed. After proper profiling was done, the requests became quicker to run, with shorter runtimes for the endpoints that were accessed.
For the test plan accessing the /all-student-name endpoint, the test results displayed an average runtime of 1252 ms before refactoring. After the refactoring process, the results now show an average runtime of 68 ms, an improvement by 94.6%.
For the test plan accessing the /highest-gpa endpoint, the test results displayed an average runtime of 86 ms before refactoring. After the refactoring process, the results now show an average runtime of 35 ms, an improvement by 59.3%.
These results show that performing profiling and refactoring to optimize the code can help increase the performance of the program significantly.


## Reflection

### 1. What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?
In the context of optimizing application performance, performance testing with JMeter helps with simulating how a program or application would perform from the user's perspective, a more broad and general perspective. JMeter executes test plans in order to evaluate the overall performance of the program or application under different loads and conditions.
On the other hand, profiling with IntelliJ Profiler performs an even more in-depth analysis when compared to JMeter performance tests. Profiling with Intellij Profiler provides a more specific and detailed analysis of the code, emphasizing more on the needs of the developer by showcasing which parts of the program that take up a lot of resources. This allows developers to identify any inefficient code or bottlenecks and perform the proper refactoring needed to resolve them.

### 2. How does the profiling process help you in identifying and understanding the weak points in your application?
The profiling process helps me in identifying and understanding the weak points in your application by providing me the specific and detailed breakdown on the application or program's execution. From that detailed recording of the execution, I can see which classes and methods take up the most time or contribute the most to the overall runtime of the application, allowing me to identify them and refactor them to increase the performance of the execution.

### 3. Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?
I personally think that IntelliJ Profiler is very effective in assisting me to analyze and identify bottlenecks in my application's code. The reason why is that it provides me a very detailed and complete analysis on my program's execution of a request. Important details, such as the method execution times, are provided and can be viewed directly within the IDE (IntelliJ IDEA), making analyzing and identification of program inefficiencies or bottlenecks more efficient and effective.

### 4. What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?
The main challenges I faced when conducting performance testing and profiling were properly understanding the testing and profiling results that I received, as well as figuring out the most appropriate refactoring that needed to be done to enhance the application's performance. I overcame these challenges by spending enough time to properly comprehend these results and figure out what the best ways to refactor the inefficient code would be.

### 5. What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?
The main benefit I gained from using IntelliJ Profiler for profiling my application's code is the ability to analyze my application code's performance and receive the specific results directly within the IDE (Intellij IDEA) itself. With the profiler being integrated into the IDE itself, the analyzing and refactoring process became more convenient and efficient.

### 6. How do you handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing using JMeter?
As of right now, I have not had any situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing using JMeter. However, if said conflicts were to happen, I would handle them by examining and evaluating the differences that are present, the program code related to those different results, and the configurations of both tools. I would also consult external sources that are trustworthy in order to gain some insight onto what exactly is making me experience differing results.

### 7. What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?
To optimize the application code after analyzing results from performance testing and profiling, I simplified or streamlined the code for the methods that make up a significant percentage of the runtime and I reduced the amount of calls to the database in those methods. I replaced the manual loops that were in the code with stream operations and made sure to make as little calls to the database as possible to help increase the speed of the operations.
To ensure that the changes I made didn't affect the application's functionality, I made sure to rerun the performance testing and profiling process in order to make sure that the application performs as expected. By doing this, I can verify that my changes didn't alter the functionality of the application.