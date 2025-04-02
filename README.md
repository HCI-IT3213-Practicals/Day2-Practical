# Day 02 Practical Sessions - Calculator App Development 🔢

Welcome to the Calculator App Project repository! This project showcases the step-by-step development of a fully functional calculator app using Axure RP 9. Each week, new features and interactions will be added to gradually build the app until it is fully functional.
## 🚀 Project Overview

The goal of this project is to develop a fully functional calculator app with an intuitive, user-friendly interface and interactive features. We are using Axure RP 9 to design the interface and define interactions. This repository will be updated to reflect the latest progress in the development process.

## 🔧 Features Implemented in Day 02

### Basic Calculator Interface:
- A simple calculator layout was created with a screen and a number pad (0-9).
- Buttons for numbers (0-9) were added, and basic operations will be implemented in future sessions.

### Number Pad Interactions:
- Interactions were created to update the calculator screen when a number is clicked.
- **Two Variables** were introduced:
  - **Flag**: Used to determine whether the input should replace the existing value or append to it.
  - **Saved Number**: Used to store the current input value.

### Initial Variable Setup:
- On page load, the following initial setups are done:
  - **Flag** is set to "Replace".
  - **Saved Number** is set to an empty string (`""`).

### Interaction Logic for Numbers (1-9):
- **If Flag equals "Replace"**:
  - Set the calculator screen text to the clicked number.
  - Set **Flag** to "Join".
  
- **If Flag equals "Join"**:
  - Set the calculator screen text to append the clicked number to the existing value.

### Interaction Logic for Number 0:
- **If Flag equals "Replace"**:
  - Set the calculator screen text to "0".
  
- **If Flag equals "Join"**:
  - Set the calculator screen text to append the number "0" to the existing value.

## 📸 Screenshots

Below are screenshots of the current progress of the app:

- **Calculator Interface**:  

![Screenshot](https://github.com/user-attachments/assets/99dfc918-6b67-447e-8a0a-b8b713130139)


## 📂 How to Use the Axure RP 9 File

1. Download and install **Axure RP 9** if you haven’t already.
   - [Download Axure RP 9](https://www.axure.com/)
   
2. Open the `.rp` file provided in this repository.

3. Use the **Page Navigator** in Axure RP 9 to navigate through the pages.

4. To preview the prototype, click the **Preview** button to see the interactions in action.

## 📜 License

This project is licensed under the **MIT License**. See the LICENSE file for details.
