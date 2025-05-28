# Github Branches
---
Welcome to GitHub branches.
After watching this video,
you will be able to explain the purpose of branches in
GitHub and describe how to merge changes into branches.
All files in GitHub are stored on a branch.
The main branch is definitive,
it stores the deployable version of your code.
The main branch is created by default, however,
you can use any branch as the main,
finished, deployable version of the code.
When you plan to change things,
you create a new branch and give it a descriptive name.
The new branch starts as
an exact copy of the original branch.
As you make changes,
the branch you created holds the changed code.
To create a new branch,
click the dropdown branch Main,
add new branch name into
a new branch text and select "Create Branch".
GitHub branches can be very
complex for large software projects.
For a simple project such as the ones
we are exploring, consider the following.
Start with a common base,
the initial source for this project.
At one point, the code is
branched while new features are developed.
In this example, both branches are undergoing changes.
When the two streams of work are ready to merge,
each branch's code is identified as a tip,
and the two tips are merged into a third combined branch.
Developers work on source files in a branch.
Since some projects take a while,
the source doesn't make sense right away.
To change the contents of a file, select the file,
click the pencil icon,
make the changes, commit the changes.
When the developer has completed their assigned work,
to save their changes, they commit the code.
Commit indicates that the developer
is convinced that the code represents
a stable platform for
the feature or set of features being developed.
When a developer commits a change source to their path,
they are required to write
a comment that describes the changes.
The comment should be meaningful and descriptive.
The developer can choose to commit to
the current branch or create a new branch.
Finally, click ```Commit changes```
Some best practices while writing a comment:
don't end the comment message with a period,
keep commit messages under 50 characters.
Use the extended window for the details.
Always write in an active voice.
Pull is used to initiate
the merging of branches in a way to capture changes.
A pull request makes
the proposed committed changes
available for others to review and use.
A pull can follow any commits
even if the code is unfinished.
A pull requires a user to approve the changes.
This can be the author of the change
or can be assigned within the team.
Note that GitHub automatically makes a pull request on
your behalf if you make a change
on a branch that you do not own.
Since the log files are immutable,
it is always possible to find
the person who approve the merge of the change.
To open a pull request,
click "Pull requests" and select "New pull request".
Select the new branch from the compare box.
Scroll down to view the changes.
Confirm that the changes are what you want to assess.
Add a title and description to the request.
Click "Create pull request."
The intent of Git repository is for
the main branch to be the only deployed code.
Developers can change source files in a branch,
but the changes are not
released until they are committed.
A pull command is issued,
the code is reviewed and approved.
The approved code is merged back into the main code.
To merge a committed code change into your main code,
click ```Merge pull request```, click "Confirm merge".
When all changes for a branch are complete,
that branch is considered obsolete and should be deleted.
In this video, you learned
all files in GitHub exist on a branch.
The main branch contains
the finished deployable version of the code.
Create new branches when you need to change the code.
The new branch starts as
an exact copy of the original branch.
As you make changes, the branch
that you created holds the changed code.
More than one branch can be
undergoing changes at the same time.
Saved changes are called commits.
Pull requests enable other users to
review and use the proposed changes committed.
When you are ready to merge
the changed code into the main branch,
you merge the committed code changes into your main code.
"""
