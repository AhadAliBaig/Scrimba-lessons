
# Intro to CLI

1. pwd gives us - print working directory
2. ls - lists , lists the content
3. cd - change directory
4. clear - clears the terminal

# Rules of navigation

1. cd .. - means go back
2. cd ../whereyouwannago 
3. cd ../.. , 2 steps back

# Creating new files and deleting files
1. create: touch etc.txt
2. delete: rm etc.txt
3. touch ../directories/etc.txt changing something anywhere from a different directory
4. ls .. , lists from parent directory

# Creating and deleting directories 
1. mkdir specify
2. redir specify - can't delete if has information in there already
3. rm -r directory , recursive delete

# write and read files

1. echo - prints what we gave it in the '' after echo
2. echo 'what needs to be inputed in our file' > hello.txt
3. above more or less it rewrites the exsiting file, we use >> , this means appends rather than rewriting
4. 

# Read from files
1. cat hello.txt - read 
2. cat .txt > another.txt , rewrites the content from .txt to another.txt, can use >> to append
3. nicerrr 


# Terminology crash course
## Linux, shell and command line

<p>
<ul>
    <li>what are options?</li>
    <li>short and long options, -r vs --recursive</li>
</ul>

<ul>
    <li>Find basics</li>
    <li>Syntax: find [path] [option] [expression]</li>
</ul>
</p>

   -name 'forest*', find by name that starts with forest
    -iname, case insensitive
1. search by type f or type d, -type f / -type d
    
1. . current dir, .. parent, ~ home, / root
2. ../forests, relative
3.  

### killing a terminal
1. ctrl + c

### rename
1. mv [old_name] [new_name]
2. same for files and dir

### move
1. mv [old_name] [new_location]

### copy
1. cp [old_name] [copy_name]
2. for dir cp -r cities_dir [copy_name]

### Search
1. grep [pattern] [file/s]
2. for files as in withing text withing files whereas find for files

### Replace
1. sed 's/pattern/replacement/' [filename]
2. sed 's/whattobereplaced/withwhattobereplaced/' [file]

### Count
1. syntax: wc [filename]
2. x y z filename, lines words bytes
3. wc -l
4. wc -w
5. wc -c bytes
6. wc -m characters
7. why?

### Sort file content
1. sort [filename]
   1. a to z
2. sort [option] [filename]
   1. for z to a: -r
   2. -n for numbers
3. removing duplicates
   1. uniq [filename]
4.  

### pip character
syntax cmd1 | cmd2

sort names.txt | uniq

1. just printed not saved, just use > or >> to redirect it to the file