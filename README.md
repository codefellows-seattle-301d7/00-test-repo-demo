![CF](https://i.imgur.com/7v5ASc8.png)  Test Repo (Demo)
=======
[![Build Status](https://travis-ci.org/codefellows-seattle-301d7/00-test-repo-demo.svg?branch=master)](https://travis-ci.org/codefellows-seattle-301d7/00-test-repo-demo) [![GitHub issues](https://img.shields.io/badge/Issues%3F-Ask%20for%20Help!-orange.svg)](https://github.com/codefellows/seattle-301d7/issues/new) 

#### This is only a test. Become familiar with the workflow for your lab assignments!

Get some practice in :smiley:

1. Fork this repository.  
2. Copy the resulting git link. 
3. `git clone` this fork into your `my-forked-repos` directory (review setup [instructions](https://github.com/codefellows/seattle-301d7/blob/master/README.md#create-and-setup-your-301-directory-structure)).  
4. `cd` into this repository.  
5. Immediately `git checkout -b your-name` (ex: git checkout -b rick-patci)  
  - Notice the "*build passing*" message icon in this README file? That's an import from Travis CI - just one of many continuous integration tools used by organizations and project teams all over the world! We use Travis CI in this class to help us lint code being submitted (in your case as the developer, it will test any PRs you submit for proper linting).
  - **Let's try and get a "build failing" message instead, so we can see what that's like**:
10. Within the `starter-code` directory, open up the `wat.js` file and remove the semicolon from the end of the line and save the file.
11. Back in our terminal, type `git status` to ensure any changes were actually being tracked by git.
12. Let's take this a step further and type `git diff` - git diff displays changes line by line, with red lines being the previous code, and green lines being the new code.
13. We should see a red line with the semicolon at the end, and a green line with a missing semicolon at the end.
14. Now to exit this diff, we type `q` to return back to the terminal.
11. Now, assuming we are still inside of the starter-code folder, we can:
12. `git add wat.js`
12. `git commit -m 'remove semicolon to make the lint test fail'`
13. `git push origin your-name`
13. Head over to GitHub to make a PR from `your-name`.
14. This will take you to a comment section that has some "bolierplate" (pre-strutured) comments. It is your task to fill in the blanks and follow the instructions :smiley:
15. Once finished with the PR comments section, submit the PR, copy the resulting link that you see in your URL path at the top of the browser window after creating the Pull Request (to submit in Canvas). 
16. Now let the test finish, and see what the result is! 
17. If you'd like to see an example, finished PR, check out mine! https://github.com/codefellows-seattle-301d7/00-test-repo-demo/pull/1

> Before we wrap up, notice the "Issues?" icon button next to the "Build Status" icon? If you're ever stuck in lab (after the 15 minute rule :wink:), click on the issues button and fill out the template answering all the questions and finally checking the boxes either by placing an 'x' inside the square brackets, or by clicking on the boxes after submitting the issue. This will notify the instructional team immediately! (TAs included).  

Try it out! Create a test issue now to get a feel for how it works (the orange button next to the build passing icon). :sunglasses:

**When finished, submit to Canvas the links to your PR as well as the sample Issue that you created.**
