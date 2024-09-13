# Student-Enrollment-From

This project is a web-based form for enrolling students, which stores data in the `STUDENT-TABLE` relation of the `SCHOOL-DB` database. The form ensures validation, updates, and allows users to interact with the student data effectively using **JsonPowerDB** as the database. 

## Table of Contents

- [Description](#description)
- [Benefits of Using JsonPowerDB](#benefits-of-using-jsonpowerdb)
- [Project Features](#project-features)
- [Release History](#release-history)
- [Illustrations](#illustrations)
- [Scope of Functionalities](#scope-of-functionalities)
- [Examples of Use](#examples-of-use)
- [Project Status](#project-status)
- [Sources](#sources)
- [Other Information](#other-information)

## Description

The **Student Enrollment Form** allows users to add and manage student details in the `STUDENT-TABLE` of the `SCHOOL-DB` database. The form uses JsonPowerDB to save, update, and retrieve student records. The form has three main control buttons:
- **[Save]**: To add new student data.
- **[Update]**: To modify existing student records.
- **[Reset]**: To clear and reset the form.

Input Fields:
- **Roll No** (Primary Key)
- Full Name
- Class
- Birth Date
- Address
- Enrollment Date

On page load or control button click, the form will display with only the primary key field enabled. The other fields and buttons will be disabled until the primary key is entered and validated.

## Benefits of Using JsonPowerDB

- **Fast and Efficient**: JsonPowerDB offers quick access and manipulation of data without the need for complex configurations.
- **Schema-Free Database**: Allows dynamic structure, making it easy to store unstructured data.
- **Real-Time Update**: JsonPowerDB enables real-time updates without requiring the page to reload.
- **Minimal Setup**: No server-side scripting required, making development faster and easier.
- **Cross-Platform**: Can be used across multiple platforms.

## Project Features

1. **Save**: Saves a new student record when the primary key doesn't exist.
2. **Update**: Allows modification of student data when the record exists in the database.
3. **Reset**: Resets the form to its default state.
4. **Validation**: Ensures no empty fields during data entry.

## Release History

| Date       | Version | Description                   |
|------------|---------|-------------------------------|
| 2024-09-14 | 1.0     | Initial release of the project |
  
The source code for this project is available on [GitHub](https://github.com/Swapnalipatil03/Student-Enrollment-From).

## Illustrations

This project provides:
- A well-designed UI for student data entry.
- Smooth interaction between form elements and database functions.

## Scope of Functionalities

The project supports:
- Adding new student records.
- Updating existing student records.
- Resetting form data.
- Input validation for all fields.

## Examples of Use

1. **Adding a New Student**: Enter a unique Roll No and fill in other details. Click on the **Save** button to add the record to the database.
2. **Updating Student Information**: Enter an existing Roll No, modify other fields, and click the **Update** button to save changes.
3. **Resetting the Form**: Click the **Reset** button to clear the form and begin a new entry.

## Project Status

This project is currently in version 1.0. Future enhancements could include:
- Adding search functionality.
- Creating advanced reports from student data.
- User authentication for admin roles.

## Sources

The project relies on:
- **JsonPowerDB** for backend database handling.
- **HTML5, CSS, JavaScript** for frontend development.
  
## Screenshorts

![image](https://github.com/user-attachments/assets/e9a1116c-20e4-4f97-88c8-5ff6e03a1e30)

![image](https://github.com/user-attachments/assets/f32dda28-aa9e-43b5-9dfc-12c54519a82f)

![image](https://github.com/user-attachments/assets/a0f588bd-ebc2-4658-a3e0-062ebf83bc26)


This project demonstrates the power and simplicity of JsonPowerDB in web-based applications. It showcases essential operations like saving, updating, and validating data efficiently.

For more information, please refer to the [official JsonPowerDB documentation](https://login2explore.com/jpdb/docs.html).

