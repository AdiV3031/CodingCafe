Q1. What did pwd print?
Q2. What did ls -a show that plain ls did not?
Q3. Pick one line from ls -l. What do you think the first column means?

A1. pwd stands for "Present Working Directory", it prints the absolute file path of the current folder.
A2. ls -a stands for "list all", while ls command shows only visible files and folders, ls -a lists all including the hidden ones.
A3. ls -l stands for "list long" shows the detailed metadata of very visible file and folder in the directory. The first column shows the file type and permissions. (- means file, d means directory etc) 

"ls coding-cafe/week02"
Q4. Why does that work from where you are standing? Which kind of path is coding-cafe/week02? Absolute or Relative?

A4. Works because we are standing in the parent directory. This is a relative path.

Q5. mv did two different jobs above. What were they?

A5. First mv was used to move a file from folder to folder, second mv command was used to rename a file

Q6. How many folders are on your PATH? (They are separated by :)
Q7. Write down exactly where your python3 lives. You will need this again in a minute.
Q8. Compare your answer to 7 with the person next to you. Are they the same? If not, why might that be?

A6. 16
A7. /Library/Frameworks/Python.framework/Versions/3.14/bin/python3
A8. No they are not the same, since my system has different python installations and setups comparatively, also system prioritises different things as $PATH is unique

Q9. What exactly did the shell say? Explain the error in your own words, using the word PATH.
A9. Shell says "Pyton3 not found" means that it searched the whole path left to right, for "Pyton3" but could not find it.

Q10. venv did not appear with plain ls. Why not? (Refer back to section 1.)
A10. Because it is a hidden folder, not visisble

Q11. What changed about your prompt?
Q12. Compare this with what you wrote down for question 7. Is it the same path? If not, what does that tell you about what activate actually did to your PATH?
Q13. What is in the second list that was not in the first?
Q14. Where does python3 point now?
Q15. Find what ls -h does. Write it in your own words.
Q16. What is the difference between what Ctrl + C and Ctrl + D did?

A11. started with (.venv)
A12. Not the same path, activate makes it go in the virtual environment.
A13.certifi, charset-normalizer, idna, requests, urllib3 instead of just pip came in the second list
A14. Points back to the same path as before.
A15. ls -h makes it human readable, uses the prefixes, kilobytes, gigabytes etc etc instead of just bytes
A16. Ctrl+C gave a keyboard interrupt, while Ctrl+D actually exited the python environment, Ctrl+C is a forceful interrupt to a running process, while Ctrl+D indicates end of input and cleanly exits.
 
