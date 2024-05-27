# Hip Hip Hip

<hr>

![image](https://github.com/shayol33/AfricaCyberFest24_CTF/blob/main/assets/Nulock's%20nemesis.png)

I connected to the challenge instace with the command shown and I tried Linux command on it, but it seems we cannot use linux commmands here.

![image](https://github.com/shayol33/AfricaCyberFest24_CTF/blob/main/assets/Nulock's%20Nemesis_2.png)

I tried to see if the machine is running a pyhton interpreter so i can just escape the shell, But that was’t it

![image](https://github.com/shayol33/AfricaCyberFest24_CTF/blob/main/assets/Nulock's%20Nemesis_3.png)

I tried to cause an error using wildcards

```
 A wildcard simply replaces the pattern with all files matching the pattern, separated by spaces. There are a few different characters that are wildcards, and have different functions:
        
        *: Matches any text of any length (example: *.txt matches any file ending with ".txt")
        
        ?: Matches any single character (example: ????.txt matches a 4-character .txt file)
        
        []: Match any single character in a set (example: [a-n].txt matches any single letter file in the first half of the alphabet ending with ".txt")
```
![image](https://github.com/shayol33/AfricaCyberFest24_CTF/blob/main/assets/Nulock's%20Nemesis_4.png)

I kept increasing the nuber of “?” then i got a flag

![image](https://github.com/shayol33/AfricaCyberFest24_CTF/blob/main/assets/Nulock's%20Nemesis_5.png)

```Flag: ACTF{Th4t_w4s_5impl3_wasnt_it?}```
