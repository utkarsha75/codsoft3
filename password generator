import random
import string

def generate_password(length):
    characters = string.ascii_letters + string.digits + string.punctuation
    password = ''.join(random.choice(characters) for _ in range(length))
    return password

def main():
    print("Welcome to the Password Generator App!")
    while True:
        try:
            length = int(input("Please enter the desired length of the password: "))
            if length <= 0:
                raise ValueError("Length must be a positive integer.")
            break
        except ValueError as e:
            print("Invalid input. Please enter a positive integer for the length.")

    password = generate_password(length)
    print("\nGenerated Password:", password)

if __name__ == "__main__":
    main()
