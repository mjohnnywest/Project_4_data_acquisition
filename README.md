# Project_4_data_acquisition
## Link to Dashboard
https://lookerstudio.google.com/reporting/3deeae7d-a26e-4861-acd0-739a21d010a3

Please follow the link above to visit the dashboard used for the project

## Intro
The Python portion of this project is designed to acquire the data to put into the dashboard of the project. It takes user inputs and credit card statements, and transforms the data into a format that our dashboard can read.

## Features

- Has a menu containing options for adding data, either manually, or using card statements
- Creates or overwrites dataframes for the dashboard to read
- Options to add several transactions of each type, in different currencies

## Requirements

- Python 3.13 or higher
- Any text editor compatable with ipynb files

Required library to pip install:

- pandas

## Usage

Ensure Pandas is pip installed

Ensure all statements that yolu would like to upload is in the "statements" folder 

Ensure you are no longer using the data in the "output" folder, data will be overwritten when exported

Ensure "project_4_data_acquisition.ipynb" is outside the "output" and "statements" folder

Open "project_4_data_acquisition.ipynb" with a text editor compatable with IYPNB files

Click "Run All" and allow the code to run

Enter numbers corresponding to the menu items listed on the cell running initialize() 

When complete, either quit without saving, to keep output folder, or Finish and export data to save the dataframes

## Future Plans

In the future, basic AI models can be trained using supervised learning, and can be added to automatically categorize purchases 

The front-end could be implimented with Flask or Javascript to make a user friendly UI for adding data 

## Notes

Stack Overflow and Geeks for Geeks was used heavily in the writing of this code, and Claude AI was used to optimize code after it was written 

## Contributing

Pull requests are welcome
