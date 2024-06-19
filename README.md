# Password Generator

This script generates passwords based on user input, such as the victim's name, parent's names, pet's name, birth city, and date of birth. The script can create passwords of varying lengths and complexities using the `crunch` tool.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Dependencies](#dependencies)

## Installation

1. Clone the repository:
   ```bash
   git clone git@github.com:Jevaa-kharthik/Password_Generator

2. Navigate to the Directory:
   ```bash
   cd Password_Generator

## Usage

1. Check the Script is Executable if not, use this command:
   ```bash
   chmod +x password_generator.sh

2. Run the Script
   ```bash
   ./password_generator.sh

3. Follow the On-Screen Prompt's:
   - Victim's Name
   - Vistim's Father Name
   - Victim's Mother Name
   - Victim's Pet Name
   - Victim's Birth City
   - Victim's Date of Birth
   - Extra Information About the Victim's

4. Choose How to Generate the Password:
   - Multiple Length
   - Single Length with Additional Information

5. For Multiple Length, specify the minimum and maximum length for the password.

6. For Same Length, specify the number of words, numbers, and symbols for the password pattern.

## Features 

  - Remove Repeated Characters: The script removes repeated characters from the combined input.
  - Multiple Length Passwords: Generate passwords of varying lengths.
  - Fixed Length Passwords: Generate passwords with a specific pattern of words, numbers, and symbols.
  - File Handling: Output is saved to a specified .txt file.
  - File is saved only in .txt Extension

## Dependencies 
  
  ##### crunch tool: Make sure the crunch tool is installed on your system.
  
  - If you are using Linux Environment : 
    
    ```bash
    sudo apt install crunch
    ```
    
- If you are using MacOS Environment :

  ```bash
  brew install crunch
  ```



