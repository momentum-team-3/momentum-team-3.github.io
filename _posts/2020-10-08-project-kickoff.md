---
layout: post
title: Ready Set Code!‍
tags: phase-4 agile final-project
---

## Before you start writing code

Today should be used for finalizing planning and doing research on data, technology, and tools you might need.

### Checklist for the whole team

- Every team member is clear on your MVP, and you know what you are building.
- You have added user stories and tasks (at minimum, for MVP) to your Trello board.
  - Your tasks should reflect the decisions you have made about how you will implement things.
  - Make sure your tasks are labeled according to what responsibilities belong to the front end or back end.
- You have created a team organization on GitHub and added every team member.
- You have created your project repo or repos on GitHub.
  - Make sure you have a `.gitignore` file! You can get one that is specific to your project at [gitignore.io](https://www.toptal.com/developers/gitignore).
- You are clear on the git and GitHub workflow for your team.
- 🚨 Make sure you are using `django-environ` and a `.env` file. This will be especially important for secret keys and sensitive info, like AWS credentials. **DON'T COMMIT YOUR SECRET KEYS!**

### Checklist for the back-end

- Make sure you are using Postgres and not SQLite.
- **Models!** What models will you need?
  - What fields belong on those models? Use the [Django Model Field Reference](https://docs.djangoproject.com/en/3.1/ref/models/fields/).
  - What relationships exist between your models? (one-to-many, many-to-many?)
    - Consider using [the CRC model](http://agilemodeling.com/artifacts/crcModel.htm) to help guide your discussions.
    - You should create an ER diagram for your models to map relationships. This may change as you work, but you should have a good plan to start with. See resources section below for helpful info on ERDs.
- What URLs will the front end need?
- What data will the front end request?
  - Are you returning HTML? -> What templates does the front end need, and who will make those?
  - Are you returning JSON? -? How will you structure your data?
- Deploy early and often -- who will deploy? Make sure more than one person on your team has the ability to do this.
- Consider appointing a rotating team lead who can be responsible for running standup, leading at check-in, and looking after the Trello board.

### Checklist for the front-end

- Can you map out a user flow through your app?
- **Wireframes for each interface the user will see**
  - With the input of back-end devs, can you say what URL corresponds to each page or interface the user sees?
  - If using React Router (with a separate front-end application), what urls do you need?
- What data will you need on each page or interface? Where is it coming from?
  - What requests will you need to make from the front end?
- Are you making forms? Discuss data with the back-end.
- What assets will you need?
- What is your general strategy for css (using a library or writing custom styles)?
  - Start to think about UI/UX and design

## Reminders

- Standup starting Monday 10/12
  - Three-to-Django @9:30 am
  - ClimbGuide @9:45 am
- First check-in Monday 10/12
  - Three-to-Django @1:30 pm
  - ClimbGuide @2:30 pm

Standup and check-ins will use the Zoom Phase 4 classroom.

## 🔖 Resources

- [Django Model Field Reference](https://docs.djangoproject.com/en/3.1/ref/models/fields/)
- [The CRC model](http://agilemodeling.com/artifacts/crcModel.htm)
- [What is an ERD?](https://www.lucidchart.com/pages/er-diagrams)
- [How to create a simple ERD](https://medium.com/@marcifey/using-crows-foot-notation-in-an-erd-2910fff5dd05)
- [GitHub Flow](https://guides.github.com/introduction/flow/)
- [Collaborating on GitHub](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests)
- [gitignore.io](https://www.toptal.com/developers/gitignore)
- [Django project template](https://github.com/momentumlearn/django-project-template): You don't have to use this, but it might be a good idea. Most, if not all, of your assignments used this structure.
