<p align="center">
    <img src="https://howtolearnmachinelearning.com/wp-content/uploads/2021/04/coursera_machine_learning_ibm.png?raw=true" alt="IBM and Coursera Logos" width="400" height="133"/>
</p>

# IBM-Capstone-Project through Coursera

<ins>Module 1</ins> : Data Collection
- The application of key concepts in data collection and analysis through APIs and web scraping.
  -  Analyzing HTTP request and utilizing the GitHub REST API to count the number of job postings from various technologies.
  -  Extract the job data from the GitHub Jobs API.
  -  Collect the data through web scarping techniques, downloading webpages, scarping links and images, and extracting data from HTML tables to write into a CSV file.
    
<br/>

<ins>Module 2</ins> :  Data Wrangling
- Perform the cleaning and preparation of the dataset for analysis
    - Find duplicated entries and missing values
    - Remove the duplicated entries and apply suitable strategies for missing data
    - Normalize datasets to ensure consistency and accuracy
 
<br/>

<ins>Module 3</ins> :  Exploratory Data Analysis
- Engage in Exploratory Data Analysis (EDA) techniques to present new insights
    - Plot the data through distribution curves, histograms, and charts
    - Detect outliers to be removed for the integrity of data
    - Reveal key relationships between analysis
    - Explore correlations between various features in the data set
    - Present the findings in a organzized and simplified DataFrame

<br/>

<ins>Module 4</ins> :  Data Visualization
- Extract meaningful insights in the form of visually appealing charts based on the data
    - Visualizing the distribution of data with histograms and box plots
    - Explore the relationships between features using scatter plots and bubble plots
    - Examionation of composition of data using pie charts and stacked bar charts
    - Compare data across categories using line charts and bar charts

<br/>

<ins>Module 5</ins> :  Constructing a Dashboard
- Utilize either IBM Cognos Analytics for interactive dashboard creation for public view
    - Sections based on Current Technology Usuage, Future Technology Trends, and Demographics

<br/>

<ins>Module 6</ins> :  Present Your Findings
A concise creation of compile of justifible finds based on the analysis of the data set. The exploration and conclusions drawn based on complex data through storytelling.

