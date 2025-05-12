# ee360c-algorithms-programming-assignment-1-solution
**TO GET THIS SOLUTION VISIT:** [EE360C Algorithms Programming Assignment #1 Solution](https://www.ankitcodinghub.com/product/ee360c-algorithms-programming-assignment-1-solution/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91630&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE360C Algorithms  Programming Assignment #1 Solution&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (5 votes)    </div>
    </div>
The goals of this lab are:

<ul>
<li>Familiarize you with programming in Java</li>
<li>Show an application of the stable matching problem</li>
<li>Understand the difference between the two optimal stable matchings</li>
</ul>
<h2>Problem Description</h2>
In this project, you will implement a variation of the stable matching problem adapted from the textbook Chapter 1, Exercise 4, and write a small report. We have provided Java code skeletons that you will fill in with your own solution. Please read through this document and the documentation in the starter code thoroughly before beginning.

Gale and Shapley published their paper on the Stable Matching Problem in 1962. According to New York Times, in 2004, New York City matched eighth graders to high schools in this way which plummeted the number of unmatched students from 31,000 to about 3,000.

The situation is the following: There are <em>n </em>eighth-grade students who submit applications for high school in a given year, each interested in attending one of <em>m </em>available high schools in New York City, each with a limited number of admission spots. Each school has a ranking of the students in order of preference, and each student has a ranking of the schools in order of preference. We will assume that there are at least as many students graduating as the total admission spots available across all <em>m </em>schools (each school can have a different admission quota). The interest lies in finding a way of assigning each student to at most one school in such a way that all available spots across all schools are filled (since we are assuming a surplus of students, there may be some students who do not get assigned to any school).

We say that an assignment of students to high schools is <em>stable </em>if neither of the following situations arises:

<ul>
<li>First type of instability: There are students <em>s </em>and <em>s</em><sup>′</sup>, and a high school <em>h</em>, such that
<ul>
<li><em>s </em>is assigned to <em>h</em>, and</li>
<li><em>s</em><sup>′ </sup>is assigned to no high school, and</li>
<li><em>h </em>prefers <em>s</em><sup>′ </sup>to <em>s</em></li>
</ul>
</li>
<li>Second type of instability: There are students <em>s </em>and <em>s</em><sup>′</sup>, and high school <em>h </em>and <em>h</em><sup>′</sup>, so that
<ul>
<li><em>s </em>is assigned to <em>h</em>, and</li>
<li><em>s</em><sup>′ </sup>is assigned to <em>h</em><sup>′</sup>, and</li>
<li><em>h </em>prefers <em>s</em><sup>′ </sup>to <em>s</em>, and <strong>– </strong><em>s</em><sup>′ </sup>prefers <em>h </em>to <em>h</em><sup>′</sup>.</li>
</ul>
</li>
</ul>
So we basically have the Stable Matching Problem as presented in class, except that (i) a school generally wants more than one student, and (ii) there is potentially a surplus of eighth-grade students. There are several parts to this problem.

<h2>Part 1: Write a report [20 points]</h2>
Write a short report that includes the following information:

<ul>
<li>Give an algorithm in pseudocode (either an outline or paragraph works) to find a stable assignment that is <strong>high school </strong></li>
<li>Give the runtime complexity of your algorithm in (a) in Big O notation and explain why. <strong>Note: Full credit will be given to solutions that have a complexity of </strong><em>O</em>(<em>mn</em>).</li>
<li>Give an algorithm in pseudocode (either an outline or paragraph works) to find a stable assignment that is <strong>student </strong></li>
<li>Give the runtime complexity of your algorithm in (c) in Big O notation and explain why. <strong>Note: Try to make your algorithm as efficient as you can, but you will get full credit even if it does not match the runtime in (b) as long as you clearly explain your running time and the difficulty of optimizing it further.</strong></li>
</ul>
<strong>For the programming assignment, you do not need to submit a proof that your algorithm returns a stable matching, or of student/high school optimality.</strong>

<h2>Part 2: Implement a Checker to check stability of any given matching [20 points]</h2>
Given a Matching object m, you should implement a boolean function to determine if the pairing of students to high schools (stored in the variable returned by m.getStudentMatching()) is stable or not. Your code will go inside a function called isStable(Matching x) inside Program1.java. A file named Matching.java contains the data structure for a matching. See the instructions section for more information on how to test this method.

<h2>Part 3: Implement Gale Shapley Algorithm [60 points]</h2>
Implement both algorithms from parts (a) (high school optimal) and (c) (student optimal) of your report. Again, you are provided several files to work with. Implement the function that yields a student optimal solution stableMatchingGaleShapley_studentoptimal() and high school optimal solution stableMatchingGaleShapley_highschooloptimal() inside of Program1.java.

Of the files we have provided, please only modify Problem1.java, so that your solution remains compatible with ours. However, feel free to add any additional Java files (of your own authorship) as you see fit.

<h2>Instructions</h2>
<ul>
<li>Download and import the code into your favorite development environment. We will be grading in Java 1.8. Therefore, we recommend you use Java 1.8 and NOT other versions of Java, as we can not guarantee that other versions of Java will be compatible with our grading scripts. <strong>It is YOUR responsibility to ensure that your solution compiles with Java 1.8. </strong>If you have doubts, email a TA or post your question on Piazza.</li>
<li>If you do not know how to download Java or are having trouble choosing and running an IDE, email a TA, post your question on Piazza, or visit the TAs during Office Hours.</li>
<li>There are several .java files, but you only need to make modifications to java. <strong>Do not modify the other files. </strong>However, you may add additional source files in your solution if you so desire. There is a lot of starter code; carefully study the code provided for you, and ensure that you understand it before starting to code your solution. The set of provided files should compile and run successfully before you modify them.</li>
<li><strong>DO NOT add a package statement to the starter code</strong>. This will result in your code not compiling, thus receiving a 0 for the code portion of this assignment.</li>
<li>The main data structure for a matching is defined and documented in java. A Matching object includes:
<ul>
<li><strong>m</strong>: Number of high schools</li>
<li><strong>n</strong>: Number of students</li>
<li><strong>highschool preference</strong>: An ArrayList of ArrayLists containing each of the high schools’ preferences of students, in order from most preferred to least preferred. The high schools are in order from 0 to <em>m</em>−1. Each high school has an ArrayList that ranks its preferences of students who are identified by numbers 0 through <em>n</em>− 1.</li>
<li><strong>student preference</strong>: An ArrayList of ArrayLists containing each of the student’s preferences for high schools, in order from most preferred to least preferred. The students are in order from 0 to <em>n</em>− 1. Each student has an ArrayList that ranks its preferences of high schools who are identified by numbers 0 to <em>m</em>− 1.</li>
<li><strong>highschool spots</strong>: An ArrayList that specifies how many admission spots each high school has. The index of the value corresponds to which high school it represents.</li>
<li><strong>student matching</strong>: An ArrayList to hold the final matching. This ArrayList (should) hold the number of the high school each student is assigned to. This field will be empty in the Matching which is passed to your functions. The results of your algorithm should be stored in this field either by calling setStudentMatching(&lt;your solution&gt;) or constructing a new Matching(data, &lt;your solution&gt;), where data is the Matching we pass into the function. The index of this ArrayList corresponds to each student. The value at that index indicates to which high school he/she is matched. A value of -1 at that index indicates that the student is not matched up. For example, if student 0 is matched to high school 55, student 1 is unmatched, and student 2 is matched to high school 3, the ArrayList should contain {55, -1, 3}. If using the flag [-bf], an input with an existing matching can be given to check correctness of the isStableMatching()</li>
</ul>
</li>
<li>You must implement the methods</li>
<li>isStableMatching()</li>
<li>stableMatchingGaleShapley_studentoptimal()</li>
<li>stableMatchingGaleShapley_highschooloptimal()</li>
</ul>
in the file Program1.java. You may add methods to this file if you feel it necessary or useful. You may add additional source files if you so desire.

<ul>
<li>Test cases take the format of text files, which either have the file extension of .in or .extended.in. Here’s how to interpret each test case, line by line:
<ul>
<li>Line 1: m n</li>
<li>Line 2: m space separated integers, denoting the number of spots available in each high school. The first integer represents the number of open spots in high school 0, the next integer represents the number for high school 1, and so on.</li>
<li>The next m lines are the preference lists of the high schools, where each space-separated integer represents a student. The list goes from left to right, from most to least desirable. The first of these m lines is the preference list for high school 0, the next line is for high school 1, and so on.</li>
<li>The next n lines are the preference lists of the students, where each space-separated integer represents a high school. The list goes from left to right, from most to least desirable. The first of these n lines is the preference list for student 0, the next line is for student 1, and so on.</li>
<li>Last line (optional): n space separated integers representing a student-high-school matching. If the first integer is <em>x</em>, then the first student is assigned to high school <em>x</em>, the second student to the second integer, and so on. This is a way of hard coding in a matching to test your implementation of isStableMatching() in Part 2 before you complete Part 3. To see examples, see the last lines of the test cases with the file extension .extended.in.</li>
</ul>
</li>
<li>java is the main driver program. Use command line arguments to choose between your checker and your high school optimal or student optimal algorithms and to specify an input file. Use -gh for high school optimal, -gs for student optimal, and -bf for importing an existing matching (to check correctness of isStableMatching()). (i.e. java -classpath . Driver [-gh] [-gs] [-bf] &lt;filename&gt; on a Linux machine). As a test, the 3-10-3.in input file should output the following for both a student and high school optimal solution:
<ul>
<li>Student 0 high school -1</li>
<li>Student 1 high school 1</li>
<li>Student 2 high school -1</li>
<li>Student 3 high school -1</li>
<li>Student 4 high school -1</li>
<li>Student 5 high school -1</li>
<li>Student 6 high school -1</li>
<li>Student 7 high school 2</li>
<li>Student 8 high school 0</li>
<li>Student 9 high school -1</li>
</ul>
</li>
<li>When you run java, it will tell you if the results of your algorithm(s) pass the isStableMatching() function that <em>you coded </em>for this particular set of data. When we grade your program, however, we will use <em>our </em>implementation of isStableMatching() to verify the correctness of your solutions.</li>
<li>We will be checking programming style. A penalty of up to 10 points will be given for poor programming practices (e.g. do not name your variables foo1, foo2, int1, and int2).</li>
</ul>
&nbsp;

&nbsp;
