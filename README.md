# Web Basics: Week 1 Assignment

This assignment will teach you the following:

- How to use the command line
- How to add HTML elements to the DOM (document object model)
- How to use the basic features of `git`

---

## Issues and Feedback

Be encouraged to ask questions or point out issues in the assignment!

Mentors will be happy to help out and your fellow students will benefit from your input.

[Report an Issue](https://github.com/Code-the-Dream-School/CtD-Week-1-Git-Assignment/issues)

---

## Instructions

### Getting Started:

Clone this repository so that the code is available on your local machine:

> **Note:** Run this command from the directory where you want to store your code

    git clone git@github.com:Code-the-Dream-School/web-basics-1-week-1-[your-username].git

Navigate to the directory you just cloned in your terminal:

    cd web-basics-1-week-1-[your-username]

Create a new local branch to work on separate from the mainline branch (`master`):

    git checkout -b lesson1

Finally, open the project directory in your code editor and continue to the next section.

### Task List:

For this assignment, all changes will be made within the `index.html` file.

- [ ] Step 1: Add a page heading by creating an `<h1>` element inside of the `<body>` element
- [ ] Step 2: Add a sentence about what you are most excited about in this course by creating a `<p>` element below the `<h1>` element
- [ ] Step 3: Enclose the `<h1>` and `<p>` elements by wrapping them inside a `<div>` element
- [ ] Step 4: Add a class named "content-container" to the `<div>` element by adding a `class` attribute

Make sure to open `index.html` in your browser to test out your changes!

### Final Step:

Check the status of your local repository to double-check the changes you made:

    git status

Stage the HTML file that you edited:

    git add index.html

Create a commit for the changes you made and add a message:

    git commit -m "your message"

Switch back to the mainline branch:

    git checkout master

Merge your development branch into the mainline branch:

    git merge lesson1

Push your commit to the remote repository (visible in GitHub):

    git push origin master

---

Created by [Code the Dream](https://www.codethedream.org)
