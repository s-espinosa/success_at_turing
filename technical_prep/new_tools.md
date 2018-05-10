---
layout: page
title: Learning New Tools
---

One of Turing’s main goals is to teach you how to confront the unknown. It’s impossible for us to cover every technology that you may encounter in your career, so it’s much more important to us that we give you the tools to quickly learn new things.

Here are a few strategies and tips that you may find helpful as you attempt to learn about technical concepts and tools.

## Be Specific with Your Searches

When you’re using Google to find information on a topic, be sure to include search terms for the specific context in which you’re using the tool and what you are trying to do. For example:

* Searching for ‘arrays’ will give you many results in many different programming languages.
* Searching for ‘arrays Ruby’ will limit those search results to Ruby specific articles.
* Searching for ‘remove nils from array Ruby’ will give you results specific to Ruby that also include results specific to the task that you’re trying to accomplish.

## Check Multiple Sources

When trying to learn how to use a tool remember that in many cases you will not be the first one to encounter this problem, but also remember that problems that look similar may not be as helpful as they first appear. Be sure to review more than just the first solution that you find.

* Open a few tabs (around five is a good starting point) and check to see what you’re seeing that each result has in common. Try to get a general sense for available solutions before more carefully picking one or two to read more carefully.
* If it seems like implementing a solution is more difficult than it should be take time to step back to see if there might be alternatives you haven’t considered.

## Read Differently

Reading about code is a little different from reading about other things. In particular, there are a few strategies that you can use to scan for useful information quickly.

* **Look for Examples:** whether your looking at official documentation, a blog post, or Stack Overflow, responses that have actual code snippets will generally be more helpful than those that simply describe their solution. Additionally, starting with a code snippet will help you to determine how related a resource is to the particular problem that you’re having. One question to ask yourself: is this person trying to do basically the same thing I’m trying to do?
* **Try the Docs First:** Ruby, HTML, CSS, and JavaScript are each thoroughly documented online. When trying to use these tools, make the official documentation your first stop. This documentation may seem foreign at first, but with practice you’ll be able to pull the information you need fairly quickly.
* **Check Stack Overflow:** SO is a place online where developers can ask each other for advice. There are a few strategies that you can use specifically when reading SO.
    * **Skip the question:** this might seem sometimes a confused person’s thinking can confuse you further
    * **Look for answers that have many up votes and/or a check:** this is the community’s way of confirming a solution
    * **Prefer answers with code snippets**
    * **Don’t skip the comments on the solution:** sometimes a solution will get a check/upvotes, but comments will point out potential flaws, drawbacks, or alternatives

## Read Code Snippets

Code snippets can be very helpful, but frequently information is hiding in plain sight if you’re not used to reading them. Be sure to pay attention to the following:

**Comments:** Comments are frequently used in code snippets to provide additional context or explanation of the code that follows.

Ruby, HTML, CSS, and JavaScript all include ways to include lines in your program that are for the benefit of programmers and not to be run by the computer.

* Ruby comments start with a # character.
* HTML comments start with <--! and end with -->.
* JavaScript and CSS comments can start with //. Multiline comments can be wrapped in `/*` and `*/`.

Often the first line of a snippet will include a path to a file meant to indicate where in your application the code will live. For example: `# ./test/car_test.rb` indicates that the code below this commented out line exists in a file called `car_test.rb` which is located in a directory called `test`.

**Capitalization:** Capitalization matters in our code.

* `person` and `Person` refer to different things in our code. Be sure to pay attention to make sure you know which is being referenced in any code snippet you read.
* Sometimes (but not always) developers will use all caps to indicate a value that should be replaced (e.g. when you see `YOUR_USERNAME` in a code snippet the intention is usually for you to replace `YOUR_USERNAME` with your actual username)

## Maintain a Bias Towards Action

Once you’ve collected information from various sources, tend to try to implement some functionality to see what it does rather than identify a perfect solution. Be sure that you’re not getting stuck reading things, and instead start trying solutions. Even if something doesn’t work out, chances are that you’ll have more information about the problem than before. Consider checking out a Git branch if you feel particularly unsure of your course of action.

## Checklist
* Google the tool with search terms that will maximize the value of your results.
* Open at least six tabs. At least one of these should be a page with official documentation.
* Skim the information in each tab to see if there are any patterns.
* Pick one or a combination of approaches to try.
* Try to implement!
* Debug with the tools you have (pry/console log).
* Reach out to cohort members, instructors, mentors, or other devs.
* Consider alternative solutions.
