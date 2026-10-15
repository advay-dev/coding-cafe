1. pwd printed the home directory that I was in. mine looked like /users/advayjain

2. ls -a showed some hidden files with names that began with a dot(.) that plain ls did not

3. the first column of ls -l showed the nature of the file (whether it was a regular file of a directory)

4. ls coding-cafe/week02 works because there really is a coding cafe folder with a week02 folder inside it from where youre standing. It is a relative path

5. mv performed 2 functions - it moved a file into a different folder, keeping the same name. it also renamed a file in the same folder

6. 12 folders on my path

7. /Library/Frameworks/Python.framework/Versions/3.13/bin/python3

8. It is not the same, as he is a windows user and hence has a different location for where his python3 lives

9. zsh: command not found: pyton3. the shell went through all folders on my path looking for a program with that name, found nothing, and gave up

10. .venv did not work with ls as it starts with a dot, so its hidden. ls -a reveals it

11. (.venv) appeared at the front of the prompt

12. /Users/advayjain/coding-cafe/.venv/bin/python3. this is a different path from question 7. activate put the venv bin folder at the front of my path

13. the second pip list included requests, idna, certifi, urllib3 and charset-normalizer while the first pip list did not

14. /Library/Frameworks/Python.framework/Versions/3.13/bin/python3

15. ls -h prints file sizes in units that people can read instead of raw byte counts

16. ctrl+c interrupts the program and tells it to stop what its doing. ctrl+d ends the program and exits python, taking you back to your shell
