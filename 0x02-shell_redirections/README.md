0. Hello World => Write a script that prints “Hello, World”, followed by a new line to the standard output.
==> echo "Hello, World"

1. Confused smiley => Write a script that displays a confused smiley "(Ôo)'.
==> echo "\"(Ôo)'"

2. Let's display a file => Display the content of the /etc/passwd file.
==> cat /etc/passwd

3. What about 2? => Display the content of /etc/passwd and /etc/hosts
==> cat /etc/passwd /etc/hosts

4. Last lines of a file => Display the last 10 lines of /etc/passwd
==> cat | tail -n 10 /etc/passwd 
==> tail /etc/passwd

5. I'd prefer the first ones actually => Display the first 10 lines of /etc/passwd
==> head /etc/passwd

6. Line #2 => Write a script that displays the third line of the file iacta. The file iacta will be in the working directory. You’re not allowed to use sed
==> head -n 3 iacta | tail -n 1 

7. It is a good file that cuts iron without making a noise => Write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
==> echo "Best School" > \\\*\\\\\'\"Best\ School\"\\\'\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\)

8. Save current state of directory => Write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
==> ls -la > ls_cwd_content

9. Duplicate last line => Write a script that duplicates the last line of the file iacta - The file iacta will be in the working directory
==> tail -n 1 < iacta >> iacta

10. No more javascript => Write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
==> find . -type f -name '*.js' -delete   
