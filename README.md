# Free_time_projects is a group of small projects that I have worked on in my free time, many of them have halped me learn more about python.

First is the Number Detector, I thought it would be too short, but I ended up learning a lot from it and spending a good amount of time, this is the first
program I have made independently. it taught me how to use: input, isspace,. lower() .upper(), .replace(), complex, except, try, isdigit(), and isalnum();
I truly did enjoy coding this and having people try it out, i put in multiple special instances and made it work with any number even if it had spaces or letters
such as one that made me realize my code was flawed is it "8 or 9 I guess" what I had done what I had done was use isalnum.() and put some of my variable within a if
meaning that it would skip over some of my filters and output that there was not a number with "8 or 9 i guess"

The first big mistake I made was using Int only covering basic numbers I then realized people could use imaginary numbers (mainly for electrical engineering
in electrical engineering they use things like 3j rather then 3i due to I standing for electric current I had to figure out complex number checks in the math
before realizing people may use "the number ___" in the input, leading me to make a long list of filters removing all upper case with .lower(), removing all hyphens with
.replace() and finally removing all letters + free space. 
