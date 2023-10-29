# Constants
USERNAME = "user1"
PASSWORD = "password1"

# Ask for user input
user_name = input("What is your user name? ")
password = input("What is your password? ")

# Check if the entered credentials are correct
if user_name == USERNAME and password == PASSWORD:
    age = int(input("What is your age? "))
    if age >= 18:
        print("You're considered an adult")
    else:
        print("You're not considered an adult")
else:
    print("Your credentials are not valid")

