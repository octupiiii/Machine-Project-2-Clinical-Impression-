# Machine-Project-2-Clinical-Impression-
This project is a Intelligent Clinical Impression System is designed to aid doctors in generating clinical impressions based on patient symptoms.

# Project Structure
### Source Code
- All source code files should have a `.c` extension.
- Header files are optional but should have descriptive filenames if custom modules are created.

### Documentation
- Include inline comments throughout your code.
- Each source code file should begin with a header comment explaining the file's purpose.

### Test Script
- Create a table format for test cases categorized by function.

### Sample Files
- Include text files for the following:
  - `symptoms.txt`
  - `impressions.txt`
  - `administrators.txt`
  - `doctors.txt`
  - `patients.txt`

### Compilation
- Use `gcc -Wall` to compile the C program.
- Ensure the program is free of syntax errors, warnings, and logical errors.

## Usage Instructions

### Running the Program
1. Compile the source code using GCC:
   ```bash
   gcc -Wall -o <filename>.c

## Menu Structure

#### Doctor Menu
- Log in using credentials stored in `doctors.txt`.
- Create or use existing lists of symptoms and impressions.
- Display or modify symptoms.
- Exit to the main menu.

#### Patient Menu
- Log in using credentials stored in `patients.txt`.
- Enter personal details and symptoms.
- Generate and display an HPI (History of Present Illness) based on entered symptoms.

#### Administrator Menu
- Log in using credentials stored in `administrators.txt`.
- Create new doctor or patient login credentials.
- Display lists of existing credentials.
- Exit to the main menu.

