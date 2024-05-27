# AirBnB Clone - Web Static

## Project Overview
The **AirBnB clone** is an online platform that connects people who have a home to offer with those who need a place to stay temporarily. In this project, we'll focus on the **web static** aspect of the application.

### Objectives
1. Develop simple HTML static pages.
2. Create a style guide.
3. Use fake content.
4. Avoid using JavaScript.
5. Organize files and folders appropriately.

## Requirements
- **Python Scripts:**
    - Allowed editors: vi, vim, emacs.
    - Files will be interpreted/compiled on Ubuntu 20.04 LTS using Python 3.8.5.
    - All files must be executable.
    - The length of your files will be tested using `wc`.
    - Python unit tests should be inside a folder named `tests`. Use the `unittest` module.
    - Test files should start with `test_`.
    - Execute tests with the command: `python3 -m unittest discover tests`.

- **HTML and CSS:**
    - All CSS files should be in a folder named `styles`.
    - Images should be in a folder named `images`.
    - Avoid using `!important` and `id` in the CSS file.
    - Do not use `<img>`, `<embed>`, or `<iframe>` tags.
    - No cross-browser compatibility issues.
    - Style code according to PEP 8 (version 2.7.*).
    - Ensure W3C compliance and validate with W3C-Validator.

## Repository Structure
Here's an overview of the relevant files in the repository:

1. **models/base_model.py:**
    - Defines common attributes/methods for other classes.

2. **models/engine/file_storage.py:**
    - Serializes instances to a JSON file and deserializes JSON files to instances.

3. **console.py:**
    - Contains the entry point of the command interpreter.

4. **models/user.py:**
    - Defines the `User` subclass.

5. **models/state.py:**
    - Defines the `State` subclass.

Feel free to explore the project further, and if you have any questions or need additional information, don't hesitate to ask! 😊
