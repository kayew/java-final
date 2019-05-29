<div align="center">
    <h1> YAPG </h1>
    <h5>Yet Another Password Generator</h5>
    <h6><i>A password generator that barely (no one) will use</i></h6>
</div>

## Made by
* Borjan Palankov
* Sebastian Alejandro

## Our Idea:
Create a password generator that can make simple and complex passwords

## Goals:
- [ ] Get user input to ask how many characters in their password, what type of password, and the number of passwords.
    - [ ] How many characters? (default 12 if complex, 4 words if simple)
    - [ ] Type of password? 
    - [ ] Number of passwords? (default 1)
- [ ] Generate Simple passwords 
    - [ ] Use an array with random words, and select them using a random number
- [ ] Generate complex passwords
    - [ ] Use substrings to choose randomly from `CHARS`,`SPECIAL_CHARS` and `NUMBERS`.
    - [ ] Concatonate these random characters together to make a password.
