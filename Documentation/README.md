# Github Organization Generator
## Project Description
This process will create a GitHub organization with the name and contact email provided by the user. It will read an excel sheet containing the organization members (including owners, if applicable) into a datatable and iterate through it to add them to the newly created organization.

## Technologies Used
- UiPath Studio version 2021.4.4
- Excel
- Microsoft Edge

## Features
- User can login/logout of Github
- User can create a new Github Organization
- User can add members/owners to the newly created Github Organization
- User can use a local excel file or download one from MS Office 365

## Getting Started
To Clone: `git clone https://github.com/UiPath-Project3-1/uipath-automation-6.git`
- You will need a valid GitHub account for the robot to login to and create the organization with.
- You will need an **xlsx** or **csv** file which contains two columns with the headers *Username* and *IsOwner*. The values in the *Username* column should only be the username for a person's Github account, not their URL. As for the *IsOwner* column, indicate whether or not that user is an owner of your organization by using the values **TRUE** or **FALSE** and **YES** or **NO**.

## Usage
To run this project from UiPath Studio, follow these steps:
  - Open the **Main.xaml** and select *Run* from the **Debug File** drop down.

## Contributors
### Team 2
<a href='https://github.com/andressiles'>Team Lead - Andres Siles-Loayza</a>

<a href='https://github.com/antonyt96'>Anthony Tejada</a>

<a href='https://github.com/jamesPan3'>James Panebianco</a>

<a href='https://github.com/shakum25'>Shalei Kumar</a>

<a href='https://github.com/schigit'>Shantel Chi</a>

### Team 3
<a href='https://github.com/jjennings510'>Team Lead - Jacob Jennings</a>

<a href='https://github.com/vrobweis'>Solution Architect - Vincent Weis</a>

<a href='https://github.com/JAGibW'>Julie Gibson</a>

<a href='https://github.com/MBachkabakian'>Michael Bachkabakian</a>

<a href='https://github.com/foleyb25'>Brian Foley</a>

### Team 3
<a href='https://github.com/'>Team Lead - Miles Plurad</a>

<a href='https://github.com/AntonM-248'>Anton Marku</a>

<a href='https://github.com/daniellieser'>Daniel Lieser</a>

<a href='https://github.com/JoeStalnaker'>Joe Stalnaker</a>
