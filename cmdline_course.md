---
layout: default
---



This course was a relatively short and compact introduction of the command line and what you can do with it. For someone who hasn't previously touched the command line, the course was rather informative. One of the more difficult things about using the command line was to remember all the different arbitrary-sounding commands and related options like `cd`, `grep -E` and so on. It turned out that you need a lot of cheat sheets at first.

### Week 1
* Week 1 was an introductory week, consisting of setting up the command line, using text editors, getting files from the web and quitting applications and some of the most basic commands like `pwd` (for printing the current working directory) and `ls` (for listing the contents of the current working directory).

### Week 2
* Week 2 was about learning how to navigate on the command line and basic file managing.
* Important commands for file managing:
  * `cd, cp, rm, mv`

### Week 3
* On week 3 we learned basic corpus tools like `tr` (translation command). Regular expressions were introduced with the `grep` command. We also made sure that the character encoding in the shell was set to UTF-8 (which was a struggle for me personally).

### Week 4
* On week 4 **the powerful sed command** was introduced

  ```Bash
  cat file1 | sed 's/Hello/Hi/g' > file2
  ```

  This piece of code will take the contents of file1, replace every ocurrence of 'Hello' with 'Hi' and direct the resulting text into file2.

### Week 5
* Week 5 was about scripting and configuration files.

![script to make comparative forms](/assets/images/script_comparative.PNG)

The picture shows a script that turns an adjective into its comparative form.

### Week 6
* Week 6 was about installing software, package managers and Makefiles. 

### Week 7
* On week 7 we learned about version control and GitHub
* Important commands:
  * git init, git clone, git add, git commit, git pull, git push