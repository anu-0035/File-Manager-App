# File-Manager-App
A file manager app in Python is a software application that allows users to browse, organize, and manage files and directories on their system. It typically features functionalities like file creation, deletion, renaming, moving, and searching, providing a command-line interface for efficient file handling.

Here's the algorithm for your Python file manager app presented in a structured format:

### Algorithm for File Manager App

#### 1. Start the Application
- Display the message: "File Manager App" and show menu options.

#### 2. Main Loop
- **While** the application is running:
  - Display options:
    1. Create a file
    2. View all files
    3. Delete a file
    4. Read a file
    5. Edit a file
    6. Exit
  - Prompt the user to enter a choice.

#### 3. Handle User Choices
- **If** choice is **1** (Create a file):
  - Prompt user for the file name.
  - Call `create_file(file_name)` function.
  
- **If** choice is **2** (View all files):
  - Call `view_files()` function.
  
- **If** choice is **3** (Delete a file):
  - Prompt user for the file name.
  - Call `delete_file(file_name)` function.
  
- **If** choice is **4** (Read a file):
  - Prompt user for the file name.
  - Call `read_file(file_name)` function.
  
- **If** choice is **5** (Edit a file):
  - Prompt user for the file name.
  - Call `edit_file(file_name)` function.
  
- **If** choice is **6** (Exit):
  - Print "Closing the App!" and terminate the loop.
  
- **If** the choice is invalid:
  - Print "Invalid choice! Give a valid choice between 1-6."

#### 4. Function Definitions
- **create_file(file_name)**: 
  - Attempt to create a file with the specified name.
  - Handle `FileExistsError` and other exceptions.

- **view_files()**: 
  - List all files in the current directory.
  - Handle the case where no files exist.

- **delete_file(file_name)**: 
  - Attempt to delete the specified file.
  - Handle `FileNotFoundError` and other exceptions.

- **read_file(file_name)**: 
  - Attempt to read the content of the specified file.
  - Handle `FileNotFoundError` and other exceptions.

- **edit_file(file_name)**: 
  - Attempt to append content to the specified file.
  - Handle `FileNotFoundError` and other exceptions.

#### 5. End of Application
- Exit the program gracefully.

This format clearly outlines the steps and functions involved in your file manager app, making it easy to understand and follow.


