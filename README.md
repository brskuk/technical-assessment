
# Table of Contents

1.  [Background](#org6d88e6c)
2.  [Examples](#org4d032c7)
3.  [Resources to use](#orgf76edbb)
4.  [Task](#org6109c0f)
5.  [Target Audience](#orgb6b8b35)
6.  [Technical Constraints](#orgc9f4e0a)
7.  [Evaluation Criteria](#org90e0ed1)



<a id="org6d88e6c"></a>

# Background

We have an eccentric Scrabble playing client who sometimes requests us to write software that can help them train for their Scrabble matches, and the client has a new request.

This time around, they would like to be able to run a specific program, that given a sentence, will replace each word in the sentence with another word starting with the same letter that is the same length. If a particular word can&rsquo;t be found that matches the criteria above, then the original word should be returned. Another requirement is that the same input should return a different output each time. Said another way, the word that is picked should be any random word that fulfills the criteria.


<a id="org4d032c7"></a>

# Examples

Given the sentence **lightly fried fish are delicious**, the program may return **likable frier frog arm delegated**. Running it again may yield **lenient fuses foam any digressed**.


<a id="orgf76edbb"></a>

# Resources to use

The client trains for his Scrabble matches using the 58000 word list here: <http://www.mieliestronk.com/corncob_lowercase.txt>. The solution should therefore use this same word list to generate the new sentences.


<a id="org6109c0f"></a>

# Task

Create a solution that will allow our client to input their sentence and get their desired output.


<a id="orgb6b8b35"></a>

# Target Audience

Assume the client is of moderate technical competence (for example they know how to paste commands into a terminal), but is not a developer themselves, so you should clearly explain how to get the solution working on their own machine.


<a id="orgc9f4e0a"></a>

# Technical Constraints

This is an open ended question that can be achieved with any technology or approach you are comfortable with, but since this is an evaluation for a development position, we assume that some code will be involved, so we require the solution to be submitted in the form of a git repository on a hosted source control platform like Github, Gitlab, Bitbucket etc.


<a id="org90e0ed1"></a>

# Evaluation Criteria

The purpose of this task is for us to understand the way you think and work and to allow us to get some insight into your technical abilities. Please do not spend more than a few hours on this task - perfection is neither expected nor desired, but a working (or almost working) solution is.

Good luck! If you have any questions about this task, feel free to get in touch with the person that sent this evaluation your way.

