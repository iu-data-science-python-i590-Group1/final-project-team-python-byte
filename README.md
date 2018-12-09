# final-project-team-python-byte
M.S. Data Science at Indiana University | Python I590 | Final Project | Team Python Byte

# Phase 1

Name 1: Sachin Sharma
1. Project setup on GITHUB with all required folder structure
2. Added Folder structure with Code and Data
3. Added 'BreastCancerWisconsin.csv' file in data folder
4. Added main file 'FinalAssignment-Phase1.ipynb' in code folder
5. Implemented solution for phase 1 assignment as per instruction and added markup
    - Data cleaning - report Number of NaN, replace ?, impute NaN by the column mean
    - Data Stats
    - Plotting Scatterplot and Bar Plot must have titles,y axis and x axis names, non-default colors. 9 histograms (subfigures) do not         have to have titles
    - Import libraries, Proper data import
    - Github set up with one folder for code and one folder for dataset
    - Readme file with contributions
 6. Merged my branch 'final-project-phase-1-sacshar' to master and verify that code is running successffully

Name 2: Leonardo
1.	Reviewed the code and completed each step of phase I assignment.
2.	Made the following changes:

    •	Changed single histogram to have one histogram for each variable.
    
    •	Changed chart labels/title
    
    •	Changed wording in markdown cells
    
    •	Formatted scatter plots.
    
    •	Changed bar plot colors and added titles for cancer types
    
    •	Rounded .describe() summary statistic results 
    
    •	Changed scatter plot colors 
    
    •	Added correlation analysis
    
    •	Added standard deviation analysis
    •	Added variance analysis
    •	Added mode analysis
    •	Added final summarization of data narrative

3.	Pushed desktop branch to GitHub branch.
4.	Review done and merged to master.
5.  Submitted assignment in Canvas.


Name 3: Mario
1. Reviewed Code and made sure the same calculations could be done in PyCharm as were done in Jupyter.
   - Made sure all calculations are done and consistent throughout the entire project. For example the mean was calculated and filled into the correct NAN fields.
2. Made sure the code would work on a variety of environments
3. Reviewed if different sets of code arrived at the same conclusion (example handling a task in pandas two different ways)
QA process steps. Made sure each bullet point was completed from the list of tasks assigned in the Assignment Details. Below are the specifics:
    - Completed: Replace ? by NaN in column A7. Use ____.replace('?', np.NaN) - but properly specify A7 column. (Completed Under Markdown 'Replace ? by NaN in column A7'
    - Completed: After replacing - your column needs to be converted back to numeric. Apply pandas function pd.to_numeric() for column A7 - Shown through printing the datatype as an object, then shown through changing through to_numeric function
    - Completed: Report how many NaN. Use isnull() function applied to the dataframe. Then you can use arithmetic sum(): Shown after Markdown 'Check Null Values and Total Count'
    - Completed: Replace NaN values with the mean of column A7. Use fillna() - Shown after 'Replace NaN values with the mean of column A7'
    - Completed: Provide the summary statistics - Shown after Markdown 'Provide the summary statistics'
    - Completed: Find number of columns and number of rows - Shown after Markdown 'Find number of columns and number of rows' using assignment of first value to rows and second value to columns. Shown after Markdown 'Report how many unique id values (column Scn)' Which uses the unique function to return a list and len to count the list.
    - Completed: Report how many unique id values (column Scn) - hint the length of unique ids
    - Completed: Draw histograms for columns A2-A10. Note: you need to subset your dataframe - slice only columns A2-A10. Use histogram function, add a color of your choice. Note you need to run hist() function on your dataframe with selected columns only. It will output all 9 columns as subplots. Here do not worry about individual titles, y and x axis. You could adjust bins and alpha (opacity) on your histograms



# Phase 2

Name 1: Sachin Sharma
1. Added file 'FinalAssignment-Phase2.ipynb' in code folder
2. Implemented solution for phase 2 assignment as per instructions and added markup
    - Use KMeans algorithm (do not use column CLASS)
    - Find the optimal number of clusters
    - Revise data variation
    - Implement normalization
3. Updated & Merged my branch to master and verify that code is running successffully
4. Reviewed the code and make it to the closure

Name 2: Leonardo
1. Reviewed the code and completed each step of phase II assignment.
2. Added the scatter matrix.
2. Increased the size of the inertia plot.
3. Added the Optimal Number of Clusters Analysis.
4. Rounded the standard deviation values.
5. Created the plot showing all standard deviation values.
6. Created a different box plot that included all variable in one plot.
7. Added the Data Variation Analysis.
8. Pushed desktop branch to GitHub branch.
9. Review completed and merged to master.

Name 2: Mario Angelier
1. Reviewed code. Made sure each item was complete based on phase II requirements2. 
2. Added shape of centoid array. Allows users to see the shape in addition to the details
3. Added Context to which features have the most variability
4. Added Context on the ideal number of clusers from KMeans on this dataset
5. Made sure we followed requirements in order as they were requested
6. Pushed local branch
7. Team merged into final master branch
Extra Note - Seems like on this phase we had done duplicated work however in both cases individually the team arrived at the same result

# Phase 3
Name 1: Sachin Sharma

Name 2: Mario Angelier
1. Created Dataframe to import into KMeans model
2. Created labels based on new cluster parameters
3. Merged labels into original dataframe
4. Created the Error Rate function
5. Printed out each Error Rate based on the return of the function.
6. Pushed local Phase 3 branch to the master

Name 3: Leonardo
1. Reviewed the code and completed each step of phase III assignment.
2. Adjusted code to remove "SCN" column and keep "Class" 
3. Removed unnecessary analysis
3. Added the density plot for analysis.
4. Added the Report Statement.
5. Pushed desktop branch to GitHub branch.
6. Review completed and merged to master.
