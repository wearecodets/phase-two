# Course Info

This is a practical, project-based course on Git, modern Javascript as well as relevant tooling in front and back-end development.

To mimic real-world software development scenarios in jobs, universities, or bootcamps, the teaching approach will be in the style of [guided-learning](http://www.teachingtoolbox.us/direct-vs-guided). This means students will take an active role in the learning process through their own self-discovery of information while the instructor will simply act as a facilitator or guide. Per week, this translates to roughly 20% classroom time (3 hours) and 80% self-learn work (12 hours). Additionally, the course utilizes [Github Classroom](https://github.blog/2018-08-15-classroom-report-predicts-positive-student-learning-outcomes/) to [familiarize students with real-world workflows](https://github.blog/2019-03-21-github-education-student-tested-peer-reviewed-and-now-published-by-the-association-of-computing-machinery/).

## Table of Contents

* [Expectations](#expectations)
* [Attendance & Participation](#attendance--participation)
* [Learning Guide](#learning-guide)
* [Classroom Agenda](#classroom-agenda)
* [Homework Pull Request](#homework-pull-request)
* [Using CodeAcademy](#using-codeacademy)
* [Note on Chromebooks](#note-on-chromebooks)

## Expectations

To increase your chance of success throughout the course, you are expected to:

1. ***Self-manage*** how you use your time wisely and build good study habits.
2. ***Self-motivate*** yourself both mentally and physically to commit to the program.
3. ***Self-learn*** the course topics through the resources we provide and also your own research.

> Each Saturday, come to class after having read the materials assigned for that week. Otherwise, it might be challenging to catch up on reading while completing the weekly assignment at the same time especially if you are totally new to programming.

## Attendance & Participation

Your attendance will not be tracked but your performance will. Participation and progress will be measured through Git commits, pull requests, and code reviews. That said, if you decide to not attend class, I would appreciate a simple heads-up on WhatsApp. If you rarely attend the class but are self-learning at home and have a solid commit/PR history — Good for you, buddy!

## Learning Guide

Each week above you will find learning materials categorized into these different sections:

* :closed_book: &nbsp; **Required Readings/Challenges** \
Read/do these before beginning of next Saturday class. As you finish each reading, [mark it as complete  using `[x]`](https://help.github.com/en/articles/about-task-lists#creating-task-lists) in your [`Work in progress` issue](https://github.com/wearecodets/phase-two/issues). This will be counted as your *reading participation for each week*. For CodeAcademy challenges, refer to the [Using CodeAcademy](#using-codeacademy) section below.

* :dart: &nbsp; **Weekly Mini Projects** \
These are the 3 mini projects we will build this week in class from [this Youtube playlist](https://www.youtube.com/watch?v=VuN8qwZoego&list=PLu8EoSxDXHP6CGK4YVJhL_VWetA865GOH). You are encouraged to pre-watch them.

* :pencil2: &nbsp; **Homework Exercises** \
Due before beginning of next Saturday class. You ***must*** participate in Thursday code review session for each homework assignment as this is one of the ways we measure your progress. Code reviews are done on Github and must be done even though you have incomplete work. [See the pull request section below](#homework-pull-request).

* :octocat: &nbsp; **Optional Resources** \
Additional materials that can help boost understanding of concepts. Though not mandatory, you are welcome to read these — [*Scientia potentia est*](https://en.wikipedia.org/wiki/Scientia_potentia_est).

## Classroom Agenda

Each 3-hour Saturday class session will strictly follow the following structure:

* **30 min:** Discuss homework challenges from PRs
* **45 min:** Mini Project #1
* **5 min:** Break 
* **45 min:** Mini Project #2
* **5 min:** Break 
* **45 min:** Mini Project #3 (Self-work)
* **5 min:** Practical applications of today's concepts

## Homework Pull Request

By submitting pull requests for each assignment, you will develop the skills and collaboration mindset that will help you when working with others on a real-world team. Pull requests allow you to experiment and document your  process and let the class instructor give feedback on them. 

For a video summary of the whole PR workflow, check out [this video](https://www.youtube.com/watch?v=oFYyTZwMyAg).

Pull request works like this:

1. After accepting an assignment, clone the repo to your local machine.

```
git clone git@github.com:wearecodets/hw1234-[YOUR GITHUB USER].git
```

2. Start a new branch called `answer` to work on solving the homework problem that is written as repo instructions.

```
git checkout -b answer
```

3. Commit changes as you go, leaving a trail of [descriptive commit messages](https://github.com/erlang/otp/wiki/writing-good-commit-messages).

```
git add -A
git commit -m 'add css grid to home page'
```

4. When ready for a code review, push your branch to remote and [open a pull request](https://help.github.com/en/articles/creating-a-pull-request#creating-the-pull-request) on Github. 

```
git push origin answer
```

In the pull request message, you must describe the following:

* What was most challenging about the homework so far?
* How did you solve it?

5. After creating a PR, [ask me for a review](https://help.github.com/en/articles/requesting-a-pull-request-review) by adding my name under the **Reviewers** section in the right sidebar.

![Review](https://res.cloudinary.com/yicf/image/upload/w_350/v1561211575/Code%20The%20Web/pr-review.jpg)

6. We will review your code on Thursday and you will have until the homework deadline to correct mistakes or improve your code. 

> Note that after creating a PR you can continue to make changes locally, commit and push them to Github. A PR does not mean that your work is complete; You should continue to improve it after reviews.

7. After my approval, you may merge the `answer` branch to `master`.

![merge](https://res.cloudinary.com/yicf/image/upload/w_350/v1561291405/Code%20The%20Web/merge-pr-button.jpg)

## Using CodeAcademy

After signing in, *DO NOT upgrade your CodeAcademy subscription to Pro*. There is no need for you to do the exercises with PRO label on them — only do the free ones:

![No PRO](https://res.cloudinary.com/yicf/image/upload/w_500/v1560677108/Code%20The%20Web/codeacademy.jpg)

Similarly, if a pop up appears after a lesson, click **Start next lesson** to skip the PRO project:

![No PRO Project](https://res.cloudinary.com/yicf/image/upload/w_500/v1560679730/Code%20The%20Web/codeacademy-popup.jpg).

## Note On Chromebooks

After powering the laptop on, you will get a screen with a red exclamation mark. At this point, you ***must*** press **Control + l** on the keyboard and you will boot directly to Linux. If you wait too long, the laptop will start beeping, notifying you to press **Control + l**. **That is the lowercase letter l, not the number 1.**

:warning::bangbang::bangbang: &nbsp; ***IMPORTANT:*** **DO NOT PRESS SPACE!!! &nbsp; THIS WILL ERASE THE LINUX OPERATING SYSTEM AND YOUR DATA!!!** &nbsp; :bangbang::bangbang::warning:

![Exclamate](https://res.cloudinary.com/yicf/image/upload/w_600/v1561341976/Code%20The%20Web/chrome-os-verification.jpg)

Some details about your machine:

  * User: `yicf`
  * Pass: `yicf`
  * Home folder: `/home/yicf` (or `~`)
  * Development folder: `/home/yicf/Development` (aliased to `dev`)