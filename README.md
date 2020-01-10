# Welcome
Hi! Thanks for taking the VandyHacks Board Dev Assessment. This repository holds the problems that you'll be doing as part of the process for joining the dev or content teams on VandyHacks Board. This README is a bit long but please read it all - it's important!

Our process for determining technical competency this year is significantly different than past years. Our goal is that we get a more accurate sense of what skills potential board members already have and what we would need to invest in teaching for new board members this semester. We hope that this new process is more accurate as well as more fair to candidates. 

Depending on your performance on this assessment (note: we are **NOT** looking for perfect scores), your application, and your interview, we may invite you for a follow up pair programming interview. We'll send you an email on this!

If at any point, you have questions, please feel free to contact us at [dev@vandyhacks.org](mailto:dev@vandyhacks.org). We also appreciate comments and feedback on this process.

## How this assessment is structured?
You will have 24 hours to complete this assessment. We are not giving you 24 hours so you can work 24 hours straight on this assessment. We're giving you that amount of time so that you can schedule your own day and build in breaks. 

There are three levels as part of this assessment from level 0 to level 2. Each level is harder than the one that precedes it. As stated above, we are not necessarily looking for pefect scores. Do your best, don't stress out if you can't do a problem, and feel free to skip between problems.

### What resources am I allowed to use?
You are allowed to use any reference material you'd like (including open sourced code on the Internet). If you directly copy code from GitHub or Stackoverflow, you do **not** have to cite it. Real software engineering invovles cleverly reusing others' code - we will not penalize that. Likewise, you may install dependencies if you believe they're the best way to solve the problem.

You are **NOT** allowed to received aid from another person. That includes other candidates applying for board, friends not applying to VandyHacks, professors, family and so on. Additionally, you are not permitted to solicit help from strangers by posting on StackOverflow or any forum site. 

If you are confused by a question, please email dev@vandyhacks.org for clarification or find a current VandyHacks board member. 
 
Anyone involved in any anuthorized collaboration will be immediately rejected from board. 

After the deadline, feel free to talk to whomever you'd like and share your code wherever you'd like!

## What languages and tools can I use?

Short answer: anything you'd like.

Longer answer: all of the code that VandyHacks uses in production is Javascript (specifically, Typescript). Therefore, we're most interested in applicants who use those languages. We will look more favorably on submissions that use Javascript and even more favorably on submissions that use Typescript **BUT** we will accept submissions in any language. A correct submission in Java will be looked on more favorably than an incorrect submission in TypeScript We expect to accept some candidates who are not experienced in Javascript.

### Read this if you're using TypeScript
If you're familiar with TypeScript, you probably know that it's a superset of JavaScript so theoretically writing JavaScript in `*.ts` files would be "valid TypeScript". However, we will not count your project as using TypeScript unless it can pass the TypeScript transpiler under `strict: true` mode. Non-strict TypeScript will be counted as JavaScript.

## How do I do the problems?
You've been provided with one folder for each level. Each folder contains a README spelling out the problem. Each candidate has a unique input that you can retrieve at https://input.vandyhacks.org. 

### What do I submit?
For submission, you need to submit the output specified in the problem (the problem will specify what the file name and format should be) as well as the code you used to compute that. If you have any particular notes on how you did a specific level, inside that level's folder, include a file called `notes.md`.

In terms of submitting code, we'd prefer if you submitted a single file of code for each level within that level's folder. This should be easy to do with languages like JavaScript or Python. That said, if you prefer to use a language where one big project is more manageable (like C++ with CMake), you may make a top level folder in the repository with all your code. We ask that it be easy to identify the classes and/or methods you used for each problem - it should be obvious to a reader of your code how to execute your solutions for each level. 

In addition to submitting your code, please include instructions in a file called `instructions.txt` or `instructions.md` that describe how to run your code such as what languages to install, and what dependencies to download.

### What does my code have to output?
The problems will ask for you to write the output to a file. You do not need to implement the file system operations to open and write to a file. Instead, it's fine if you log your output to the console and then manually type or copy that into the appropriate file. 

Additioanlly, your code doesn't have to do 100% of the computation. For example, let's say we gave you the height of 4 people and asked who was the tallest. A perfectly acceptable solution would be logging their heights and just eyeballing which is the highest number. However, that would not be an acceptable solution if we gave you the height of 100 people - we'd expect you to write some sort of maximum number algorithm.

In general, the inputs you'll be provided will be on the longer side. However, if you use code to simplify it down to something easier that you can "eyeball" the solution for, we won't object. You should include a comment in your code or something in `notes.md` if that's your approach. 

### Quick aside on Git and GitHub
If you've taken ISD or above, you're probably familiar with how Git and GitHub work. If you're not, you should familiarize yourself with how to `git clone` (to download the assignment to your computer), `git commit` (to save your work's current state), and `git push` (to push your committed changes to GitHub so we can see them). 

## How will this be assessed?
VandyHacks will have an internal rubric that we use to assess your output and your code. We will grade on:
- Correctness
- Code style (this includes comments, spacing, proper variable naming, minimal code reuse, not testing if a boolean is `true` etc)
- Language used (we'll give a bonus for Javascript, and an extra bonus to Typescript with all other languages being treated equally)

If you think your code ouputs something incorrect, feel free to include a short explanation in `notes.md` (explained above) of what is wrong and what mistake you think led to that. We may give partial credit for mistakes that are accurately diagnosed.

Do note that we will not be communicating the score recevied to each candidate. Instead, based on the results of this, your interview, and your application, we may invite you to the pair programming interview. Also note that while you may not receive an invitation to the pair programming interview, you may still be accepted onto another VandyHacks committee. 

We will not consider any code pushed after the deadline. Code that is committed before the deadline but not pushed until after the deadline will not be considered. Manually changing a commit's datetime will result in disqualification from the process.

## When can I work on this?
From now until the deadline (found above).