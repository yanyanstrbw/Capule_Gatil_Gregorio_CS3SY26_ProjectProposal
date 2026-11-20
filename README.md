# CS3SY26_ProjectProposal by AlMendozaof CSt Unit


## Project Proposal Template

### Project Title or Name of the Application	: inDecisive
### Section			   	      : Beryllium
### Group Members			    : Capule, Gatil, Greogrio
### Date (Proposal Date)  : Nov 5, 2026

### Project Description:
Our project, inDecisive is a project to help people, such as overthinkers and indecisive people, to be able to form an outcome through a well thought process. In today’s world, many people worry a lot about making a simple decision. We want to alleviate that problem for them by creating this program. They will go through several questions to gain a decision based on facts given and needed. It helps the targeted audience to make decisions and answers to “Should I ____?” questions.

It will start with a parent class, a parent class which has a basic flow of questions, answers, and a flow on how it works. This parent class will be the base, it is what will be inherited.

CLASS 1
Class Name: decision
Attributes: title
Methods: 
askUser (the question we will ask the user, has a yes or no answer and returns True or False)
answer (final answer to question)
start_asking (prints title)
run_questions (temporary, this is where questions will be)


The rest of the classes after Class 1 are each question, which only needs to use the method run_questions. It also inherits the title and overrides it.

CLASS 2
Class Name: goOutDecision (inherits from decision)
Attributes: title (inherits from class decision and overrides)
Methods:
run_questions (in this method, it will also call askUser while having questions and answers)

CLASS 3
Class Name: buyThisDecision (inherits from decision)
Attributes: title (inherits from class decision and overrides)
Methods:
run_questions (in this method, it will also call askUser while having questions and answers)

CLASS 4
Class Name: chatCrushDecision (inherits from decision)
Attributes: title (inherits from class decision and overrides)
Methods:
run_questions (in this method, it will also call askUser and answer method while having questions and answers)

CLASS 5
Class Name: doAssignmentDecision (inherits from decision)
Attributes: title (inherits from class decision and overrides)
Methods:
run_questions (in this method, it will also call askUser while having questions and answers

After all of these, there’s the main code which allows to you to pick from 4 choices
“Should I Go Out?”
“Should I Buy This?”
“Should I Chat My Crush?”
“Should I Do My Assignment?”
If you pick one, it will call the class and start method inherited to start the process.

Essentially, throughout the program, the user will be asked follow-up questions so that the program can determine what decision the user should make. These follow-up questions will also be answered with either “Yes” or “No”. When the program reaches its final verdict, it will display a message to the user. It will tell them whether they should definitely do the action, definitely not do the action, maybe do the action, or maybe not do the action.

Here is the class diagram to show how this will work.
https://drive.google.com/file/d/1hFnR7HEQIDYztvgbt26bCqxGDUhMZQMb/view?usp=sharing

The long term outcome of this project is to help indecisive people find an easier way to make decisions. It can provide an easier way for them to think so that they do not have to deal with stress or pressure in making decisions. This lessens the worries of people and lets them live more optimistic lives. This project can also possibly serve as a stepping stone for more ambitious projects that can help people in more specific situations.

Our objectives are:
Objective 1: Find common daily scenarios that most people find themselves in
Objective 2: See how we can use classes and subclasses to create an efficient way of coding responses to questions
Objective 3: Help people make different decisions in different common scenarios using the code
Objective 4: See how the simple ideas and coding patterns used in this project can be used to create more ambitious projects


[Click here for Rubrics and Sample projects](https://docs.google.com/document/d/1xKd1CqK6DcNWS2_oJPBNtY5n3I3Hqiw8FY3W295Iqfk/edit?usp=sharing)
