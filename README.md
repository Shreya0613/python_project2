def convert_units():
    print("Unit Converter")
    print("1. Meters to Kilometers")
    print("2. Kilometers to Meters")
    print("3. Inches to Feet")
    print("4. Feet to Inches")
    print("5. Grams to Kilograms")
    print("6. Kilograms to Grams")
    print("7. Kilograms to Pounds")
    print("8. Pounds to Kilograms")

    choice = int(input("Enter your choice (1-8): "))
    value = float(input("Enter the value to convert: "))

    if choice == 1:
        print(f"{value} meters = {value / 1000} kilometers")
    elif choice == 2:
        print(f"{value} kilometers = {value * 1000} meters")
    elif choice == 3:
        print(f"{value} inches = {value / 12} feet")
    elif choice == 4:
        print(f"{value} feet = {value * 12} inches")
    elif choice == 5:
        print(f"{value} grams = {value / 1000} kilograms")
    elif choice == 6:
        print(f"{value} kilograms = {value * 1000} grams")
    elif choice == 7:
        print(f"{value} kilograms = {value * 2.20462} pounds")
    elif choice == 8:
        print(f"{value} pounds = {value / 2.20462} kilograms")
    else:
        print("Invalid choice.")

# Run the converter
convert_units()
