import re

 #Function to validate license plate
def validate_license_plate(plate):
    pattern = r'^[A-Z]{2}[0-9]{2}[A-Z]{2}[0-9]{4}$'
    if re.match(pattern, plate):
        return "Valid License Plate"
    else:
        return "Invalid License Plate"

# User input
license_plate = input("Enter the license plate: ").upper()
print(validate_license_plate(license_plate))
