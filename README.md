Weather Modeling Using Python
📌 Description
This project demonstrates a simple weather (temperature) modeling program using Python.
The temperature is calculated using a quadratic equation based on time and coefficients:
Temperature=a×time2+b×time+c
The program shows three different ways to provide input:
Hard-coded values
Keyboard input
File input

🛠️ Features
Uses a Python function for temperature calculation
Demonstrates user input handling
Demonstrates file handling
Compatible with Google Colab

📂 Files Used
weather_data.txt
Contains coefficients and time values used for file-based input.

🧮 Function Used
def temperature_modeling(a, b, c, time):
    return a * time**2 + b * time + c

▶️ How the Program Works
1️⃣ Hard-Coded Input
Coefficients (a, b, c) and time are predefined in the code
Temperature is calculated and displayed

2️⃣ Keyboard Input
User enters coefficients and time during execution
Temperature is calculated based on user input

3️⃣ File Input
Coefficients and time are read from weather_data.txt
Temperature is calculated using file data
