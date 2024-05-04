SecurePass
SecurePass is a command-line tool designed to help users create and evaluate the strength of their passwords. It provides a simple interface for generating random passwords and checking their complexity.

Features
Password Generation: Easily generate strong, random passwords with the generate command.
Password Checking: Check the complexity of your passwords to ensure they meet security requirements.
Password Summary: View a summary of all passwords checked during your session.
Usage
Generate a Password: Use the generate command to create a random password.
bash
Copy code
$ python securepass.py generate
Check a Password: Use the check command followed by the password you want to check.
bash
Copy code
$ python securepass.py check <your_password_here>
View Password Summary: At any time, you can view a summary of all passwords checked during your session by typing exit.
bash
Copy code
$ python securepass.py
Installation
Clone the repository:
bash
Copy code
$ git clone https://github.com/your_username/securepass.git
Install the required dependencies:
bash
Copy code
$ pip install -r requirements.txt
Run the tool:
bash
Copy code
$ python securepass.py
Contribution
Contributions are welcome! If you have any ideas for improving SecurePass or want to report a bug, please open an issue or submit a pull request.
