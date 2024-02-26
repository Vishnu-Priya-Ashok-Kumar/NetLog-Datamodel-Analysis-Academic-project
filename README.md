# NetLog Datamodel Analysis

This repository contains the documentation and workflow details for the NetLog Datamodel analysis project. The provided dataset underwent extensive analysis to develop the NetLog Datamodel, incorporating sorting, adding new columns, utilizing VLOOKUP formulas, and various data manipulation techniques. 

## Table of Contents

1. [Project Overview](#project-overview)
2. [Deliverables and Workflows](#deliverables-and-workflows)
3. [Project Management](#project-management)
4. [Conclusion](#Conclusion)
5. [Contributors](#contributors)
6. [Acknowledgments](#acknowledgments)

## Project Overview

The primary objectives and tasks completed in this project are as follows:

- **Sorting LogDate and LogTime**: The LogDate and LogTime columns were sorted from newest to oldest, adhering to project requirements for data coherence.

- **Addition of New Columns**: Several new columns, including RecordTypeName, PrevLogDate, PrevLogTime, PrevLogRecordType, and PrevDetailsData, were added to enrich the Datamodel.

- **Data Retrieval with VLOOKUP**: VLOOKUP formulas were utilized to retrieve data for the added columns, enhancing the dataset's informational depth.

    Here VLOOKUP Formula used is
  
      `=VLOOKUP(F11,'Record Types'!$Q$7:$R$20,2,FALSE)`


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

## Conclusion

The NetLog Datamodel project involved sorting LogDate and LogTime, adding new columns, and using VLOOKUP formulas to enhance data coherence and depth. Key steps included handling #N/A values, categorizing devices, extracting text, and creating pivot tables. Deliverables included workflow documentation and various analyses. Results yielded a finalized Datamodel, insights into data trends, and actionable recommendations for further data exploration and process improvements.

## Contributors

1.Vishnu Priya Ashok Kumar
2.Adedolapo Adewale
3.Shivangi Koltharkar

## Acknowledgments

Special thanks to [Academic Team No 8] for their support and guidance throughout this project.
