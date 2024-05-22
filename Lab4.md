<b>Lab Report 4 <br></b>
<b>Step 1 <br></b>
Log into ieng6 <br>
Keys pressed: `ssh kkatragadda@ieng6.ucsd.edu` + [enter]<br>
![Image](LB-RP-4-1.png)<br>
<b>Step 2 <br></b>
Clone your fork of the repository from your Github account (using the SSH URL)<br>
Keys pressed: `git clone git@github.com:Flareboltex/lab7.git` + [enter]<br>
![Image](LB-RP-4-2.png)<br>
<b>Step 3 <br></b>
Run the tests, demonstrating that they fail<br>
Keys pressed: `cd lab7` + [enter] + `bash test.sh` + [enter]<br>
![Image](LB-RP-4-3.png)<br>
<b>Step 4 <br></b>
Edit the code file to fix the failing test<br>
Keys pressed: `vim ListExamples.java` + [enter] + [left] + [x] + [i] + [2] + [esc] + [shift] + [:] + [w] + [q]
![Image](LB-RP-4-4.png)<br>
<b>Step 5 <br></b>
Run the tests, demonstrating that they now succeed<br>
Keys pressed: [up] + [up] + [enter] 
![Image](LB-RP-4-5.png)<br>
<b>Step 6 <br></b>
Commit and push the resulting change to your Github account (you can pick any commit message!)<br>
Keys pressed: `git add .` + [enter] + `git commit -m "Fixed error"` + [enter] + `git push origin main` + [enter] 
![Image](LB-RP-4-6.png)<br>
