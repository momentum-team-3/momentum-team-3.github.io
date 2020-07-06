---
title: Mob Programming Note-Taking App
layout: default
---


# MobCoded Note-Taking App

We'll mob code a web application for taking notes, like the one you created for your front end assignment. A user should be able to log in to their account, display a list of all their notes, create new notes, edit existing notes, and delete notes.

Notes have a title, text, the date/time created and most recently updated (these latter two should not be user-editable but set automatically when the note is saved to the database). Users can categorize their notes by adding at least one category when they create a new note or edit a note.

CSS is not important in this project, but you should add minimal styling by simply linking to a library like Shoelace or Bootstrap.

You won't be able to do all of this so make some decisions about where to start and what to do later.

The repo we will use and commit to is here: [https://github.com/momentum-team-2/django-mob-notes](https://github.com/momentum-team-2/django-mob-notes)

## General roadmap for the Product

* Create a new Django project using the [Momentum Django Project Template](https://github.com/momentumlearn/django-project-template).
* Create an app inside that project called `notes`.
* Create your models with the required fields.
* Create a `Category` model with fields for a name and a slug, as well as a relationship to the Note. Users should be able to go to a category detail page using a slug url and see a list of all the notes in that category.
* Don't forget to make migrations for your models and run those migrations.
* Create a view called `notes_list` to show you the list of all your notes in `notes/views.py`. The list should show the note title and date updated. Link this view to the root URL. Create a template for this view.
* Create a view called `notes_detail` to show you all the information about a single note in `notes/views.py` and link this view to `notes/<int:pk>`. Create a template for this view.
* Extract the common pieces of your templates and use template inheritance to make a `base.html` template that both your notes list and notes detail templates inherit from.
* Create a `NoteForm` that uses `forms.ModelForm` to handle note data.
* Add the ability for logged in users to create, edit, and delete a note through the UI (instead of through the admin). Don't do all of these at once.
* Implement registration and login using `django-registration-redux`.

### Stretch goal

If we get through the basic app functionality, consider implementing this.

* The note list should be sorted by date updated. Add options to sort based on other criteria.
* Add the ability to write notes in markdown

## Mob programming rules

Each person must _verbally_ contribute to the code being written, but only one person at a time is typing. As always, our discussion will be guided by our respect for each other and our agreement from day one to protect our safe learning space. It's ok to be wrong and not to know something, so take risks.

**The Goal**: Finish this app during class time today (morning and afternoon).

We will switch roles every 10 minutes. Move fast, be decisive, write code and run it.

### The roles

**The Driver** This person shares their screen and does the typing. In this role, you are mainly a conduit for the ideas of the group, implementing what the Navigator asks you to. You are not generating code yourself.

**The Navigator** The navigator leads the way, making decisions based on the input of the group about what to do and giving direction about what to type to the driver.

**The Facilitator** The job of the facilitator is to moderate the discussion and be sure all voices are heard. This person leads the discussion, asks pertinent questions to generate ideas, and keeps things moving forward in cooperation with the Navigator.

**The Scout** This person is responsible for looking up syntax or documentation and may be asked to do that by anyone on the team.

**The Contributors** These developers make suggestions and offer helpful advice as needed. Facilitators may ask them directly for their input and moderate their contributions to the discussion.

### Role assignments

We'll shift roles at 10-minute intervals.

At the beginning of each shift, pull down all the code from the repo.

At the end of each shift, add, commit, and push all the code that has been written.

#### shift 1

driver: Shelby
navigator: Joey
facilitator: Rajee
scout: Russell
contributors: Tyler, Blake

#### shift 2

driver: Russell
navigator: Shelby
facilitator: Joey
scout: Tyler
contributors: Blake, Rajee

#### shift 3

driver: Tyler
navigator: Russell
facilitator: Shelby
scout: Blake
contributors: Rajee, Joey

#### shift 4

driver: Blake
navigator: Tyler
facilitator: Rusell
scout: Rajee
contributors: Joey, Shelby

##### shift 5

driver: Rajee
navigator: Blake
facilitator: Tyler
scout: Joey
contributors: Shelby, Russell

#### shift 6

driver: Joey
navigator: Rajee
facilitator: Blake
scout: Shelby
contributors: Tyler, Russell
