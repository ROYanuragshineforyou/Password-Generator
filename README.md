# Password-Generator
Generates Password for the user.

Import Modules:

string: Provides constants for ASCII letters and punctuation.
random: Offers functions for generating random numbers and making random selections.
User Input:

password_len: User is prompted to enter the desired password length.
Character Sets:

s1, s2, s3, s4: Sets of lowercase letters, uppercase letters, digits, and punctuation, respectively.
Combined into a list s.
Password Generation:

random.sample(s, password_len): Randomly selects unique characters from the combined list s.
Characters are joined into a string.
Output:

The generated password is printed to the console.
