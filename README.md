# Termux-Display-Name
This setup customizes the Termux prompt to show a  name before the `$` sign.  
It personalizes the terminal by displaying your chosen team name at the start of every command line.  
 

## Features  
- Look like Pro
- No Error 

## Installation  
just copy and paste

# 1st Look  
    ```bash
   nano ~/.bashrc
   PS1='\[\e[1;34m\]┌──(\[\e[1;31m\]ROOT\[\e[1;37m\]VOID\[\e[1;34m\]㉿\[\e[1;36m\]TERMUX\[\e[1;34m\])-[\[\e[1;33m\]\w\[\e[1;34m\]]\n\[\e[1;34m\]└─\[\e[1;36m\] € \[\e[0m\]'
    ```


![WhatsApp Image 2025-08-24 at 01 01 24_af6329c8](https://github.com/user-attachments/assets/7a19fb63-c599-43ea-9c79-219692e39f8e)

   
# 2nd Look
    ```bash
   nano ~/.bashrc
   PS1='\[\e[1;33m\]ROOTVOID\[\e[1;34m\][\[\e[1;36m\]\w\[\e[1;34m\]]\[\e[0;32m\]:\[\e[1;31m\]# \[\e[0m\]'
    ```

   ![WhatsApp Image 2025-08-24 at 01 01 23_50ee4181](https://github.com/user-attachments/assets/24dde9b0-d13f-4e79-94d8-b84320c761e3)

##Full ANSI color reference (basic set).
 ```bash
 Code	               Color

\e[0m	               Reset / Default
\e[30m             	 Black
\e[31m	             Red
\e[32m	             Green
\e[33m	             Yellow
\e[34m 	             Blue
\e[35m	             Magenta
\e[36m	             Cyan
\e[37m	             White / Light Gray
```
##Bright versions (bold or high-intensity)
 ```bash
Code	              Color

\e[1;30m	          Bright Black / Gray
\e[1;31m	          Bright Red
\e[1;32m	          Bright Green
\e[1;33m	          Bright Yellow
\e[1;34m	          Bright Blue
\e[1;35m	          Bright Magenta
\e[1;36m	          Bright Cyan
\e[1;37m	          Bright White
```

##Other useful styles:
 ```bash
Code	             Effect
\e[1m	             Bold / Bright
\e[4m	             Underline
\e[7m	             Reverse (swap FG/BG)
\e[0m	             Reset all
```
Enjoy and becone a pro.
