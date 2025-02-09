# Trip Data Analysis

This project analyzes a large dataset of flight data containing 1,000,000 rows. The goal is to perform several key tasks related to flight operations and their scheduling. Below are the tasks included in this analysis:

## Tasks

### 1. Counting Monthly Flights
- **Objective**: Find the number of flights landing at **Amsterdam Airport Schiphol** in **2024**, broken down by month.

### 2. Filtering Flights by Departure Time
- **Objective**: Extract flights departing from **Tokyo Haneda Airport** between **09:00 and 18:00**, and store the results in a file.

### 3. American Airlines Flights from Seoul
- **Objective**: Identify all **American Airlines** flights departing from **Seoul Incheon International Airport** and store the results in a file.

### 4. Overnight Flights Count
- **Objective**: Calculate the number of overnight flights per month in **2024**. These flights depart between **20:00 and 23:00** and arrive the next day after **03:00**.

### 5. Occupancy Rate Calculation
- **Objective**: Calculate the occupancy rate for each flight departing from **John F. Kennedy International Airport** between **09:00 and 15:00**, and store the results in a file.

#  Order Data Analysis

process and analyze order data using Apache Spark. It processes a text file containing details of orders such as IDs,Product Code, quantities, and prices, then calculates the total value for each order based on this data.

## Project Purpose

- **Data Processing**: Analyze data using Apache Spark to improve performance when dealing with large datasets.
- **Total Calculation**: Compute the total value of orders based on quantities and prices.

## Expected Results

- **Order Total Values**: Calculate the total value for each order ID.
- **Decimal Precision**: Ensure decimal precision by rounding the values to two decimal places.

# Student and Major Data Analysis

This project performs data analysis on two datasets: students and majors. It joins the datasets based on a common key (the student ID) to extract information about students and their associated majors.

## Tasks

### 1. Data Loading
- **Objective**: Load two datasets:
  - **Students Dataset**: Contains student details like ID, first name, last name, Group ID.
  - **Majors Dataset**: Contains major codes and their corresponding major names.

### 2. Data Transformation
- **Objective**: 
  - Process the **students dataset** to extract student details and format them into a tuple consisting of the major and the full name (first and last names).
  - Process the **majors dataset** to create tuples where the first element is the major code and the second element is the major name.

### 3. Data Join
- **Objective**: join between the two datasets using the major code to match students with their corresponding major names.

### 4. Results Extraction
- **Objective**: Extract and display the full name of students along with their major names.
