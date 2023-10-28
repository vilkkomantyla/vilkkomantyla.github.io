---
layout: default
---

## Overview

The Command-Line Tools -course covers the basics of using the command 
line. The main topics of the course include processing text files with 
command line tools, connecting to remote servers, installing and running 
programs and using version control tools. Scripts and regular expressions 
are also covered.

The course offers tools which can be handy in any kind of work done with 
the computer. Knowing the architecture of the command line and being able 
to navigate in it expands the possibilities of utilizing the computer in 
ones work.

 
| Week1           | Week 2         | Week 3             | Week 4    | Week 5                | Week 6              | Week 7          |
| --------------- | -------------- | ------------------ | --------- | --------------------- | ------------------- | --------------- |
| basic commands  | directories    | corpus processing  | sed       | scripts               | root                | version control |
| nano            | processes      | regular exressions | pipelines | environment variables | installing software | final project   |
|                 | remote servers |                    | n-grams   | configuration files   | make                |                 |


### Week 1

The course started with the basic commands necessary for using the command 
line (ls, pwd, wget, mv, cp, rm etc.). It also provided a tutorial for 
using the nano text editor and gave insight to different file formats.

I was already familiar with the basic commands and nano from my studies in 
computer science, but it was a good recap.

% wget https://moodle.helsinki.fi/mod/assign/view.php?id=3253582

% Download a web page with wget

### Week 2

On the second week of the course I learned to process entire 
directories with the flag -R. The concept of root directory and special 
directories such as /bin and /usr were covered. I also learned how 
to monitor and kill processes and use remote servers.

% cp -r ~/some_directory/ .

% Copy the contents of some_directory to the current working directory

### Week 3

The third week of the course concentrated on corpus processing. Converting 
between different text encodings and commands for generating word lists 
(tr, sort, uniq) were central topics. A part of the week was dedicated to 
regular expressions which are useful in corpus processing.

I learned to use tr which I found really useful.

% cat document.txt (pipeline) tr [:lower:] [:upper:]

% Print the contents of document.txt in uppercase.

### Week 4

Week 4 expanded the corpus processing concept with sed and all its flags. 
After the week I was able to use pipelines for 
effectively processing corpora. Pipeline techniques are essential in 
forming the document into sentence per line format or generating word 
frequency lists. Week 4 also gave introduction to n-grams and their 
possible usages.

I learned to wrap my head around pipeline techniques. They are often quite 
long and complex but also really powerful, so it was nice to learn how to 
use them.

% sed -E 's/I/you/g' document.txt > you_document.txt

% Sed command for replacing every instance of the word "I" with the word 
"you" in document.txt and redirecting the output to new document 
you_document.txt.

### Week 5

The fifth week combined the commands learned in the previous weeks for 
scripting. I learned to write own scripts for different tasks. 
Additionally, it was crucial to grasp the idea of environment variables to 
be able to use scripts efficiently. Configuration files were 
also introduced.

Scripts were really cool to uncover this week, since you can do so much 
with them.

% chmod u+x script.sh

% Give user rigths to execute the script, which is necessary for running 
them

### Week 6

Week 6 started with explaining the root user concept, which is important 
for instance in installing software and packages. Programs and libraries 
are often dependant on other resources, so dependencies were covered. This 
week also introduced make and teaches how to write them.

Make was a new concept to me, so it was nice to familiarize myself with 
it.

### Week 7

The final week of the course was about version control. An introduction to 
Git and GitHub was given in detail. The main focus of the final week was 
the final assignment, where the I needed to create a webpage using GitHub 
Pages, namely this page. 

I got to reflect on what I had learned and use the knowledge in practice 
in creating the webpage.

% git pull

% Fetch latest changes made to a github repository
