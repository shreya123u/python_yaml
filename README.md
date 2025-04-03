 Step 1: Install Required Packages
 To handle YAML files in Python, you will need the PyYAML library. If you don't have it installed, you can install it
 using pip. Open your terminal and run:
 ![Screenshot 2025-04-03 155715](https://github.com/user-attachments/assets/b5851863-9106-409f-b426-c3c51be8e2c1)
 
 Step 2: Create the YAML File
 Create a YAML file named students.yaml. This file will contain information about students, including their
 names, ages, majors, and GPAs. Here’s an example structure:
![image](https://github.com/user-attachments/assets/4da4dc65-e8b2-4be5-a9ef-f3c7b75bb7aa)

 Explanation of the YAML Structure
 students: This is a list of dictionaries, where each dictionary represents a student.
 Each student has attributes:
 name: The student's name.
 age: The student's age.
 major: The student's field of study.
 gpa: The student's Grade Point Average.

 
 Step 3: Write the Python Application
 Create a new Python file named app.py. This script will read the data from the YAML file, allow users to view
 all students, and filter students by GPA.
 Here’s the complete code with explanations
 ![image](https://github.com/user-attachments/assets/9d3ad0df-0e9a-49e4-873b-f286c1d7329c)

 Explanation of the Code
 1. Importing the Library:
 import yaml: This imports the PyYAML library, allowing us to work with YAML files.
 2. Loading Data:
 2025-04-01
 The load_data function opens the specified YAML file, reads its contents, and converts it into a
 Python dictionary using yaml.safe_load.
 3. Displaying Students:
 The display_students function takes a list of student dictionaries and prints their details.
 4. Filtering Students:
 The filter_students_by_gpa function takes a minimum GPA and filters the list of students. It
 uses a list comprehension to create a new list containing only those students whose GPA meets
 or exceeds the specified value.
 5. Main Function:
 The main function orchestrates the loading of data, displaying all students, and prompting the
 user for a GPA to filter by.
 6. Execution Block:
 The if __name__ == "__main__": block ensures that the main function runs only when the
 script is executed directly, not when imported as a module.


 Step 4: Run the Application
 1. Make sure both app.py and students.yaml are in the same directory.
 2. Open your terminal, navigate to the directory, and run:

 Expected Output
 When you run the application, you should see output similar to this:

 ![Screenshot 2025-04-03 155724](https://github.com/user-attachments/assets/8085d54a-e0f4-4ce8-8871-e8d1a1e8abdd)

 
 Conclusion
 
 This application serves as a basic example of how to read data from a YAML file and utilize it within a Python
 program. You can expand upon this foundation by adding more features, such as sorting, updating student
 information, or saving changes back to the YAML file

  

 
 
 
