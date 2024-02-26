# NetLog Datamodel Analysis

This repository contains the documentation and workflow details for the NetLog Datamodel analysis project. The provided dataset underwent extensive analysis to develop the NetLog Datamodel, incorporating sorting, adding new columns, utilizing VLOOKUP formulas, and various data manipulation techniques. 

## Table of Contents

1. [Project Overview](#project-overview)
2. [Deliverables and Workflows](#deliverables-and-workflows)
3. [Data Sheet Download](#data-sheet-download)
4. [Project Management](#project-management)
5. [Results/Findings](#Results/Findings)
6. [Contributors](#contributors)
7. [Acknowledgments](#acknowledgments)

## Project Overview

The primary objectives and tasks completed in this project are as follows:

- **Sorting LogDate and LogTime**: The LogDate and LogTime columns were sorted from newest to oldest, adhering to project requirements for data coherence.

- **Addition of New Columns**: Several new columns, including RecordTypeName, PrevLogDate, PrevLogTime, PrevLogRecordType, and PrevDetailsData, were added to enrich the Datamodel.

- **Data Retrieval with VLOOKUP**: VLOOKUP formulas were utilized to retrieve data for the added columns, enhancing the dataset's informational depth.

- **Handling #N/A Values**: To address issues with #N/A values, adjustments were made, including increasing the height/search range to 162, and special measures were taken to lock in VLOOKUP formulas through copy and paste special values.

- **Sample Data and Record Layouts**: Details of sample data and record layouts for Device and User logs from different data centers were provided.

- **Pivot Table Creation**: Pivot tables were created for the 112 and 113 RecordTypes using the corresponding Datamodels.

- **Categorization and Text Extraction**: New columns like Wi-Fi Devices and Workstations (Cabled Devices) were added for categorization. Additionally, columns like TempStr and UserName were created using formulas to extract relevant information.

- **Workflow Documentation**: Detailed workflow documentation was provided for creating the Datamodel from log data and filtered records, including steps for data extraction, filtering, and analysis.

- **Analysis and Visualization**: Various analysis tasks were performed, including calculating time differences, creating pivot tables, and profiling login times.

## Deliverables and Workflows

The project involved the creation of several deliverables and workflows, including but not limited to:

- Practical D - ReadMeFirst sheet
- Documentation for creating DM from Log and Filtered Records
- Postings Review Sheet
- Survey generation for "Junior Data Analyst" job positions
- Analysis and addition of columns to captured responsibilities data
- Extraction of NetLog Data for further work on specific issues
- Creation of Record Types sheet and sorting
- Workflow documentation for various tasks such as filtering records, creating pivot tables, and calculating time differences
- Documenting and tracking progress for each task


## Project Management

The project was managed meticulously, with detailed documentation, tracking, and version control to ensure transparency and accountability throughout the process.

## Results/Findings

It seems like you're asking for the results of the data analysis project described in the README. The results of a data analysis project can vary significantly based on the specific objectives, data, and analyses performed. However, I can provide some general examples of what the results might include:

1. **NetLog Datamodel**: The finalized NetLog Datamodel, including sorted LogDate and LogTime, and new columns like RecordTypeName, PrevLogDate, PrevLogTime, PrevLogRecordType, and PrevDetailsData.

2. **Data Analysis Findings**: Insights and discoveries derived from the analysis, such as trends, patterns, anomalies, correlations, and relationships within the data.

3. **Visualization Outputs**: Charts, graphs, and visualizations created to illustrate key findings and make complex data more understandable.

4. **Workflow Documentation**: Detailed documentation of the workflows followed during the analysis, including steps taken, tools used, and any challenges encountered.

5. **Deliverables**: Completed deliverables such as practical sheets, workflow documentation, survey results, and any other artifacts produced as part of the project.

6. **Recommendations**: Recommendations or actions based on the analysis findings, which may include suggestions for process improvements, further data collection, or decision-making.

7. **Summary and Conclusions**: A summary of the analysis results, key takeaways, and conclusions drawn from the project, highlighting its significance and implications.

These are just some examples of the possible results of a data analysis project. The specific results will depend on the goals, scope, and nature of the project. If you have specific questions about the analysis or want more detailed information, please feel free to ask!

## Contributors

1.Vishnu Priya Ashok Kumar
2.Adewale Dolapo
3.Shivangi Krishna

## Acknowledgments

Special thanks to [Team No 8] for their support and guidance throughout this project.
