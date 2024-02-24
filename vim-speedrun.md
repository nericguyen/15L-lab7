# Welcome to my Speedrun Fixing a Bug in Someone's Hypothetical Code!!!!1!!1!

You are going to see me do the following:
* Log into my remote ieng6 account
* Clone a fork of the repository from Github using the SSH URL
* Compile and run the tests
* Edit the code file to fix the failing test
* Compile and run the tests
* Commit and push the resulting change to Github

## Logging Into My Remote ieng6 Account

![image](https://github.com/nericguyen/15L-lab7/assets/149546505/130274f8-ab25-4610-8fc7-28b4a98a68bb)

I typed out the command `ssh ern006@ieng6-202.ucsd.edu` manually and then pressed `<enter>`.  This lets me log into a remote server for the CSE basements in UCSD.
Then I double clicked `cs15lwi24` with my mouse and typed `<command><c>` (simulataneously) to copy the code and typed `<command><v>` (simulataneously) in the terminal and pressed `<enter>`.
This lets me start working in the directory for my account.

*Side Note: Notice how I was not prompted to input a password because I did magic with the SSH keys which I discussed in my previous blogposts, which you should totally read!*

## Cloning a Fork of the Repository from Github Using the SSH URL

![image](https://github.com/nericguyen/15L-lab7/assets/149546505/b0774164-5a31-4b09-a23f-8cacfe560b08)

I clicked the big green "<> Code" button and then clicked "SSH" and copied the link to the ssh clone of the forked repository in my clipboard.

![image](https://github.com/nericguyen/15L-lab7/assets/149546505/d9ba1ed3-b2e9-4404-9c14-a36f92f252fe)

I then returned to my terminal and typed `git clone ` and then typed `<command><v>` (simulataneously) to paste the link I copied.  Then I pressed `<enter>`.

## Compiling and Running the Test

![image](https://github.com/nericguyen/15L-lab7/assets/149546505/bd226aac-5485-4d12-9504-75e51717ad8d)

I typed in the terminal `<c><d><space><1><5><tab>`, which automatically fills the line with the relative path that starts with "15" if there is only one, which was **/15L-lab7-fork**.  I press `<enter>` to change the directory to **/home/linux/ieng6/cs15lwi24/ern006/15L-lab7-fork**.  To run the compiler and tester, there is a bash script already within the directory that I can run. I type `<b><a><s><h><space><t><tab>`, which like before, fills it with the only relative path that starts with t, which was **/test.sh**.  I press `<enter>` and the tests run.

## Editing the code file to fix the failing test

![image](https://github.com/nericguyen/15L-lab7/assets/149546505/767149ce-0295-4ff6-b5d3-4ebfc7657eaf)

I type in the terminal `<v><i><m><space><L><tab>`, which attempts to fill in the space for me with the path that starts with "L."  **/ListExamples.java** and **/ListExamplesTests.java** both start with L, and share the start "ListExamples," so the terminal fills it to say `vim ListExamples`.  I then typed `<.><j><a><v><a>` and then hit `<enter>`.

![image](https://github.com/nericguyen/15L-lab7/assets/149546505/20445845-b164-4147-9c74-56f5a8670930)

It takes me to the code of **/ListExamples.java** in the vim text editor.  I type `<4><3><j>`.  The j command brings the cursor down one line, and the 43 does that command 43 times, effectively bringing our cursor to line 44.  I type `<1><1><l>` to go to the end of the first word.  The l command brings my cursor to the right one character and the 11 makes it happen 11 times.  I type `<x>` to delete the "1" and then I type `<i><2>` to insert a "2."  The x command deletes the character under the cursor, and the i command changes vim into a state of inserting characters.  Typing 2 simply inserts 2 into the java file where the cursor is.  Then I hit `<esc>`.  This removes me from the state of inserting characters into the state of typing commands into vim.  I type `<:><w><q>` and then hit `<enter>` to save the changes I made in the java file and exit vim back to the terminal.

## Compiling and running the test

![image](https://github.com/nericguyen/15L-lab7/assets/149546505/bae6e0a1-ca21-4b23-8a1f-1de9059dbb71)

In the terminal, I do `<up><up>` to go back to the second to last commmand I ran in the terminal, which was `bash test.sh`.  I hit `<enter>` to run the bash script again to compile and run the tests.

## Committing and pushing the Resulting Change to Github

![image](https://github.com/nericguyen/15L-lab7/assets/149546505/01d90daa-d169-4ed2-b53d-37b5299a329d)

In the terminal, I type `<g><i><t><space><a><d><d><space><L><tab><.><j><a><v><a><enter>` and `<g><i><t><space><c><o><m><m><i><t><space><L><tab><.><j><a><v><a><enter><-><m><space>` and then typed a message of my choosing.  This stores the changes I made in the java file.

![image](https://github.com/nericguyen/15L-lab7/assets/149546505/fc886ee2-2293-437c-b1b7-4a1958c72161)

I finally type `<g><i><t><space><p><u><s><h><enter>` to sync the changes in this directory with the files in Github.

![image](https://github.com/nericguyen/15L-lab7/assets/149546505/c4396862-19a9-4203-99f2-3824cf871a16)

We can see that the file was changed on the Github website with the commit message I used earlier.

## Conclusion

Thank you for reading my speedrun, my original time was like 13 minutes but my current PB is 3 minutes.
