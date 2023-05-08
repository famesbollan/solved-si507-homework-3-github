Download Link: https://assignmentchef.com/product/solved-si507-homework-3-github
<br>
You will need a github account to start and complete this homework assignment.

<h2><strong>Homework Objective:</strong></h2>

Demonstrate the ability to:

<ul>

 <li>Use git and github to maintain project history and collaborate</li>

 <li>Use branching and merging to support parallel collaborative work</li>

 <li>Create a program for Magic Ball 8</li>

</ul>

<h2><strong>Supporting Material:</strong></h2>

<ul>

 <li>Magic Eight Ball Possible answers: <a href="https://en.wikipedia.org/wiki/Magic_8-Ball">https://en.wikipedia.org/wiki/Magic_8-Ball</a></li>

 <li>Magic 8-ball simulator: <a href="http://www.8-ball-magic.com/index.php#anchor">http://www.8-ball-magic.com/index.php#anchor</a></li>

</ul>




Readings:

<ul>

 <li><a href="http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1/">http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1/ </a></li>

 <li><a href="https://readwrite.com/2013/10/02/github-for-beginners-part-2/">https://readwrite.com/2013/10/02/github-for-beginners-part-2/</a></li>

 <li><a href="https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control">https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control</a></li>

 <li><a href="https://git-scm.com/book/en/v2/Getting-Started-A-Short-History-of-Git">https://git-scm.com/book/en/v2/Getting-Started-A-Short-History-of-Git </a></li>

 <li><a href="https://git-scm.com/book/en/v2/Getting-Started-Git-Basics">https://git-scm.com/book/en/v2/Getting-Started-Git-Basics </a></li>

 <li><a href="https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging">https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging</a></li>

</ul>

<h3><strong>Part 1: Using Github and Creating Magic Eight Ball code (20pts)</strong></h3>

Find a partner and sign up your pairing <a href="https://docs.google.com/spreadsheets/d/1IFDv8mPh2TI4GOmt1b3hZRUdZEA6AjCbGIt2AgbfFe8/edit?usp=sharing">here</a>, so we know who’s working with whom.

There may be an odd number of people if someone is absent. If you don’t have a partner, you can join a group of two and follow the same process with some slight differences as a Person C — it’s not a problem to be a 3rd party in a group and won’t make much of a difference. See the bottom of this document if you are in a group of 3! (Could even be more fun.)




If you are encountering other difficulties and are unable to find a partner, please let your GSI know so you can come up with another way of fulfilling similar objectives.




<strong>There are (at least) two roles:</strong>

Person A

Person B




You’re encouraged to work on this together, side-by-side, and talk through both/all parts!




The instructions here are written in terms that are sometimes general and sometimes git-specific. For the general instructions, you will need to figure out how to translate the common-sense description into the appropriate git commands (of course taking advantages of all of the usual channels for getting help).




<strong>PERSON A:</strong>

<ul>

 <li>Create a directory on your personal computer and have git start tracking it.</li>

 <li>Create a magic_eight.py file</li>

 <li>Create a function that asks users “What is your question?” (or something similar) and saves the response.</li>

 <li>Create a repository on GitHub for your work, called SI507-HW03-(uniquename).</li>

 <li>Add Person B (and C) as a collaborator</li>

 <li>Connect your GitHub repository to your local repo</li>

</ul>




<strong>PERSON B:</strong>

<ul>

 <li>Get the repository</li>

 <li>Create a new branch called “add_questions”</li>

 <li>In the magic_eight.py file add code to pick an answer at random from the <a href="https://en.wikipedia.org/wiki/Magic_8-Ball">20 possible 8 ball answers</a>.</li>

 <li>Push your new code *and branch* to GitHub.</li>

</ul>

<strong> </strong>

<strong>PERSON A:</strong>

<ul>

 <li>Create a new branch called “check_question”</li>

 <li>Write code that checks if user input is a question (i.e., ends in a ‘?’) and, if not, prints “I’m sorry, I can only answer questions.” (or something similar)</li>

 <li>Edit the program so that it keeps asking for user input until the user inputs “quit”</li>

 <li>Get your changes onto GitHub</li>

</ul>




<strong>PERSON B:</strong>

