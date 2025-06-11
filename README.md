# cmsc430-project-1-solved
**TO GET THIS SOLUTION VISIT:** [CMSC430 Project 1 Solved](https://mantutor.com/product/cmsc-430-project-1-solved-2/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113941&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMSC430 Project 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
The first project involves modifying the attached lexical analyzer and the compilation listing generator code. You need to make the following modifications to the lexical analyzer, scanner.l:

1. A new token ARROW should be added for the two character punctuation symbol =&gt;.

2. The following reserved words should be added:

case, else, endcase, endif, if, others, real, then, when

Each reserved words should be a separate token. The token name should be the same as the lexeme, but in all upper case.

3. Two additional logical operators should be added. The lexeme for the first should be or and its token should be OROP. The second logical operator added should be not and its token should be NOTOP.

4. Five relational operators should be added. They are =, /=, &gt;, &gt;= and &lt;=. All of the lexemes should be represented by the single token RELOP.

5. One additional lexeme should be added for the ADDOP token. It is binary -.

6. One additional lexeme should be added for the MULOP token. It is/.

7. A new token REMOP should be added for the remainder operator. Its lexeme should be

rem.

8. A new token EXPOP should be added for the exponentiation operator. Its lexeme should be **.

9. A second type of comment should be added that begins with // and ends with the end of line. As with the existing comment, no token should be returned.

10. The definition for the identifiers should be modified so that underscores can be included, however, consecutive underscores, leading and trailing underscores should not be permitted.

12. A Boolean literal token should be added. It should have two lexemes, which are true and false. The token should be named BOOL_LITERAL.

You must also modify the header file tokens.h to include each the new tokens mentioned above.

The compilation listing generator code should be modified as follows:

1. The lastLine function should be modified to compute the total number of errors. If any errors occurred the number of lexical, syntactic and semantic errors should be displayed.

If no errors occurred, it should display Compiled Successfully. It should return the total number of errors.

2. The appendError function should be modified to count the number of lexical, syntactic and semantic errors. The error message passed to it should be added to a queue of messages that occurred on that line.

3. The displayErrors function should be modified to display all the error messages that have occurred on the previous line and then clear the queue of messages.

An example of the output of a program with no lexical errors is shown below:

1 (* Program with no errors *)

2

3 function test1 returns boolean;

4 begin

5 7 + 2 &gt; 6 and 8 = 5 * (7 – 4);

6 end;

Compiled Successfully

Here is the required output for a program that contains more than one lexical error on the same line:

1 — Function with two lexical errors

2

3 function test2 returns integer;

4 begin

5 7 $ 2 ^ (2 + 4);

Lexical Error, Invalid Character $

Lexical Error, Invalid Character ^

6 end;

Lexical Errors 2

Syntax Errors 0

Semantic Errors 0

You are to submit two files.

1. The first is a .zip file that contains all the source code for the project. The .zip file should contain the flex input file, which should be a .l file, all .cc and .h files and a makefile that builds the project.

2. The second is a Word document (PDF or RTF is also acceptable) that contains the documentation for the project, which should include the following:

a. A discussion of how you approached the project

b. A test plan that includes test cases that you have created indicating what aspects of the program each one is testing and a screen shot of your compiler run on that test case

c. A discussion of lessons learned from the project and any improvements that could be made

Grading Rubric

Criteria Meets Does Not Meet

Functionality 70 points 0 points

Defines new comment lexeme (5) Does not define new comment lexeme

(0)

Correctly modifies identifier definition to include underscores (5) Does not correctly modify identifier definition to include underscores (0)

Adds real and Boolean tokens (5) Does not add real and Boolean tokens

(0)

Defines additional logical operators (5) Does not define additional logical operators (0)

Defines additional relational operators

(5) Does not define additional relational operators (0)

Defines additional arithmetic operators

(5) Does not define additional arithmetic operators (0)

Defines additional reserved words and arrow symbol(5) Does not define additional reserved words and arrow symbol (0)

Adds new tokens to the token header file (5) Does not add new tokens to the token header file (0)

Implements modifications to display multiple errors on the same line (15) Does not implement modifications to display multiple errors on the same line (0)

Implements modifications to count and display each type of compilation error (15) Does not Implement modifications to count and display each type of compilation error (0)

Test Cases 15 points 0 points

Includes test case containing all lexemes (5) Does not include test case containing all lexemes (0)

Includes test case with multiple errors on one line (5) Does not include test case with multiple errors on one line (0)

Includes test case with no errors (5) Does not include test case with no errors (0)

Documentation 15 points 0 points

Discussion of approach included (5) Discussion of approach not included (0)

Lessons learned included (5) Lessons learned not included (0)
