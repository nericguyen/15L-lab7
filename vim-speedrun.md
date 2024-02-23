# Welcome to my Speedrun Fixing a Bug in Someone's Hypothetical Code!!!!1!!1!

You are going to see me do the following:
* Log into my remote ieng6 account
* Clone a fork of the repository from Github using the SSH URL
* Compile and run the tests
* Edit the code file to fix the failing test
* Compile and run the tests
* Commit and push the resulting change to Github

## Logging into my remote ieng6 account

![image](https://github.com/nericguyen/15L-lab7/assets/149546505/254dc885-fa16-4956-a47f-3f39d61e4aff)
I typed out the command `ssh ern006@ieng6.ucsd.edu` by myself and then pressed \<Enter\>.  This lets me log into a remote server from the CSE basements in UCSD.
Then I double clicked `cs15lwi24` with my mouse and typed [command][c] (I'm using a Mac sorry) to copy the code and typed [command][v] in the terminal and pressed \<Enter\>.
This lets me start working in the directory for my account.  Just ignore this part honestly.

*Side Note: Notice how I was not prompted to input a password because I did magic with the SSH keys which I discussed in my previous blogposts, which you should totally read!*

## Cloning a fork of the repository from Github using the SSH URL

![image](https://github.com/nericguyen/15L-lab7/assets/149546505/b0774164-5a31-4b09-a23f-8cacfe560b08)

I clicked the big green `<> Code` button and then clicked "SSH" and copied the link to the ssh clone of the forked repository in my clipboard.

![image](https://github.com/nericguyen/15L-lab7/assets/149546505/d9ba1ed3-b2e9-4404-9c14-a36f92f252fe)

I then returned to my terminal and typed `git clone ` and then typed [command][v] to paste the link I copied.  Then I pressed \<Enter\>.

## Compiling and running the test

![image](https://github.com/nericguyen/15L-lab7/assets/149546505/d3cdd559-72dd-4f5a-a72d-053ce7f1a290)

I typed in the terminal [c][d][space][1][5]<\Tab\>, which automatically fills the line with the relative path that starts with "15" if there is only one, which there is.  I press
<\Enter\> to change the directory to **/home/linux/ieng6/cs15lwi24/ern006/15L-lab7-fork**.  To run the compiler and tester, there is a bash script already within the directory that I can run.
I type [b][a][s][h][space][t]\<Tab\>, which like before, fills it with the only relative path that satrts with t.  I press \<Enter\> and the tests run.

## Editing the code file to fix the failing test

![image](https://github.com/nericguyen/15L-lab7/assets/149546505/767149ce-0295-4ff6-b5d3-4ebfc7657eaf)

I type in the terminal [v][i][m][space][L]\<Tab\>, which attempts to fill in the space for me with the path that starts with "L."  ListExamples.java  ListExamplesTests.java
both start with L, and share the start "ListExamples," so the terminal fills it to say `vim ListExamples`.  I then typed [.][j][a][v][a] and then hit \<Enter\>.

![image](https://github.com/nericguyen/15L-lab7/assets/149546505/20445845-b164-4147-9c74-56f5a8670930)

It takes me to the code of `ListExamples.java` in the vim text editor.  I type [4][3][j].  The j command brings the cursor down one line, and the 43 does that command 43 times,
effectively bringing our cursor to line 44.  I type [1][1][l] to go to the end of the first word.  I type [x] to delete the `1` and then I type [i][2] to insert a `2`.
Then I type `esc`.  To save my work and exit the vim editor, I type [:][w][q] and then hit `<enter>`.

## Compiling and running the test

j
