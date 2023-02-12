# [Code 401 Reading Notes](../README.md/#code-401---advanced-software-development)

## Prework - SQL

Structured Query Language is a language designed to allow both technical and non-technical users query, manipulate, and transform data from a relational database. SQL databases are very simple and therefore provide safe and scalable storage for millions of websites and mobile applications.

- [SQL Lesson 1](./img/SQL-1.PNG)
- [SQL Lesson 2](./img/SQL-2.PNG)
- [SQL Lesson 3](./img/SQL-3.PNG)
- [SQL Lesson 4](./img/SQL-4.PNG)
- [SQL Lesson 5](./img/SQL-5.PNG)
- [SQL Lesson 6](./img/SQL-6.PNG)
- [SQL Lesson 13](./img/SQL-13.PNG)
- [SQL Lesson 14](./img/SQL-14.PNG)
- [SQL Lesson 15](./img/SQL-15.PNG)
- [SQL Lesson 16](./img/SQL-16.PNG)
- [SQL Lesson 17](./img/SQL-17.PNG)
- [SQL Lesson 18](./img/SQL-18.PNG)

---

## [The Terminal](https://codefellows.github.io/common_curriculum/prework/terminal)

[The Command Line](https://ryanstutorials.net/linuxtutorial/commandline.php)

- Most of this was review since we had this assignment in previous readings. One useful thing though was when there is a file with a space in the title. To move or delete that file, you add quotes around it.

## Growth Mindset

I have become more aware of the impact my words and actions have on those around me, and am working on expressing myself in a more empathetic and understanding manner. I've also noticed that I'm better able to manage my own emotions and stress levels when I take the time to practice self-care and engage in activities that bring me joy. Through recent interactions with others, I am learning the value of active listening and how it can improve my relationships and ability to connect with those around me.

## Biases

I've noticed certain unconscious biases I have and the impact they can have on my thoughts and actions towards others. I'm making an effort to challenge these biases by seeking out diverse perspectives and actively listening to those with different backgrounds and experiences. I'm working on being more mindful of the language I use and the assumptions I make about others, and am working to replace these with a more open-minded and non-judgmental approach.

## Data Structures

One of the most important things to consider when deciding on the best data structure for a particular problem is the time and space complexity of the various operations that need to be performed on the data. Also, it is also important to consider the type of data you are working with and its characteristics, such as its size, whether it is static or dynamic, and whether it is ordered or unordered.

An infinite recursive call stack occurs when a function calls itself repeatedly without a proper termination condition, causing the stack to grow without bounds. To avoid an infinite recursive call stack, you need to ensure that the recursion terminates when a specific condition is met.

Here are a few common techniques to avoid an infinite recursive call stack:
- Base case: Define a base case or a terminating condition that will stop the recursion. Once this condition is met, the function should return without making any further recursive calls.
- Progressive shrinking: Ensure that the inputs to the function are reduced in size with each recursive call, so that eventually the base case will be reached.
- Proper ordering of the recursive calls: If the function makes multiple recursive calls, you need to make sure that each call leads to a smaller problem, so that the recursion terminates.