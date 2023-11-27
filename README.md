# PasswordGen

Deploy Link: https://laurabacon.github.io/PasswordGen/

This site is a password generator. When the page is loaded you are presented with an empyt box and a button that says 'generate password'.
Upon clicking the button you are met with a series of confirms and prompts. After inputting how long and what kind of characters you would like to be included in this password, you will recieve a randomly generated password. 

Upon Deploying:
![Alt text](<Screen Shot 2023-11-27 at 3.09.49 PM 2.png>)

After password is generated:
![Alt text](<Screen Shot 2023-11-27 at 3.05.04 PM 2.png>)


GIVEN I need a new, secure password
WHEN I click the button to generate a password
THEN I am presented with a series of prompts for password criteria
WHEN prompted for password criteria
THEN I select which criteria to include in the password
WHEN prompted for the length of the password
THEN I choose a length of at least 8 characters and no more than 128 characters
WHEN asked for character types to include in the password
THEN I confirm whether or not to include lowercase, uppercase, numeric, and/or special characters
WHEN I answer each prompt
THEN my input should be validated and at least one character type should be selected
WHEN all prompts are answered
THEN a password is generated that matches the selected criteria
WHEN the password is generated
THEN the password is either displayed in an alert or written to the page


