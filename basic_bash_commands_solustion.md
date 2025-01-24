*Exercise 1*

*Navigate to your home folder and display all of its contents along with permissions information*
bash
cd ~ 
ls -l 

*Exercise 2*

*Display the contents of the /var/log folder sorted by size (in more human-readable sizes - KB, MB, etc.) in ascending order*
bash
du -h /var/log/* | sort -h


*Exercise 3*

*Using the nano editor, write your name to the file firstname.txt*
bash
nano firstname.txt

*Exercise 4*

*using the echo command, write your last name to the file lastname.txt*
bash
echo "Garayev" > lastname.txt

*Exercise 5*

*Using the cat command, display the contents of both files*
bash
cat firstname.txt lastname.txt

*Exercise 6*

*Using the cat command, add the contents of the file lastname.txt to the file firstname.txt*
bash
cat lastname.txt >> firstname.txt

*Exercise 7*

*Write a list of folders from your home folder to the file with the name of your choice*
bash
ls -d ~/ */ > myfolder.txt
