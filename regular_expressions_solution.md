*Exercise 1*

*Display all resource names from your home folder whose name begins with a capital letter*
bash
ls ~/ | grep '^[A-Z]'


*Exercise 2*

*From your home folder, display all the resource names whose name begins with a '.' (period)*
bash
ls -a ~/ | grep '^\.'


*Exercise 3*

*Count all the names from task number 2*
bash
ls -a ~/ | grep -c '^\.'


*Exercise 4*

*Display all names from your home folder that contain only uppercase and lowercase letters*
bash
ls ~/ | grep '^[a-zA-Z]*$'

*Exercise 5*

*Display all the names from your home folder that do not contain uppercase letters*
bash
ls ~/ | grep -v '[A-Z]'

*Exercise 6*

*Display all names from your home folder that do not contain a 3 letter extension*
bash
ls ~/ | grep -v '\.[a-zA-Z0-9]\{3\}$'

*Exercise 7*

*In the /etc folder, find all names that start with 'c' and end with 'y'*
bash
ls /etc | grep '^c.*y$'

*Exercise 8*

*In the /etc folder, find all names that have two adjacent 's' letters*
bash
ls /etc | grep 'ss'

*Exercise 9*

*Build an expression that will select names that contain a six-letter string of characters, of which the first, third and fifth character can be any character, the second and fourth must be an uppercase letter, the sixth must be an e.*
bash
ls ~/ | grep '^.\{0,5\}[A-Z][a-zA-Z].[A-Z].[a-zA-Z]e'

*Exercise 10*

*From your home folder, display all names that are exactly 4 characters in length. Those names should contain only lowercase and uppercase letters and numbers.*
bash
ls ~/ | grep '^[a-zA-Z0-9]\{4\}$'

*Exercise 11*

*From the /var/log folder, display all names that have the extension 'log'*
bash
ls /var/log | grep '\.log$'
