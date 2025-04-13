# Java Streams Troubleshooting Guide
  
<hr />

#### Table of Contents:

1. [Overview of Java Streams](#streams)
2. [Mistake #1: Utilizing Streams with Non-Complex Iterations](#one)
3. [Mistake #2: Omitting .close() Method for Stream Sources](#two)
4. [Mistake #3: Improper Handling of Terminal/Console Operations](#three)
5. [Mistake #4: Too Many Parallel Streams](#four)
6. [Mistake #5: Modifying External Variable State](#five)
7. [Mistake #6: Null Values in Streams Not Being Handled](#six)
8. [Mistake #7: Suboptimal Implementation of Intermediate Operations](#seven)
9. [Mistake #8: .collect() Improperly Utilized for Mutable Reduction Scenarios](#eight)
10. [Mistake #9: Forgetting to Utilize sorted() Method with limit()](#nine)
11. [Mistake #10: Overlooking 'Optional' with the findAny() and findFirst() Methods](#ten)
12. [Supplemental Resources](#supplemental)
  
<hr />
  
## 1. <a name="streams">Overview of Java Streams</a>
  
<hr />
  
## 2. <a name="one">Mistake #1: Utilizing Streams with Non-Complex Iterations</a>
  
Instead of:
  
```
List<String> firstNames = Arrays.asList("Tyler", "Barry", "Sophia");
firstNames.forEach(System.out::println);
```
  
Restrict stream usage to more complex tasks, such as reducing, mapping, and filtering.
  
<hr />

## 3. <a name="two">Mistake #2: Omitting .close() Method for Stream Sources</a>

<hr />

## 4. <a name="three">Mistake #3: Improper Handling of Terminal/Console Operations</a>

<hr />

## 5. <a name="four">Mistake #4: Too Many Parallel Streams</a>

<hr />

## 6. <a name="five">Mistake #5: Modifying External Variable State</a>

<hr />

## 7. <a name="six">Mistake #6: Null Values in Streams Not Being Handled</a>

<hr />

## 8. <a name="seven">Mistake #7: Suboptimal Implementation of Intermediate Operations</a>

<hr />

## 9. <a name="eight">Mistake #8: .collect() Improperly Utilized for Mutable Reduction Scenarios</a>

<hr />

## 10. <a name="nine">Mistake #9: Forgetting to Utilize sorted() Method with limit()</a>

<hr />

## 11. <a name="ten">Mistake #10: Overlooking 'Optional' with the findAny() and findFirst() Methods</a>
  
<hr />
  
## 12. <a name="supplemental">Supplemental Resources</a>
  
* [Java Clean Coding Guide](https://github.com/chaseofthejungle/java-clean-coding-guide)  
* [Java Quick Reference Guide](https://github.com/chaseofthejungle/java-quick-reference-guide)
  
<hr />
  
TODO #1: Overview of 10 common Java stream errors, and how to resolve them with refined code.  
TODO #2: Add overview of Java streams.
