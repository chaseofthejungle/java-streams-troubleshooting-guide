# Java Streams Troubleshooting Guide
  
<hr />

#### Table of Contents (10 Common Mistakes + Supplemental Resources):

1. [Utilizing Streams with Non-Complex Iterations](#one)
2. [Omitting .close() Method for Stream Sources](#two)
3. [Improper Handling of Terminal/Console Operations](#three)
4. [Too Many Parallel Streams](#four)
5. [Modifying External Variable State](#five)
6. [Null Values in Streams Not Being Handled](#six)
7. [Suboptimal Implementation of Intermediate Operations](#seven)
8. [.collect() Improperly Utilized for Mutable Reduction Scenarios](#eight)
9. [Forgetting to Utilize sorted() Method with limit()](#nine)
10. [Overlooking 'Optional' with the findAny() and findFirst() Methods](#ten)
11. [Supplemental Resources](#supplemental)
  
## 1. <a name="one">Utilizing Streams with Non-Complex Iterations</a>
  
Instead of:
  
```
List<String> firstNames = Arrays.asList("Tyler", "Barry", "Sophia");
firstNames.forEach(System.out::println);
```
  
Restrict stream usage to more complex tasks, such as reducing, mapping, and filtering.
  
<hr />

## 2. <a name="two">Omitting .close() Method for Stream Sources</a>

<hr />

## 3. <a name="three">Improper Handling of Terminal/Console Operations</a>

<hr />

## 4. <a name="four">Too Many Parallel Streams</a>

<hr />

## 5. <a name="five">Modifying External Variable State</a>

<hr />

## 6. <a name="six">Null Values in Streams Not Being Handled</a>

<hr />

## 7. <a name="seven">Suboptimal Implementation of Intermediate Operations</a>

<hr />

## 8. <a name="eight">.collect() Improperly Utilized for Mutable Reduction Scenarios</a>

<hr />

## 9. <a name="nine">Forgetting to Utilize sorted() Method with limit()</a>

<hr />

## 10. <a name="ten">Overlooking 'Optional' with the findAny() and findFirst() Methods</a>
  
<hr />
  
## 11. <a name="supplemental">Supplemental Resources</a>
  
[Java Clean Coding Guide](https://github.com/chaseofthejungle/java-clean-coding-guide)  
[Java Quick Reference Guide](https://github.com/chaseofthejungle/java-quick-reference-guide)
  
<hr />
  
TODO: Overview of 10 common Java stream errors, and how to resolve them with refined code.
