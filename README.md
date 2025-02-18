# LondonBikesData
Working with Tableau, Visual Studios, Python, and Kaggle

NOT USING KAGGLE API 
- in other projects I have, but for this project I am more focused on gaining experience with Tableau
-  
Steps: 
# Step 1: Data Gathering, Exploration, and Manipulation
- Libraries: pandas, zipfile, kaggle
- Downloaded the data set using "kaggle datasets download -d hmavrodiev/london-bike-sharing-dataset" in the terminal.
- Next I extracted the files from the downloaded zip file using the zipfile library
- read in the csv file as a panadas dataframe
- explored the data using bikes.info() and bikes (this is what i named the pandas dataframe)

- Mapping data
    - Created season dictonarys so that i could map integers 0-3 to the actual season values
    - Created weather dictonary to map integers to the actual value

# Step 2: Export dataframe to excel file
- bikes.to_excel('london_bikes_final.xlsx', sheet_name = 'Data')
- I did this so that I could take the clean and manipulated data to Tableau where I will visualize it!
  
- 
