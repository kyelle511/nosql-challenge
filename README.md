# nosql-challenge
Module 12 Challenge - NoSQL </br>
Contributor: Katy Yelle

Context
"The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. The editors of a food magazing 'Eat Safe, Love' wish to have the ratings data evaluated in order to help their journalists and food critics decide where to focus future articles"

### Repository Structure
    -Main Folder
        -.gitignore
        -NoSQL_analysis_starter.ipynb
        -NoSQL_setup_starter.ipynb
        -README.md

    -Sub Folders
        -Resources
            -establishements.json

### Overview
-No_SQL_setup_starter.ipynb </br>
This JupyterNotebook file uses data imported through the terminal (see the Markdown cell at the top for the text used to import the data). It then prepares the uk_food database and establishments collection for use.  The code adds a new document for the restaurant 'Penang Flavours', and uses data in the database to help assign a Business Type ID to the new document. It prepares the database by removing documents from the Dover Local Authrority, and updates the data types for latitude, longitude and Rating Value. 

-No_SQL_analysis_starter.ipynb </br>
This JupyterNotebook file uses the data prepared in the 'No_SQL_setup_starter.ipynb' file so be sure that file has already been run.  This file does an exploratory analysis of the data to answer 4 questions:
1. Which establishments have a hygiene score equal to 20? (i.e. a bad score)
2. Which establishements in London have a Rating Value greater than or equal to 4 (a good rating)?
3. What are the top 5 establishments with a Rating Value of 5 (perfect rating), nearest to the newly added restaurant 'Penang Flavours'? (sorted by lowest hygiene score)
4. How many establishments in each Local Authority area have a hygiene score of 0 (a perfect score)?

Analysis results for each question is also converted to a DataFrame.