# JSON to CSV Converter

  __Overview__
  
This Java desktop application converts data from a JSON file into a CSV file.
It reads JSON content, maps the information into a suitable structure, and writes the transformed data into a CSV file.

__Project Structure__

- JsonToCsvConverter.java
Main class that executes the program and manages the workflow:

1. Reads the JSON file.

2. Maps the data into a list of records.

3. Writes the records into a CSV file.
   

- JsonService.java
Service responsible for reading JSON files and converting them into a list of Java objects using Jackson.

- CsvService.java
Service responsible for writing a list of objects into a CSV file.

- Person.java
Data model (POJO) representing the structure of the JSON objects.


# How to run it
1.Place your JSON file in the project directory.
2. Compile the project.
3. Run the converter.
4. Output CSV file.
