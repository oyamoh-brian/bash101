# bash0x101
# This is my Learning Journey of BASH
## What is Bash?

Bash is a Unix shell / Command Language Written By Brian FOX. Bash Script Files Usually have the <b>*.sh</b> extension. To become a power user, you need to have knowlegde about bash scripting language

If you do not have a Linux/Unix Image, you can use an online bash interpreter
For exam-ple, [Repl.it , an Online Bash compiler, Online Bash IDE, and online Bash,](https://repl.it/languages/bash) lets you create, run and even share your bash scripts online. Its main disadvantage is that its functionallity is basic. Anyway it is awesomee

Did you know that bash stands for <b>Bourne Again Shell? 😊</b> 

 ## Running bash scripts
 
1. ### Running in Console.
You can run bash in your console by just typing commands and hitting *RETURN* 
eg 
```bash
oyamoh-brian@localhost : ~$ echo Hello World
Hello World
oyamoh-brian@localhost : ~$
```
2. ### Running by Creating a .sh file
You can create a sh file using your prefered editor eg **vim, nano or sublime-text**
Make sure to save your file using a .sh extension
eg 
```bash
echo Hello World
```
Then to run the file in your console you will just type the path to the file name and concatenate with the filename
eg ```oyamoh-brian@localhost : ~$ ./Desktop/hello.sh```

## Permissions to run your Scripts
After creating your script file, you need to let your UNIX/LINUX system know that it is an executable file
thus you need to run the following command
```oyamoh-brian@localhost : ~$ sudo chmod u+x /path/script.sh```(replace path with the path to your file and script.sh withy your file name)
Thus you can now run your script effeciently
#### Summary on how to change permissions and run(This is a simple terminal session)
```bash
oyamoh-brian@localhost : ~$sudo chmod u+x ./Desktop/hello.sh
oyamoh-brian@localhost : ~$ ./Desktop/hello.sh
Hello World
oyamoh-brian@localhost : ~$
```
