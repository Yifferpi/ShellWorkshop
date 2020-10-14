
Task 1
==========================================
List all the users on the system in alphabetical order.
Solution: cat passwd | cut -d : -f 1 | sort

Prints the number of users on the system.
Solution: cat passwd | wc -l

Task 2
==========================================
Inside the task2 folder, print all the lines from the documents that dont start with #.
Solution: 'cat * | grep -v '#''

Print the names of the 4 biggest files in the folder
Solution: - du -h * | sort -rh | cut -f 2 | head -n 5


