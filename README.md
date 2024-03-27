# Business Card Information Extraction Application 

This Streamlit application allows users to upload an image of a business card and extract relevant information from it using easyOCR. The extracted information includes the company name, cardholder name, designation, mobile number, email address, website URL, area, city, state, and pin code. Users can then save the extracted information along with the uploaded business card image into a database.

Table of Contents:

Problem Statement
Approach
Results
Usage
Requirements
Installation
How to Run
Contributing
License
Problem Statement
As per the project requirements, the task is to develop a Streamlit application that facilitates the extraction of business card information from uploaded images. The extracted data should be displayed in a clean and organized manner on the graphical user interface (GUI). Additionally, users should have the ability to save this information along with the uploaded image into a database. The application should support operations such as reading, updating, and deleting data through the Streamlit UI.

Approach:

Install Required Packages: Install Python, Streamlit, easyOCR, and a database management system like SQLite or MySQL.

Design User Interface: Create an intuitive UI using Streamlit to guide users through the process of uploading an image and extracting information.

Implement Image Processing and OCR: Utilize easyOCR to extract relevant information from the uploaded business card image, employing image processing techniques for enhancement.

Display Extracted Information: Present the extracted information in an organized manner within the Streamlit GUI.

Implement Database Integration: Utilize SQLite or MySQL to store extracted information and images. Implement CRUD operations for data management.

Test the Application: Thoroughly test the application to ensure functionality.

Improve the Application: Continuously enhance the application by adding features, optimizing code, and addressing bugs.

Results:

The result is a Streamlit application that facilitates the extraction of business card information from uploaded images. Users can upload images, extract data, and save it along with the image into a database. The application provides a user-friendly interface and supports CRUD operations for efficient data management.


License

NA



