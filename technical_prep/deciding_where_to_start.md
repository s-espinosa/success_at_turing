---
layout: page
title: Deciding Where to Start
---

## First, Break the Problem Down

It is difficult to identify all of the different pieces of a problem at the outset. Some will be fuzzy, and some will feel more focused. Some will remain fuzzy until much later in the project. When you're first starting to work on a project, see if you can work to identify a few things that you know will need to happen (even if much of the problem still feels unclear!). Once you've done that, you can work on implementing those few items. Getting to work has three substantial benefits:

* Completing some work (even if it feels simple!) will give you a sense of accomplishment. You won't be looking at a blank canvas anymore!
* Once you have some code written, other problems will come into sharper contrast.
* Writing code gives you tools that you can use to write more code. You now have some things that you can use that may make solving other problems easier.

Once you've identified some potential places to start, the next step is to pick something and dive in! but where to start...

### If you know that you have limited energy…

* What will be the lightest lift? Do that!
* Alternatively, what feels most familiar? Solving one problem has the benefit of creating additional tools that you can use to attack the remaining problems.

### When you don’t know where to start write a test

* Writing a test will often help drive your decision making. If you later realize that some other piece of the application needs to be implemented first, it’s o.k. to skip the test (put an `x` in front of the `it` in MiniTest, or write `skip` in the first line of an `it` block.
* Again, maintain a bias towards action.

### If you don’t know how you want something to work...

Ask yourself how it would work in your ideal world. For example, if you want to display some information in a view, ask yourself, what would be the easiest thing for me to have access to in this view (e.g. an array? a hash? a single return value?), and then write the code in the view as though that were true. Now that you have an idea of what you want you can go worry about how to make it work in your model and/or controller.

### When I have a solution that doesn’t seem to be working check your assumptions

Read the output from your test carefully. Is the error coming from the file and line that you expect? If not, a number of things may have happened:

* You may have assumed that one piece of the puzzle was working that hasn’t actually been implemented.
* You may have completely solved the problem at hand and inadvertently broken something else without realizing. Sometimes it’s easy to not notice that you’ve actually succeeded in your current task if you continue to see errors pop up without reading carefully.

Use your tools to see what is happening

* Pry/console.log(): These tools can tell you the current values of variables at a given point in your test/application. Have you created the things you expected to create? Have you passed the values that you expected to pass? Don’t guess! Don’t stare at your computer screen! Use your tools to figure out what’s going on!

## Maintain a Bias Towards Action

Remember through all of this, keep trying things! Often in the process of working on one aspect of an application you will create a tool that makes some other easier. Alternatively, you will work on one part of an application and realize it’s more dependent on other functionality than you initially realized. This doesn’t mean that your time has been wasted. Even if you need to reassess the code that you’ve written up to this point, it’s likely that much of the code that you’ve written can still be used with some adjustments.
