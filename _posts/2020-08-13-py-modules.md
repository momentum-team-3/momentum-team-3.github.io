---
layout: post
title: Python Modules and Programs
tags: phase-2 python modules import
---

Breaking down programming problems into their smallest pieces is one of the most critical skills in programming. You'll need to practice this for the weekend assignment.

## Today's topics

- Modules and `import`
- Exceptions
- Program shape & design

## How to approach a large project

### Sketch it out before you write code

Developers need to sketch out their ideas. (This is the true purpose of whiteboards for engineering teams, not grilling job candidates on obscure algorithms!) A pencil and paper is a great tool for programming. If that isn't your style, use a stylus and tablet, a Google Doc, or whatever you like to jot things down. Don't start in the code editor, in other words!

- What is the program/product's purpose or goal? Restate it in your own words to be sure you get it.
- What is the core of its purpose? See if you can clear away the bells and whistles and get down to the simplest version of what it does.
- Bullet list out the main things it needs to do to achieve its purpose.
- Then go back and look at each bullet, and break it down further. What steps might need to happen first?
  - each step could be something you know how to do OR something you don't know how to do. Examples:
      - `Get the contents of a file`
      - `Figure out some way to choose a random word`
      - `Keep track of what letters have been guessed`
- Go back and re-read your list. What are you missing? Is there anything out of order? Have a realization about a step that could be made clearer? Revise it until it looks solid to you.
- **You may have to revisit this plan and revise it as you discover new problems to solve while you work!** This is ok! It is all in a day's work for a software developer.

Once you have a plan you think is somewhat doable, then you can start writing code. Work through your steps in the order that makes sense, keeping in mind that you can hard code values as placeholders where you need to.

**You must run your program repeatedly to get feedback about what is happening.**

**Change one thing at a time and work methodically.**

**Take breaks.**

**Talk to other developers when you are stuck.** Talking through the problem will often clarify what you need to do. See [Rubber Duck Debugging](https://rubberduckdebugging.com/).

Don't forget to use your print statements to give you necessary information as your program runs.


### 🐍 Code Break

[Try working with a module]({% link code-exercises/py-guess-number.md %})

### Project

[Mystery Word](https://classroom.github.com/g/yiygoPXt)

### Resources

- What does `if __name__ == "__main__"` do?
  - [Stack Overflow Answer](https://stackoverflow.com/questions/419163/what-does-if-name-main-do)
  - [Clinton's Answer](https://github.com/momentumlearn/student-resources/blob/master/articles/pymain.md)
- [The Hitchhiker's Guide to Python](https://docs.python-guide.org/)
- [Python notebooks](https://github.com/momentum-team-2/examples/tree/master/python-notebooks)

### Code from class
- [Mystery Word starter code](https://github.com/momentum-team-2/examples/tree/master/py_mystery_word_starter)
