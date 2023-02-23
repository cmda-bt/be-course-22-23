# Week 6

> No Deploy Fridays
>
> — [@iamdevloper][quote-author]

[![][inspiration-cover]][inspiration-link]

> [`Don’t deploy on Fridays, friends`][inspiration-link] by
> [**@cassidoo**][inspiration-author].

## Table of Contents

*  [Slides](#slides)
*  [Theory](#theory)
*  [Playground](#Playground)
*  [Assignments](#assignments)
*  [Hand in](#hand-in)

## Slides

_Coming Soon_

## Theory

When working with multiple people on an app, it is best to avoid working in the same files as much as possible. Until now you have probably written most of your code in your main .js file (called index.js or server.js for example). From now on try to keep the main .js file as small as possible and look into using [Express routers][express-routers] for handling differents paths. And when you look at routers, you will probably come into contact with the  **MVC architecture**. Another common feature is to look into **sessions or tokens** for authenticating a user (with a login for example). We'll cover this in the lecture but make sure you fully understand these concepts, the resources below can help.

*  [routers](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/routes)
*  [sessions and tokens](https://www.youtube.com/watch?v=GhrvZ5nUWNg)
*  [MVC - Model, View, Controller][model–view–controller]

## Playground
You can do these exercises before you start working on the assignments to get comfortable with the topics covered in class. Below are interactive self guided lesson modules from [freeCodeCamp](https://www.freecodecamp.org/learn).

*   [mongodb and mongoose](https://www.freecodecamp.org/learn/back-end-development-and-apis/#mongodb-and-mongoose)

## Assignments

### Combine

![Combine banner](assets/banners/combine.png)
The upcoming weeks you'll work with your team to create a complete matching application. Make a coherent application from all the individual features.

> **This is a team assignment but you'll be graded individually!** Each prototype contains an individually recognizable contribution of you based on the learning goals and topics of this course. So, you need to show you worked on something for back-end. For example; you can't just work on the CSS of the project because that was your role in the team.

#### Synopsis

*   **Homework**
*   **Time**: 10:00h
*   **Goals**: all subgoals,
*   **Due**: before week 8

#### Description

You probably need to rewrite parts of your code in order to combine all features and add more features. Be sure to use **[Express routers][express-routers]** and dive into to the **[MVC model–view–controller][model–view–controller]** architecture. 


### Topic

![Topic banner](assets/banners/topic.jpg)

Additionaly you can pick one or more topics to get **bonus points**. It's important that you really do a deep-dive into the topic. So extensive research documented in the wiki and advanced implementation.

> Pick one or more topics from the list below and work on those topics for your team assessment to get bonus points.

#### Synopsis

*   **Homework**
*   **Time**: 10:00h
*   **Goals**: subgoal 10,
*   **Due**: before week 8

#### Description
The topic can be anything related to back-end. The list below will give you some starting points. There are things like security enhancements, application structure, performance optimizations and many more.

→ [List of topics for inspiration][topics]

> Something not on the list? These are topics we as teachers came up with but if you always wanted to learn something that's not on the list, pitch it to your teacher!

## Hand-in

Let your teacher know what you are going to work on during the team assessment and what topic(s) you picked by opening an issue on our [GitHub issue tracker][issues]. Fill in the issue template of `topic` with the correct information.

Your assignment will be reviewed by teachers and student assistants, so expect people to read it and be ready for tips and tops!

[quote-author]: https://twitter.com/iamdevloper/status/1108993784132587520
[inspiration-cover]: assets/images/deploy-tweet.png
[inspiration-link]: https://twitter.com/cassidoo/status/1154809678607446016?lang=en
[inspiration-author]: https://twitter.com/cassidoo

[express-routers]: https://expressjs.com/en/guide/routing.html#express-router
[model–view–controller]: https://en.wikipedia.org/wiki/Model–view–controller

[issues]: https://github.com/cmda-bt/be-course-22-23/issues
[topics]: /topics.md
