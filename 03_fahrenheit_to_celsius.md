Problem Statement
Write a program which prompts the user for a temperature in Fahrenheit (this can be a number with decimal places!) and outputs the temperature converted to Celsius.

The Celsius scale is widely used to measure temperature, but places still use Fahrenheit. Fahrenheit is another unit for temperature, but the scale is different from Celsius -- for example, 0 degrees Celsius is 32 degrees Fahrenheit!

The equation you should use for converting from Fahrenheit to Celsius is the following:

degrees_celsius = (degrees_fahrenheit - 32) * 5.0/9.0

(Note. The .0 after the 5 and 9 matters in the line above!!!)

Here's a sample run of the program (user input is in bold italics):

Enter temperature in Fahrenheit: 76

Temperature: 76.0F = 24.444444444444443C


def main():
    print("Delete this line and write your code here! :)")


# This provided line is required at the end of
# Python file to call the main() function.
if __name__ == '__main__':
    main()




    def main():
    # User se Fahrenheit mein temperature input lena
    degrees_fahrenheit = float(input("Enter temperature in Fahrenheit: "))

    # Fahrenheit se Celsius mein convert karna
    degrees_celsius = (degrees_fahrenheit - 32) * 5.0 / 9.0

    # Result print karna
    print(f"Temperature: {degrees_fahrenheit}F = {degrees_celsius}C")


# Ye line main() function ko call karti hai jab file run hoti hai
if __name__ == '__main__':
    main()
