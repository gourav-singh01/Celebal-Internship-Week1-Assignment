# Celebal Internship - Week 1 - Assignment

This repository contains my submission for the Week 1 assignment of the Celebal Technologies internship. The focus of this week was getting familiar with basic data exploration and cleaning using Python and Pandas.

## Project Structure
* `assignment1.ipynb` - The Google Colab notebook containing all the step-by-step cleaning and processing code.
* `Cleaned_Combined_dataset.csv` - The final cleaned dataset exported after completing the tasks.

## Steps Completed
1. Loaded the raw `Combined_dataset.csv` into a Pandas DataFrame and inspected its shape, columns, and data types.
2. Handled missing data by filling blank text fields with placeholders and imputing missing ratings with the median.
3. Found and dropped duplicate rows to keep the data unique.
4. Cleaned up the price formatting and generated a random `quantity` column to simulate realistic order sizes.
5. Created a new derived column for `total_amount` by multiplying the price and quantity.
6. Filtered the data to separate and view highly-rated products (rating > 4.0).
7. Saved the final structured data into a new CSV file.
