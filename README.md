# programmingparadigm
In this task, we were asked to choose 4 programming languages(2 for Imperative programming paradigm and 2 for Declarative programming paradigm) to accomplish some tasks to have a better understanding on the differences of imperative and declerative paradigms. I chose Python and Java for Imperative language and SQL and Prolog for Declarative language. The tasks are the following:
- Compute the sum of numbers
- Compute the average of numbers
- List the numbers less than 10

# PYTHON
![Screen Shot 2022-02-23 at 12 01 14 AM](https://user-images.githubusercontent.com/70185585/155171133-d2ea7588-5a2e-46d1-8a95-4bbb6c941277.png)

Brief History of Python PL
####    Guido van Rossum of Centrum Wiskunde & Informatica (CWI) in the Netherlands created Python in the late 1980s as a replacement to the ABC programming language, which was influenced by SETL and was capable of handling exceptions and interacting with the Amoeba operating system. It went into effect in December 1989. Python is a general-purpose programming language that is widely used, interpreted, object-oriented, and high-level programming language with dynamic semantics.


Python Code Explanation
#####    I created 2 functions one is for getting the sum of the array which I named it as _sum() and one is _less() for getting the elements that are less than 10. I called these functions and print the returned values but on line 19 for the average, I divide the returned value of _sum() to the length of the array to get the average.

# JAVA
![Screen Shot 2022-02-23 at 12 01 34 AM](https://user-images.githubusercontent.com/70185585/155172977-ceaa7865-af6d-4784-b455-c7209d6fe58a.png)

Brief History of Java PL
#### In the early 1990s, Sun Microsystems' James Gosling and colleagues created Java, an object-oriented programming language. Unlike traditional languages, which are often designed to be compiled to native (machine) code or interpreted from source code at runtime, Java is designed to be compiled to bytecode, which is then executed by a Java Virtual Machine (usually via JIT compilation).  The goal for Gosling was to create a virtual machine and a language that was similar to C but had more homogeneity and simplicity than C/C++. Java 1.0 was the first public implementation, released in 1995. With free runtimes for popular platforms, it promised "Write Once, Run Anywhere." The language's syntax is similar to C and C++, but it has a simpler object model and fewer low-level features. Though they have similar names and a C-like syntax, Java and JavaScript are only distantly related.

Java Code Explanation
#####  Just like what I did in python, I created 2 functions one is for getting the sum of the array which I named it as sum() and one is less() for getting the elements that are less than 10. Again, I called these functions and print the returned values but on line 24 for the average, I divide the returned value of _sum() to the length of the array to get the average.

# SQL
![Screen Shot 2022-02-23 at 12 03 18 AM](https://user-images.githubusercontent.com/70185585/155176333-86cec405-e83f-4fd2-9552-f3c85ad5bdff.png)

Brief History of SQL PL
#### IBM researchers Raymond Boyce and Donald Chamberlin created the SQL programming language in the 1970s. Following Edgar Frank Codd's work "A Relational Model of Data for Large Shared Data Banks" in 1970, the computer language SEQUEL was established. SQL applications are used by businesses and other organizations to access and manipulate information and data in their databases, as well as to create and alter new tables. SQL aids in the handling of data kept in databases, allowing users to obtain the data they need when they need it.

SQL Code Explanation
##### In this code, I created a table first where I store the numbers. In order to store the numbers, I used the INSERT command and one by one I inserted all the given numbers. To get the sum of all the given numbers, I used SUM command and stated inside the parenthesis the column name whish is number where I stated in line 3 and also stated the table name which is digit where I declared in line 2. To get the average, I used the command AVG with the same column name and table name. And lastly for getting the numbers less than 10, I used the SELECT command and put a conditional statement at line 20 where it filters the numbers less than 10.

# PROLOG
![Screen Shot 2022-02-23 at 12 02 27 AM](https://user-images.githubusercontent.com/70185585/155177385-d21a7576-9d4f-4805-8d15-aa03c0ee57ea.png)

Brief History of Prolog PL
#### Prolog arose from studies conducted at the University of Aix-Marseille in the late 1960s and early 1970s. Robert Kowalski of the University of Edinburgh collaborated with Alain Colmerauer and Phillipe Roussel of the University of Aix-Marseille to build the fundamental design of Prolog as we know it today. Colmerauer's research at the time gave ways to codify the Prolog language, while Kowalski contributed the theoretical framework on which Prolog is built. Prolog is still widely used in North America and Europe today. Prolog was heavily utilized in the European Esprit program, as well as in the ICOT Fifth Generation Computer Systems Initiative in Japan. This project was created by the Japanese government in an attempt to create intelligent computers. In these historical computer endeavors, Prolog was a key actor.

Prolog Code Explanation
##### The first 2 lines are the codes for summation. It is is a recussion code where it checks the succeding elements of the array and you can see the array on the Stdin Inputs. The first line there is the input for summation and you will see the array. Next is getting the average where just like what we always do, we divide the sum of the array to length of the array and taht's it, you wil get the average but in this case we also checked if there is an element in the array. Lastly, for getting the elements less than 10 wjere we stated in our Stdin Inputs that the numbers we want to be stored in R are the elements less than 10.