<br/>
Full presentation link: [My Data Analyst Capstone Project by Jordan White] (https://www.canva.com/design/DAGtYShVhCc/mBGnX77192OztIuuoeQ8XQ/edit?utm_content=DAGtYShVhCc&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

<br/>



<br/>

Table of Contents
--
  - [Dataset Description](#data-description)
  - [Tools](#tools)
  - [Tasks to Complete](#tasks-to-complete)
    - Section 1 : [Data Collection](#task-1-data-collection)
    - Section 2 : [Data Wrangling](#task-2-data-wrangling)
    - Section 3 : [Exploratory Data Analysis](#task-3-exploratory-data-analysis)
    - Section 4 : [Data Visualization](#task-4-data-visualization)
    - Section 5 : [Dashboard Implementation](#task-5-dashboard-implementation)
    - Section 6 : [Presentation of Findings](#task-6-presentation-of-findings)
  - [Future Goals](#future-goals)
    
## Dataset Description

A file provdided by Coursera showcasing developers concepts regardiong software technologies. The survey data is exported for synthesis as CSV file containing 65,000 responses. The data set is listed: [Dataset](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/T3iZyjwN9ifjS-B0JaYVgw/survey-data-updated%205.csv),  under Open Database License (ODbL). 

Column Description of Survey data

<table border="1">

<tbody><tr>
  <td><strong>Column name</strong></td>
  <td><strong>Question text</strong></td>
</tr>

  
<tr>
  <td>ResponseId</td>
  <td>Randomized respondent ID number.</td>
</tr>


<tr>
  <td>MainBranch </td>
  <td>Which of the following options best describes you today?</td>
</tr>


<tr>
  <td>Age</td>
  <td>What is your age?</td>
</tr>


<tr>
  <td>Employment</td>
  <td>What is your current employment status?</td>
</tr>


<tr>
  <td>RemoteWork</td>
  <td>How often do you work remotely?</td>
</tr>

<tr>
  <td>Check</td>
  <td>Check	Various verification or check questions related to survey consistency.</td>
</tr>


<tr>
  <td>CodingActivities</td>
  <td>What coding activities do you engage in (hobby, professional, and open-source contributions)?</td>
</tr>

<tr>
  <td>EdLevel</td>
  <td>What is the highest level of formal education you have completed?</td>
</tr>

<tr>
  <td>LearnCode</td>
  <td>How did you learn to code?</td>
</tr>


<tr>
  <td>LearnCodeOnline</td>
  <td>Have you used online resources to learn coding?</td>
</tr>


<tr>
  <td>TechDoc</td>
  <td>How do you use technical documentation?</td>
</tr>


<tr>
  <td>YearsCode</td>
  <td>How many years have you been coding?</td>
</tr>

<tr>
  <td>YearsCodePro</td>
  <td>How many years have you coded professionally?</td>
</tr>


<tr>
  <td>DevType</td>
  <td>What is your role or type of development work you do?</td>
</tr>


<tr>
  <td>OrgSize</td>
  <td>What is the size of the organization you work for?</td>
</tr>


<tr>
  <td>PurchaseInfluence</td>
  <td>How much influence do you have on purchasing technology at your company?</td>
</tr>

<tr>
  <td>BuyNewTool</td>
  <td>How does your company decide whether to buy new tools or technology?</td>
</tr>

<tr>
  <td>BuildvsBuy</td>
  <td>Does your company prefer to build or buy software?</td>
</tr>

<tr>
  <td>TechEndorse</td>
  <td>Do you endorse any specific technologies at your company?</td>
</tr>

<tr>
  <td>Country</td>
  <td>In which country do you reside?</td>
</tr>

<tr>
  <td>Currency</td>
  <td>Which currency do you use day-to-day?</td>
</tr>


<tr>
  <td>CompTotal</td>
  <td>What is your current total compensation (salary, bonuses, and so on)?</td>
</tr>

<tr>
  <td>LanguageHaveWorkedWith</td>
  <td>Which programming languages have you worked with in the past year?</td>
</tr>

<tr>
  <td>LanguageWantToWorkWith</td>
  <td>Which programming languages do you want to work with in the future?</td>
</tr>


<tr>
  <td>LanguageAdmired</td>
  <td>Which programming languages do you admire most?</td>
</tr>

<tr>
  <td>DatabaseHaveWorkedWith</td>
  <td>Which database technologies have you worked with in the past year?</td>
</tr>

<tr>
  <td>DatabaseWantToWorkWith</td>
  <td>Which database technologies do you want to work with in the future?</td>
</tr>

<tr>
  <td>DatabaseAdmired</td>
  <td>Which database technologies do you admire most?</td>
</tr>

<tr>
  <td>PlatformHaveWorkedWith</td>
  <td>Which platforms have you worked with in the past year?</td>
</tr>

<tr>
  <td>PlatformWantToWorkWith</td>
  <td>Which platforms do you want to work with in the future?</td>
</tr>

<tr>
  <td>PlatformAdmired</td>
  <td>Which platforms do you admire most?</td>
</tr>


<tr>
  <td>WebframeHaveWorkedWith</td>
  <td>Which web frameworks have you worked with in the past year?</td>
</tr>

<tr>
  <td>WebframeWantToWorkWith</td>
  <td>Which web frameworks do you want to work with in the future?</td>
</tr>


<tr>
  <td>WebframeAdmired</td>
  <td>Which web frameworks do you admire most?</td>
</tr>

<tr>
  <td>EmbeddedHaveWorkedWith</td>
  <td>Which embedded systems have you worked with in the past year?</td>
</tr>

<tr>
  <td>EmbeddedWantToWorkWith</td>
  <td>Which embedded systems do you want to work with in the future?</td>
</tr>

<tr>
  <td>EmbeddedAdmired</td>
  <td>Which embedded systems do you admire most?</td>
</tr>

<tr>
  <td>MiscTechHaveWorkedWith</td>
  <td>Which miscellaneous technologies have you worked with in the past year?</td>
</tr>

<tr>
  <td>MiscTechWantToWorkWith</td>
  <td>Which miscellaneous technologies do you want to work with in the future?</td>
</tr>

<tr>
  <td>MiscTechAdmired</td>
  <td>Which miscellaneous technologies do you admire most?</td>
</tr>

<tr>
  <td>OpSysPersonal</td>
  <td>What operating systems do you use for personal tasks?</td>
</tr>

<tr>
  <td>OpSysProfessional</td>
  <td>What operating systems do you use for professional tasks?</td>
</tr><tr>

</tr><tr>
  <td>SOVisitFreq</td>
  <td>How frequently do you visit Stack Overflow?</td>
</tr>

<tr>
  <td>SOAccount</td>
  <td>Do you have a Stack Overflow account?</td>
</tr>

<tr>
  <td>SOPartFreq</td>
  <td>How often do you participate in Q&amp;A on Stack Overflow?</td>
</tr>

<tr>
  <td>AISelect</td>
  <td>How do you feel about artificial intelligence tools for development?</td>
</tr>

<tr>
  <td>AIBen</td>
  <td>What benefits have you experienced from using AI tools?</td>
</tr>

<tr>
  <td>AIChallenges</td>
  <td>What challenges have you faced while using AI tools?</td>
</tr>

<tr>
  <td>JobSat</td>
  <td>How satisfied are you with your current job?</td>
</tr>




</tbody></table>

We will examine, extract, transform, analyze and report our analysis.



## Tools
- [`python`](https://www.python.org/downloads/) v3.12.2
- [`pandas`](https://pandas.pydata.org/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMML0187ENSkillsNetwork31430127-2021-01-01) for managing the data.
- [`numpy`](https://numpy.org/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMML0187ENSkillsNetwork31430127-2021-01-01) for mathematical operations.
- [`seaborn`](https://seaborn.pydata.org/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMML0187ENSkillsNetwork31430127-2021-01-01) for visualizing the data.
- [`matplotlib`](https://matplotlib.org/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMML0187ENSkillsNetwork31430127-2021-01-01) for additional plotting tools.
- [`folium`](https://python-visualization.github.io/folium/latest/) for geospatial data visualization such as choropleth maps.
- [`plotly`](https://plotly.com/python/) for interactive plotting tools.
- [`Google Looker Studio`](https://lookerstudio.google.com/overview) for dashboards.
- [`IBM Cognos Analytics`](https://www.ibm.com/products/cognos-analytics) for dashboards

## Tasks to Complete
### Task 1: Data Collection
- [x] Collecting Data using APIs
- [x] Collecting Data Using Web Scraping
- [x] Exploring Data

### Task 2: Data Wrangling
- [x] Finding Missing Values
- [x] Determine Missing Values
- [x] Impute Missing Values
- [x] Removing Duplicates
- [x] Normalizing Data
- [x] Data Wrangling

### Task 3: Exploratory Data Analysis
- [x] Analyzing Distrirbution
- [x] Handling Outliers
- [x] Correlation

### Task 4: Data Visualization
- [x] Distribution of Data
- [x] Visualizing Relationship
- [x] Visualizing Composition of Data
- [x] Comparison of Data

### Task 5: Dashboard Implementation
- [x] Dashboard

### Task 6: Presentation of Findings
- [x] Final Presentation

### Future Goals
- [x] Create Dashboard in Tableau or Google Studio Looker.

