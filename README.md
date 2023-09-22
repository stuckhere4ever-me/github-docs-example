# Writing Good Documentation

## Step 1 - Using Codeblocks
Codeblocks in markdown let us share code
A good cloud engineer uses codeblocks whenever possible because it *allows* others to copy / paste code to replicate and **research**

- In order to do a code block we need to use three (3) backticks (`)
- This is not to be confused with a tilda (~)

```
# Get user input as a string
user_input = input("Enter a number: ")

# Convert the user input to a float (for handling decimal numbers)
try:
    number = float(user_input)
except ValueError:
    print("Invalid input. Please enter a valid number.")
else:
    # Add 5 to the number
    result = number + 5

    # Print the result after adding 5
    print(f"After adding 5, the result is: {result}")

    # Multiply the result by 10
    final_result = result * 10

    # Print the final result
    print(f"Final result after multiplying by 10: {final_result}")
```

- When you can you should attempt to apply syntax highlighting to your code

```python
# Get user input as a string
user_input = input("Enter a number: ")

# Convert the user input to a float (for handling decimal numbers)
try:
    number = float(user_input)
except ValueError:
    print("Invalid input. Please enter a valid number.")
else:
    # Add 5 to the number
    result = number + 5

    # Print the result after adding 5
    print(f"After adding 5, the result is: {result}")

    # Multiply the result by 10
    final_result = result * 10

    # Print the final result
    print(f"Final result after multiplying by 10: {final_result}")
```

We can use the (! [] ()) syntax to display an image but it is not possible to resize it
![twin kitties!](https://github.com/stuckhere4ever-me/github-docs-example/assets/79291937/4b812614-34ce-44ac-a953-a8233c601903)

Or we can use html and use (img width= src=)

<img width=500px src="https://github.com/stuckhere4ever-me/github-docs-example/assets/79291937/4b812614-34ce-44ac-a953-a8233c601903" />


> Good Cloud Engineers will use codeblocks for both code and errors.  Here is an example of an error.

```bash
Traceback (most recent call last):
    1: from your_script.rb:2:in `<main>'
your_script.rb:2:in `<main>': undefined local variable or method `undefined_variable' for main:Object (NameError)
```

## Step 3 


## Refrences
- [Basic Wrting and Formating(Github flavored markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)<sup>[1]</sup>
- [Github Docs](https://docs.github.com/en)<sup>[2]</sup>
