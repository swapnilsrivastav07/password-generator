# password-generator
The program is a password generator implemented in bash scripting. It defines a function called generate_password that takes a desired password length as input.

Inside the function, a character set containing lowercase letters, uppercase letters, numbers, and special characters is defined. The function uses /dev/urandom as a source of random data and filters out any characters not present in the defined character set. It then selects the desired password length from the filtered characters using head -c "${length}".

The generated password is stored in a variable and displayed on the terminal using echo.

By calling the generate_password function with a desired length, you can easily generate and obtain a random password.
