---
layout: page
title: Problem Solving
---

When your new to programming, each project can feel like a field filled with landmines. It can be difficult to even describe what the problem is or why it's difficult, let alone move forward with beginning to solve it. At a high level, it can help us to break problem solving into three distinct phases.

* Deciding where to start
* Planning your approach
* Writing the code

Don't try to skip those first two! It can be tempting to think that you need to start writing code right away, but a little bit of planning can be immensely helpful.

## Deciding Where to Start

Let's imagine a friend of yours has asked you to create an application to track revenue and inventory for their bakery.

* Assuming that we are going to take on this project, what are some things that we might want to track specifically?
* Is there any part of this problem that feels more important than another?
* What feels like the easiest place to start if we were going to tackle this problem?

Discuss with a neighbor and share.

## Planning Your Approach

Given the same bakery example from above, let's assume that we've decided that we want to stat developing three classes to get started on our project: Pastry, Employee, and Store.

* What might be some of the attributes of a pastry?
* What might be some of the attributes of an employee?
* What might be some of the attributes of the store?
* What might be some of the things an employee might be able to do? What are their responsibilities?
* What might be some of the things the store might be able to do? What responsibilities does the store have?

Brainstorm and discuss with a neighbor.

### Pseudocoding & Rubber Ducking

Pseudocoding and rubber ducking help us break down problems into smaller pieces that we can complete one at a time.

At a high level:

* Rubber ducking is the process of asking yourself questions to determine what you might need to do next.
* Pseudocoding is writing down the high-level steps that you would take to solve a problem in plain English.

You could view the warmup that  you just completed as a version of rubber ducking with training wheels. In the future you might be presented with more of a blank slate, while here we helped you generate some of the initial questions. Let's use the answers to those questions to create a class for an Employee and add some methods to that class.

For example, one action that an employee might take would be to sell a pastry. If we were going to rubber duck to try to solve this problem, we might first ask ourselves what steps an employee takes when they sell a pastry. They first need to know the price of the pastry. Then they would need to tell a customer that price and take their money. Then they could check to see if they owed the customer any change. Then finally they would give that pastry to the customer.

Once we have those steps down, we can begin to pseudocode our solution. We could start by adding an empty method to an employee class and then capture the steps that we thought of as comments.

```ruby
class Employee
  def sell
    # Check price of pastry
    # Get money from customer
    # Give customer change
    # Give customer pastry
  end
end
```

The lines that are commented out above are what we call *pseudocode*. They will not run when our program runs, but we can use them to break down a problem and then write code that actually does accomplish these tasks in our codebase. We can now write these lines one-by-one. For example, we might take that first line and turn it into the following:

```ruby
class Employee
  def sell(pastry)
    # Check price of pastry
    price = pastry.price
    # Get money from customer
    # Give customer change
    # Give customer pastry
  end
end
```

Pick another one of the actions that an employee or store might take and write down the smaller steps that an employee might need to take to complete that action.

If we want to, we can then continue to rubber duck and pseudocode to break each one of these steps into smaller steps.

## Writing the Code

This class isn't about writing code, but ultimately that's what you'll need to do. The next step is to take all of that planning that you've done and use it to try to create a solution that actually works on your computer. But sometimes translating words into code can be difficult. If you knew how to do that, you wouldn't be here.

* How might you learn about the tools that you're using?
* What might you do when you get stuck?

Discuss and share.

### How to use your resources

You have a number of resources at your disposal over the course of the Turing program:

* Documentation, Google, and Turing lesson plans
* Other students in your cohort
* Students in other cohorts
* Mentors
* Instructors

Ultimately the thing to remember is to make sure to make learning your goal. Don't copy someone else's solution. Don't be satisfied walking away from a conversation with a mentor or another student, accepting their help, and not completely understanding the code that you have in your project. One way to test is to delete any code you wrote with another person and rewrite it yourself!

## Checks for Understanding

* What strategies might you use to break down a problem?
* What are some resources you might as you try to work through a problem?
* What will indicate to you that you that you're getting the most out of a particular project?

## Other Resources

* [More detailed info on deciding where to start](./deciding_where_to_start)
* [Notes and recommendations on learning new tools](./new_tools)
