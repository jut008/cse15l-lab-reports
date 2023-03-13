# Lab Report 4
## Speed Running
Just for self-note, this lab report will be on how to effectively and efficiently complete tasks. For this lab we were given specific tasks to comlete so I'm going to give a run down on the method or my approach on how to complete the tasks in a timely manner.

Below are the given tasks for this lab.
1. Log into ieng6
2. Clone your fork of the repository from your Github account
3. Run the tests, demonstrating that they fail
4. Edit the code file to fix the failing test
5. Run the tests, demonstrating that they now succeed
6. Commit and push the resulting change to your Github account (you can pick any commit message!)

From now on I'm going to initally write how I exactly completed my steps including the commands and shortcut keys I use, then include any commentary if necessary.

**Step 1**
```
ssh cs15lwi23aqs@ieng.ucsd.edu
```

**Step 2**
```
git clone <cmd-v>
```
So 'cmd-v' is my copy and paste because I'm on mac, but what was copied and pasted was the forked repository which was 'git@github.com:jut008/lab7.git' which was provided from and by the github page.

**Step 3**
```
cd l<tab> 
<cmd-v> (javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java) 
<cmd-v> (java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests)
```

I used the first portion in () for the copy and paste, then copied and pasted the second portion right after which were both from the CSE15L website.

**Step 4**
```
nano L<tab>.j<tab>
3 x <ctr-w> <cmd-v>
6 x <left-arrow>
<delete> 2
<ctr-o> <return>
<ctr-x>
```

For this step I repeated several commands and for the copy and paste I copied and pasted 'index1 += 1;'.
  
**Step 5**
```
javac L<tab>.j<tab>
2x <up-arrow>
```
The up arrows will get me to the 'java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests' command in my command history.

**Step 6**
```
git add L<tab>.j<tab>
git commit -m "1 update"
```
### Screenshots of the approach
![Image](Lab4SpeedRun(1).png)
![Image](Lab4SpeedRun(2).png)

