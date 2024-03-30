# whether
def check_voting_age(age):
    if age >= 18:
        print("You are old enough to vote!")
    else:
        print("You are not old enough to vote yet.")

def main():
    try:
        age = int(input("Please enter your age: "))
        check_voting_age(age)
    except ValueError:
        print("Invalid input. Please enter a valid age.")

if __name__ == "__main__":
    main()
