# Resources

Hello!

This is just a loose collection of "must-read" or "nice-to-read" documents to create common ground for code practices. Think of it as a poor man's [Thoughtbot Playbook](https://thoughtbot.com/playbook). Which is going to be our first resource:

**The Thoughtbot Playbook**

[An high-level overview of app development](https://thoughtbot.com/playbook)

**The 12-factor App**

[All IR projects should be 12 factor.](https://12factor.net/). We should emphasize developer ergonomics and ease of deployment.

**Code Review**

**If you read nothing else, please read this.** [Code review process & etiquette is extremely important. It is one of the most critical growth channels for engineers, new or experienced.](https://hypothes.is/blog/code-review-in-remote-teams/)

**Git workflows**

I prefer the rebase flow, but it's likely we'll probably be working off of a vanilla merge or fork flow. Here is information about both.

[Overview of rebase workflow](https://www.atlassian.com/git/tutorials/merging-vs-rebasing)
[Forking workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/forking-workflow)
[Configuring git with ssh](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/)

**How to write good code**
Can be surprisingly difficult, even for experienced engineers. Some will tell you to read a classic Java volume called "Clean Code", which is a terrific book. [However, there's a fantastic, simplified javascript version that emphasizes clean code principles right on github.](https://github.com/ryanmcdermott/clean-code-javascript)

Some misc tips from me:
 - To become a greater javascript programmer, see if you can write code without using if or switch statements.
 - Emphasize pure functions over mutation. In fact, see if you can write code without ever using mutation or ever using a let statement.
 - Comments are apologies for not writing your code clearly enough. Use them wisely.
 - Don't leave commented out code in a master branch, ever.
 - Don't leave TODOs in the code, ever. Represent TODO items as tickets on the project kanban board.
 - Don't put console logs in your code...except inside your logger module. Think about logging logically systematically than random output.
 - The clean code manual was written for OOP. Keep in mind JS is strongest when written in a more functional style. Composition over inheritance, etc. There was a significant controversy years ago that ES6 classes would lead JS engineers in the wrong direction with their code style. After seeing ES6 mature and its usage spread, I have to agree.

**Style Guide**

[We use the AirBnb style guide](https://github.com/airbnb/javascript). Would recommended actually reading through a bit of it - they provide explanations for their various rules. The explanations reveal an astounding attention to detail and care for craft that we should all emulate.
