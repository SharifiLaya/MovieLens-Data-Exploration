## MovieLensData Exploration
**Data Description**
- Movie lens data was collected by the GroupLensresearch project atthe university of Minnesota.
- Domain -Entertainment and Internet
- Context -The GroupLensResearch Project is a research group inthe Department of Computer Science and Engineering at theUniversity of Minnesota. The data is widely used for collaborativefiltering and other filtering solutions. However, we will be using thisdata to act as a means to demonstrate our skill in using Python to“play” with data.

**Attribute Information**
- Download the zip file from data source
- Extract the zip file and you will find a folder named ml-100k
- Go through the README file that you will find in the folder from the above stepwhere you will find the information about the attributes in the three datasets

**Learning Outcomes:**
- Exploratory Data Analysis
- Visualizations using python
- Pandas

**Stepsandtasks:**
- You will need to import 3 files from the folder as dataframes into your Jupyter notebook -u.data, u.item, u.user.
- Display univariate plots of the attributes:'rating','age','releasedate','gender'and'occupation',from their respective dataframes
- Visualize how popularity of Genres has changed over the years.From the graph one should be able to see for any given year,movies of which genre got released the most.
- Display the top 25 movies by average rating,as a list/series/dataframe.Note:-Consideronly the movies which received at leasta 100 ratings

__Verifythefollowingstatements(noneedofdoingastatisticaltest.Compareabsolutenumbers):__

• Menwatchmoredramathanwomen,
• MenwatchmoreRomancethanwomen,
• WomenwatchmoreSci-Fithanmen
