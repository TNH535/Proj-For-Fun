# Brute Force Login Simulation

## Overview
This project is a **Brute Force Login Simulation** designed to demonstrate the security risks of weak passwords by attempting to brute-force a user-provided password using a predefined character set.

## Features
- Simple **Login Form** with Username & Password fields.
- **Toggle Password Visibility** with an eye icon.
- **Brute Force Attack Simulation** on the entered password.
- **Progress Bar** to visualize the brute-force process.
- **Time Analysis** to measure how long it takes to crack the password.

## Technologies Used
- **HTML, CSS** (Frontend design & styling)
- **JavaScript** (Brute-force logic & event handling)

## How It Works
1. User enters a **username** and **password**.
2. Clicks the **Login** button.
3. The script **attempts to brute-force** the password by trying every possible combination (up to 6 characters long).
4. If the password is found, it displays the cracked password and time taken.
5. If it exceeds the character limit, it notifies that the password was not found.

## Installation & Setup
1. Clone only the `BruteForceSim` directory from the repository using Sparse Checkout:
   ```sh
   git clone --no-checkout https://github.com/TNH535/Proj-For-Fun.git
   cd Proj-For-Fun
   git sparse-checkout init --cone
   git sparse-checkout set BruteForceSim
   git checkout main
   ```
2. Navigate to the `BruteForceSim` folder.
3. Open the `index.html` file in a browser.
4. Alternatively, use **Live Server** in VS Code to run the project.

## License
This project is licensed under the **MIT License** – free to use for educational purposes.

## Disclaimer
This project is for **educational purposes only**. Do not use this knowledge for unauthorized access or malicious activities.

## Author
- **TNH535**
- GitHub: [TNH535](https://github.com/TNH535)

