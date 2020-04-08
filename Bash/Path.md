Had an issue regarding installing pip, virtualenv, or any form of python related modules/packages

the problem was, Bash wont recognize it

its because of some debian flaw where: anything in ~/.local/bin wont be found by the bash
or in other words there were no path going to that directory
so you either move your crap or add a path 

what i did i just added a path
and these links helped me out:

- https://unix.stackexchange.com/questions/26047/how-to-correctly-add-a-path-to-path
- https://unix.stackexchange.com/questions/25605/how-to-add-home-directory-path-to-be-discovered-by-unix-which-command
- https://unix.stackexchange.com/questions/40750/remove-duplicate-path-entries-with-awk-command

it took me around 1 hour to understand the situation, but i learned new stuff, so its a win win.