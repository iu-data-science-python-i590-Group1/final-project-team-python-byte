# final-project-team-python-byte
M.S. Data Science at Indiana University | Python I590 | Final Project | Team Python Byte

# Phase 1

Name 1: Sachin Sharma
1. Project setup on GITHUB with all required folder structure
2. Added Folder structure with Code and Data
3. Added 'BreastCancerWisconsin.csv' file in data folder
4. Added main file 'FinalAssignment-Phase1.ipynb' file
5. Implemented solution for phase 1 assignment as per instruction added markup
6. Merged my branch 'final-project-phase-1-sacshar' to master and verify that code is running successffully

Name 2: Mario
1. Reviewed Code and made sure the same calculations could be done in PyCharm as were done in Jupyter.
   - Made sure all calculations are done and consistent throughout the entire project. For example the mean was calculated and filled into the correct NAN fields.
2. Made sure each bullet point was completed from the list of tasks assigned in the Assignment Details. Below are the specifics:
    - Completed: Replace ? by NaN in column A7. Use ____.replace('?', np.NaN) - but properly specify A7 column. (Completed Under Markdown 'Replace ? by NaN in column A7'
    - Completed: After replacing - your column needs to be converted back to numeric. Apply pandas function pd.to_numeric() for column A7 - Shown through printing the datatype as an object, then shown through changing through to_numeric function
    - Completed: Report how many NaN. Use isnull() function applied to the dataframe. Then you can use arithmetic sum(): Shown after Markdown 'Check Null Values and Total Count'
    - Completed: Replace NaN values with the mean of column A7. Use fillna() - Shown after 'Replace NaN values with the mean of column A7'
    - Completed: Provide the summary statistics - Shown after Markdown 'Provide the summary statistics'
    - Completed: Find number of columns and number of rows - Shown after Markdown 'Find number of columns and number of rows' using assignment of first value to rows and second value to columns. Shown after Markdown 'Report how many unique id values (column Scn)' Which uses the unique function to return a list and len to count the list.
    - Completed: Report how many unique id values (column Scn) - hint the length of unique ids
    - Completed: Draw histograms for columns A2-A10. Note: you need to subset your dataframe - slice only columns A2-A10. Use histogram function, add a color of your choice. Note you need to run hist() function on your dataframe with selected columns only. It will output all 9 columns as subplots. Here do not worry about individual titles, y and x axis. You could adjust bins and alpha (opacity) on your histograms

Name 3: Leonardo
1. Reviewed the code and made the following changes:
    -Changed single histogram to have one histogram for each variable.
    -Changed chart lables/title
    -Changed wording in markdown cells
    -Formated scatter plots.
    -Changed bar plot colors and added titles for cancer types
    -Rounded .describe() summary statitic results 
    -Changed scatter plot colors 
    -Added correlation analysis
    -Added standard deviation analysis
    -Added variance analysis
    -Added mode analysis
    -Added final sumerization of data narrative
2. Pushed desktop branch to github branch
3. Pending review from team to merge to master 

# Phase 2
Name 1: Sachin Sharma

Name 2: Mario

Name 3: Leonardo

# Phase 3
Name 1: Sachin Sharma

Name 2: Mario

Name 3: Leonardo
