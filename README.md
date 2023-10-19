# Database Systems CS305

## Title

Using Joins to find errors

## Assigned: 12 October 2023

## Due: END OF CLASS

![bases](./graphics/debugging.png)
Errors from entry in databases are common and can be hard to find to correct. With large databases, these kinds of errors may never be located for correction. In this activity, you will use `join`'s in SQL to determine where entry mistakes have been made.

## Project Goals

* To gain experience working with complex queries.
* To encode queries using a `join` to compare tables.
* To gain experience with writing queries to locate errors in databases.

## Instructions

Bigin by building your database using the builder file: `src/builder.txt`. Note, this database builder has an obvious error that will need to be addressed before it will be able to populate its table from the csv files in the `src/data/` directory. Once your database has been successfully built, please address the questions in the file `writing/reflection.md`.

## Data

The synthetic data in this activity can be found in `src/data/` and was obtained from the random data generating site; [generatedata](https://generatedata.com/generator).

## Project Assessment

This is a check mark grade. Your work will be considered complete when you see the green check-mark at the top of page of your GitHub repository.

## GatorGrade

You can check the baseline writing and commit requirements for this lab assignment by running department's assignment checking `gatorgrade` tool. To use `gatorgrade`, you first need to make sure you have Python3 installed (type `python --version` to check). If you do not have Python installed, please see:

- [Setting Up Python on Windows](https://realpython.com/lessons/python-windows-setup/)
- [Python 3 Installation and Setup Guide](https://realpython.com/installing-python/)
- [How to Install Python 3 and Set Up a Local Programming Environment on Windows 10](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-windows-10)

Then, if you have not done so already, you need to install `gatorgrade`:

- First, [install `pipx`](https://pypa.github.io/pipx/installation/)
- Then, install `gatorgrade` with `pipx install gatorgrade`

Finally, you can run `gatorgrade`:

`gatorgrade --config config/gatorgrade.yml`

## Seeking Assistance

* Extra resources for using markdown include;
  + [Markdown Tidbits](https://www.youtube.com/watch?v=cdJEUAy5IyA)
  + [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* Do not forget to use git commands to push your work to the cloud for the instructor to grade your assignment. You can go to your GitHub repository using your browser to verify that your files have been submitted. Please see the TL’s or the instructor if you have any questions about assignment submission.

Students who have questions about this project outside of the lab time are invited
to ask them in the course's Discord channel or during instructor's or TL's office hours.
