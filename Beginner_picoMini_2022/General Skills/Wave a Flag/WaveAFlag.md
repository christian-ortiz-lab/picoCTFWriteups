# PicoCTF 2021 
# Wave a flag
### Description
    Can you invoke help flags for a tool or binary? This program has extraordinary helpful information...
### CTF Information
    Value: 10
    Category: General Skills
    Author: Syreal
### Challenge Hints
    1. This program will onlu work in the weshell or another Linux computer.

    2. To get the file accessible in your shell, enter the following in the Terminal prompt: $ wget https://mercury.picoctf.net/static/b28b6021d6040b086c2226ebeb913bc2/warm

    3. Run this program by entering the following in the Terminal prompt: $ ./warm, but you'll first have to make it executable with $ chmod +x warm

    4. -h and --help are the most common arguments to give to programs to get more information from them!

    5. Not every program implements help features like -h and --help.

### Flag Solution

1. ```$ wget https://mercury.picoctf.net/static/b28b6021d6040b086c2226ebeb913bc2/warm```

2. ```Waveaflag$ ./warm  ```

3. ``` zsh: persmission denied: ./warm ```

4. ```$ chmod +x warm ```

5. ```$ ./warm ```

6. ```Output: Hello user! Pass me a -h to learn what I can do! ```

7. ```$ ./warm help ```

8. ``` Output:  Oh, help? I actually don't do much, but I do have this flag here: picoCTF{b1scu1ts_4nd_gr4vy_d6969390}```
### Flag
```picoCTF{b1scu1ts_4nd_gr4vy_d6969390}``` 
