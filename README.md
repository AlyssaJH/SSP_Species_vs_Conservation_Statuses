# Introduction
The Association of Zoos and Aquariums (AZA) is a non-profit, independent accrediting organization representing more than 250 facilities in the United States and internationally. These facilities may participate in any of the AZA’s many cooperatively managed Species Survival Plan (SSP) programs, which are established to manage a species’ ex situ (meaning “outside of its natural habitat” - e.g. in zoos) population. 

The International Union for Conservation of Nature (IUCN), composed of both governmental and non-governmental organizations, is the global authority on the status of the natural world. The IUCN’s Red List of Threatened Species is the world’s most comprehensive source of information on the global extinction risk status of animal, fungus, and plant species. Evaluated species are classified into one of eight categories: 
- Extinct (EX)
- Extinct in the Wild (EW)
- Critically Endangered (CR)
- Endangered (EN)
- Vulnerable (VU)
- Near Threatened (NT)
- Least Concern (LC)
- Data Deficient (DD)

Additionally, the direction of change of a species’ population size over time is assessed and categorized as one of the following: 
- Increasing 
- Decreasing 
- Stable 
- Unknown 
- Unspecified

This project aims to analyze animal species with dedicated AZA SSPs and their IUCN Red List global extinction risk statuses to determine if SSPs prioritize the world’s most vulnerable species. 

# Project Requirements 

The following features are included in this project in order to fulfull the requirements of Code:Kentucky's data analytics course: 

1. Read TWO data files (JSON, CSV, Excel, etc.).
2. Clean your data and perform a pandas merge with your two data sets, then calculate some new values based on the new data set.
3. Make 3 matplotlib or seaborn (or another plotting library) visualizations to display your data.
4. Utilize a virtual environment and include instructions in your README on how the user should set one up. 
5. Build a custom data dictionary and include it either in your README or as a separate document.
6. Annotate your code with markdown cells in Jupyter Notebook, write clear code comments, and have a well-written README. 

# Running the Program

To run this program, follow these steps: 
1. Clone this repository to your local machine. 
2. Create and activate a virtual environment (instructions below).
3. Install the necessary dependencies by running 'pip install -r requirements.txt'.
4. You can now run all cells in the Jupyter Notebook. 
5. When you are done exploring the repository, deactivate the virtual environment. 

### Virtual Environment Instructions

1. After you have cloned the repository to your local machine, open the project folder in Visual Studio Code.
2. In VS Code, create a virtual environment via the terminal.
3. Activate the virtual environment.
4. Install the required packages.
5. When you are done exploring the repository, deactivate the virtual environment.

### Virtual Environment Commands

| Command | GitBash | Linux/Mac |
| ------- | ------- | --------- |
| Create | python -m venv venv | python3 -m venv venv |
| Activate | source venv/Scripts/activate | source venv/bin/activate |
| Install | pip install -r requirements.txt | pip install -r requirements.txt |
| Deactivate | deactivate | deactivate |

# Discussion 

### Summary

The purpose of this project was to analyze animal species with dedicated AZA SSPs and their IUCN Red List global extinction risk statuses to determine if SSPs prioritize the world’s most vulnerable species. 

To complete this analysis, I created two datasets: one with data retrieved from the Association of Zoos and Aquariums’ Animal Program Database and one with data retrieved from the International Union for Conservation of Nature’s Red List of Threatened species. 

This data was read, cleaned, manipulated, and analyzed using Pandas. All visualizations were created using Matplotlib.  A data dictionary for each dataset is included in the repository and instructions on how to run the project using a virtual environment can be found in the README. 

### Findings

As can be seen from the pie chart titled ‘Species Distribution by Extinction Risk Status’, over half of all species with dedicated SSPs are classified as ‘near threatened’ or ‘least concerned’, the 2 categories least at risk of extinction. Conversely, the populations of over half of the species with dedicated SSPs are classified as ‘decreasing’, which can be seen from the pie chart titled ‘Species Distribution by Population Trend’. The bar chart titled ‘Species Distribution by Extinction Risk Statistics and Population Trend’ unites these results and reveals what percent of SSP species are classified as each unique combination of extinction risk and population trend. 

### Implications

The results of my analysis suggest that species with dedicated SSPs are likely to be faced with a low risk of extinction and a population that is decreasing in size. Whether these parameters are taken into account when determining for which species to establish dedicated SSPs remains unknown. 

It is important to note that SSPs are not the only avenue by which AZA facilities protect vulnerable species. Though a species may not have its own SSP, it is likely safeguarded by at least one of the AZA’s many other conservation initiatives. 

### Future Plans

I plan to continue working on and improving this project in the coming months. My first course of action will be rework instances in which I manually entered data rather than referencing an object. I would also like to explore other methods of creating visualizations, perhaps creating a tableau dashboard. Ultimately, I would like to convert all tasks into custom functions to improve performance. 

# Sources
SSP dataset created with data retrieved from the Association of Zoos and Aquariums' Animal Program Database.

AZA. 2024. Animal Program Database. https://www.aza.org.

Red List dataset created with data retrieved from the Internation Union for Conservation of Nature's Red List of Threatened Species. 

IUCN. 2024. The IUCN Red List of Threatened Species. Version 2024-2. https://www.iucnredlist.org.
