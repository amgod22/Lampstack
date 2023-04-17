# Details

Rename this file in the format `yourRollNumber_solution.md` (example, `220000_solution.md`) and submit the solution in the Google form link provided 
*** https://forms.gle/RZtKpFcKfrWrYYxF9 ***


## Your zeroth approach below

Reasoning - 

Removed unlisted and changed int ved[] to char ved[] . THis was done in order to remove any pre existing errors from the code. IN order to run the code on linux terminal i had to first install gcc using the sudo apt install command.
 once done i ran the command gcc zeroth.c and then did ls in order to view all the contents of this file.
 FRom among all the contents there was a slightly different one called a.out 
 I opened it using ./a.out
 After doing this the linux terminal showed a statement which was as follows--
 The answer of this challenge is output of "man" when run on the terminal, copy the exact output

```
%%% Replace this with the 0th challenge answer %%%
```

---

## Your first approach below (first.txt)

Reasoning - First I opened the Lamp_stack-main from downloads section in my linux terminal and from it i found the contents of strings.txt using find command.After that I got a path of strings.txt

Tried using different rot types and found the code by using  rot8
```
./Lamp_Stack/Lamp_Stack/1/5/0/3/strings.txt (Answer)
```
CLASS of that INPUT
---

## Your second approach below (strings.txt)

Reasoning - To find the location of strings.txt ,we used  find . -name strings.txt  and extracted password using "cat" .when i applied the cat command on The path provided to me from first.txt , I got 7 different string file names 
kw4QLNylm2inErX
DabAWF1UenBD2W
kPVEQPc6ZN8x2jn
g4JoMqFZyat9vd5
ORNwuwGtKDLydge
TqMuGims7vlJtno
8dc2evcCSSc4kUy (password)
.THe password to the next challenge was in one of the files containing the string to the next of which (password) is written. Actually i had to find the location of all those strings. The locations were named like ELeven.txt ,fifteen.txt etc..



and found location of all the given strings by  grep -R 'stringname'
I pasted the names of all those given 7 string names in this command one by one and checked the file names as passwords  for the string which was given as password and it was contained in eleven.txt 
hence from here i found out that the password to the fourth.zip would be "eleven.txt"

```
%%% Replace this with the 2nd challenge answer %%%
```
./Lamp_Stack2/1/5/0/3/strings.txt
8dc2evcCSSc4kUy (password)

Lamp_Stack2/six.txt:kw4QLNylm2inErX
Lamp_Stack2/three.txt:DabAWF1UenBD2W
Lamp_Stack2/five.txt:ORNwuwGtKDLydge
Lamp_Stack2/one.text:ORNwuwGtKDLydge
Lamp_Stack2/seven.txt:kPVEQPc6ZN8x2jn
Lamp_Stack2/eight.txt:g4JoMqFZyat9vd5
Lamp_Stack2/ten.txt:TqMuGims7vlJtno
Lamp_Stack2/eleven.txt:8dc2evcCSSc4kUy
---

## Your third approach below (fourth.zip)

Reasoning - I unzipped the fourth.zip usinf the unzip command itself.Then i entered the password which i found in the previous challenge.

unzipped using password - eleven.txt 
after that i was given with a number of options to replace the file like yes , no , all etc.
i selected all which opened for me a directory named as get_in and I had to find the string beginning with "Devops" from among them.
```
%%% Replace this with the 3rd challenge answer %%%
```

---


- Name : Aryan Mishra
- Roll : 220225
- GitHub username: amgod22
- Discord username: aryanmi22#8315


## Do not tamper below this line

---

Q29yZSB0ZWFtIGtvIGZha2UgZG8=