<ul>

 <li>Get the latest code from GitHub</li>

 <li>Merge your branch into the master branch</li>

 <li>Get your changes back onto GitHub</li>

</ul>




<strong>PERSON A:</strong>

<ul>

 <li>Get the latest code from GitHub</li>

 <li>Merge your branch into the master branch (after Person B has completed merge)</li>

 <li>Get your changes back onto GitHub</li>

</ul>




<strong>PERSON A+B:</strong>

<ul>

 <li>Pull the master branch and verify that everything works</li>

</ul>







<strong>IF YOU HAVE 3 PEOPLE IN YOUR GROUP:</strong>

Add a Person C, who will follow the same steps as Person B, but both B and C will create different branches (say, “add_questionsB” and “add_questionsC”) and each add only 10 of the total answers.




BEFORE TURNING IT IN:

Edit the README.md file to include the names, uniqnames, section number, and github IDs of the 2 or 3 people who worked on the project.




<h3><strong>Extra Credit 1 (2 pts)</strong></h3>




For the first extra credit, you are going to implement a simple version of the classic card game <em>Go Fish</em> with a partner.  You will need to create a new repo on Github called   SI507-HW03-gofish-(uniquename) containing a file named <em>go_fish.py </em>(which you will later submit on canvas).  For the first extra credit, you will simply create a version of the game which asks for input from two human players taking turns (no computer players will be involved).




The goal of this part of the exercise is to familiarize yourself with collaborative coding and also give you some more experience/practice with concepts you have learned previously. (<em>HINT:</em> Feel free to use your Card, Deck, and Hand classes from Homework 2).




Go Fish Rules: <a href="https://en.wikipedia.org/wiki/Go_Fish">https://en.wikipedia.org/wiki/Go_Fish</a>




Adjustments To These Rules:

<ol>

 <li>You do not need to worry about selecting a dealer, ‘cutting the deck’, or ‘deal direction’ when dealing out the cards at the beginning of the game.  Simply start each human player with a hand of 7 cards.</li>

 <li>You have creative license in terms of how you structure the game, prompt the user for input, etc.  That being said, please include directions as to how to play in your output (ie. on someone’s turn, you might print the following when asking for input: ‘<em>Please choose a card rank you would like to ask the other player if they have (between 1-13):’ )</em></li>

</ol>




Once you have completed this part of the assignment, please submit a link to your repository.  You and your partner are expected to have each made <strong><em>at least two commits</em></strong> each. The README for your repo should list the names, uniqnames, section number, and github IDs of everyone who contributed to the project.

<h3><strong>Extra Credit 2 (2 pts)</strong></h3>

For the second extra credit, you are going to implement an autoplay feature for <em>Go Fish</em> which will allow you to run a game simulation between 2 and 4 computer players.  This implementation can simply have each computer player play randomly or you can implement a simple ‘intelligent play’ system should you choose to do so.  For this part of the assignment, you will create a branch of the repository you created for Extra Credit Part 1. The branch should be called ‘autoplay’. You will <em>not</em> merge this branch back into master, but keep it separate (it’s a different <em>version</em> of your Go Fish game).




The rules for this part of the assignment are rather open ended as well, however, please provide ample output which displays the actions and final outcome of the game clearly in the terminal.  At the beginning of the game, prompt the user to input how many computer players they would like to take part in the simulation (between 2 and 4).  For this portion of the assignment, you may deal each computer player 7 cards to start with.




As with the first extra credit, you and your partner are each expected to make <strong><em>at least 2 commits each </em></strong>(they should be real commits, with several lines of code added in each case) to this part of the assignment.  You don’t need to submit anything different for this. If we see that there is an autoplay branch in your repo, we will test it out to determine credit for this part of the assignment.







<strong>What to turn in</strong>:




All code must be executable. Any code that does not run in<strong> Python3</strong> will be <strong>given a score of 0.</strong>  You can receive partial credit for working programs.

Submit following python module(s):

<ul>

 <li>A link to your GitHub repository for Part 1</li>

 <li>Make sure the two (or three) of you have “registered” that you’re working together through the Google Sheets signup sheet</li>

 <li>(Optional) a link to your GitHub repository for the Extra Credit problems.</li>

</ul>







<strong> </strong>


