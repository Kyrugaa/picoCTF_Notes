# picoCTF_Notes 2022


## TASK 1: Obedient Cat | 5 points


### Description

#### This file has a flag in plain sight (aka "in-the-clear"). Download flag.



### Hints: 

#### 1: Any hints about entering a command into the Terminal (such as the next one), will start with a '$'... everything after the dollar sign will be typed (or copy and pasted) into your Terminal.

#### 2: To get the file accessible in your shell, enter the following in the Terminal prompt: $ wget https://mercury.picoctf.net/static/a5683698ac318b47bd060cb786859f23/flag

#### 3: $ man cat


### Process:
#### 1: mkdir obedient_cat
#### 2: $ wget https://mercury.picoctf.net/static/a5683698ac318b47bd060cb786859f23/flag
#### 3: cat flag
#### 4: picoCTF{s4n1ty_v3r1f13d_4a2b35fd}


## TASK 2: Mod 26 | 10 points


### Description

#### Cryptography can be easy, do you know what ROT13 is? cvpbPGS{arkg_gvzr_V'yy_gel_2_ebhaqf_bs_ebg13_uJdSftmh}



### Hints:

#### 1: This can be solved online if you don't want to do it by hand!



### Process:
#### 1: Copy cvpbPGS{arkg_gvzr_V'yy_gel_2_ebhaqf_bs_ebg13_uJdSftmh}
#### 2: Converted it on https://codebeautify.org/rot13-to-text-converter
#### 3: picoCTF{next_time_I'll_try_2_rounds_of_rot13_hWqFsgzu}



## TASK 3: Python Wrangling | 10 points


### Description


#### Python scripts are invoked kind of like programs in the Terminal... Can you run this Python script using this password to get the flag?


### Hints:

#### 1: Get the Python script accessible in your shell by entering the following command in the Terminal prompt: $ wget https://mercury.picoctf.net/static/2ac2139344d2e734d5d638ac928f1a8d/ende.py

#### 2: $ man python


### Process:
#### 1: mkdir python_wrangling
#### 2: wget https://mercury.picoctf.net/static/2ac2139344d2e734d5d638ac928f1a8d/ende.py
#### 3: pw.txt and flag.txt.en download in python_wrangling Directory.
#### 4: python3 ende.py -d flag.txt.en
#### 5: Please enter the password: 68f88f9368f88f9368f88f9368f88f93
#### 6: picoCTF{4p0110_1n_7h3_h0us3_68f88f93}


## TASK 4 Wave a flag | 10 points


### Description


#### Can you invoke help flags for a tool or binary? This program has extraordinarily helpful information...

### Hints 

#### 1: This program will only work in the webshell or another Linux computer.
#### 2: To get the file accessible in your shell, enter the following in the Terminal prompt: $ wget              https://mercury.picoctf.net/static/fc1d77192c544314efece5dd309092e3/warm
#### 3: Run this program by entering the following in the Terminal prompt: $ ./warm, but you'll first have to make  it executable with $ chmod +x warm

#### 4: -h and --help are the most common arguments to give to programs to get more information from them!
#### 5: Not every program implements help features like -h and --help.

