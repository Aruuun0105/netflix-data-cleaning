# Netflix Data Cleaning

## Summary of Cleaning Steps:

- Filled missing values in:
 -'director' , 'cast', 'country' ,'rating', and 'duration' with 'Unknown' or 'Not Rated'
- Dropped rows where 'date_added' was missing
- Converted 'date_added' to datetime format
- Removed duplicate rows
- Rebamed all column headers to lowercase and replaced spaces with underscores
- Saved the cleaned dataset as 'cleaned_netflix_data,csv'
 