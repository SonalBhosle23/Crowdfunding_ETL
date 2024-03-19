# Crowdfunding ETL Mini Project

This repository contains the code and resources for the Crowdfunding ETL (Extract, Transform, Load) mini project. The project focuses on extracting data from CSV files, transforming it using Pandas, NumPy, datetime, and regular expressions (regex), and loading it into a relational database.

## Project Structure

The repository is structured as follows:

- **Output folder**: Contains screenshots as evidence of the creation of the schema in our database and the SQL file.
- **Resources folder**: Contains imported and exported files used in the notebook code.
- **ETL_Mini_Project notebook file**: This is the main notebook file containing the ETL process.

## Dependencies

The ETL_MINI_Project notebook utilizes the following dependencies:

- Pandas
- NumPy
- Datetime
- Regular expressions (regex)

## Approach

In this project, we opted for Option 2 to utilize regular expressions as our means to extract information from the CSV files. This approach allows for flexible and precise extraction of data patterns from unstructured text.

## Outputs

After extracting, transforming, and loading the data, we created an Entity-Relationship Diagram (ERD) to represent the database schema. Screenshots of the ERD and other relevant outputs can be found in the **Output folder**.

## Usage

To replicate the ETL process:

1. Ensure you have the required dependencies installed.
2. Open and run the `ETL_Mini_Project` notebook file.
3. Follow the instructions and code within the notebook to execute the ETL process.
4. Refer to the outputs in the **Output folder** for evidence of the work done.

## Database Creation

1. Create the database.
2. Execute the 'crowdfunding_db_schema.sql' script in pgAdmin 4.
3. Import the CSV files, ensuring that 'contacts.csv', 'category.csv', and 'subcategory.csv' are imported before 'campaign.csv'.

## Conclusion

The Crowdfunding ETL mini project demonstrates the process of extracting data from CSV files, transforming it using various Python libraries, and loading it into a relational database. The use of regular expressions enhances the flexibility and accuracy of data extraction, while the generated ERD provides a visual representation of the database schema.

### Team Members
- Sonal Bhosle
- Simone Nagel
- Oliver James Uy

### Resources:
Reference for split function
https://stackoverflow.com/questions/14745022/how-to-split-a-dataframe-string-column-into-two-columns

To create ERD:
http://www.quickdatabasediagrams.com/