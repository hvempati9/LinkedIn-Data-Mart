# LinkedIn-Data-Mart
This project demonstrates an end-to-end data pipeline built to extract, process, store, and visualize LinkedIn profile data.

# Data Extraction:
Utilized the Proxycurl API to extract LinkedIn profile information. The profile data was saved as JSON files, and associated profile images were downloaded and stored in organized local directories.

# Data Transformation & Loading:
Leveraged Pentaho Data Integration to process and clean the extracted data. The transformed data was then loaded into MySQL tables, achieving a data accuracy of approximately 99%.

# Data Visualization:
Developed an interactive Power BI dashboard that visualizes the LinkedIn profiles along with their images. The dashboard includes a search feature, allowing users to easily query profiles by name.

This pipeline showcases the integration of API-driven data extraction, ETL processing, relational database storage, and business intelligence for user-friendly data exploration.