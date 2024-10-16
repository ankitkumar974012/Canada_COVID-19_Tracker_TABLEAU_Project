# Canada_COVID-19_Tracker_TABLEAU_Project

Overview: 
This highly interactive COVID-19 tracker was created using Tableau to monitor the pandemic’s impact in Canada from January 2020 to January 2023. It will allows users to filter data by region and cases or deaths, providing a comprehensive view of the pandemic’s progression.

Dataset: 
The dataset includes fields for the names of Canadian provinces and territories, reporting dates, total cases, total deaths, and cases and deaths over the last seven days. Unnecessary fields were deleted to streamline the dashboard.

Topics Covered: The dashboard covers various Tableau functionalities, including:
      	Creating charts and graphs
      	Using sets, calculated fields, and parameters
      	Designing an uncluttered dashboard using sheet swapping
      	Formatting and designing a dashboard

Task Carried Out in this Project
      	Field Name and Properties Changes: Fields were renamed to reflect their data accurately, and geographic roles were assigned to enable map creation.
      	Charts:
          •	Column Charts: Show COVID-19 cases and deaths per region. Unwanted records were excluded, and running totals were corrected using calculated fields.
          •	Map Charts: Display the geographic impact of the virus. Running totals were corrected, and the charts were filtered to show accurate results.
          •	Line Charts: Show trends over time. Filters were applied to remove unwanted records and correct double counting.
      	Sheet Swapping (Creating Dynamic Charts): Sheet swapping allows users to switch between charts using a drop-down menu. This was achieved using parameters,   
        calculated fields, and dashboard containers.
      	Banner: Displays a summary of the user’s selection, including total cases, total deaths, new cases, and new deaths over the last seven days.
      	Contextual Text Element: Informs users about the results displayed, with placeholders that change based on user selections.
      	Footer: Displays the data source and the last update time. A blank calculated field was used to retrieve data source metadata.

Dashboard Creation: The dashboard was created using vertical and horizontal containers to organize the elements. Filters and parameters were applied to make the dashboard interactive.
  Dashboard Features:
      	Line Charts: Two-line charts display the trends in total COVID-19 cases and deaths over time for the selected region.
      	Map of Canada: A large map in the center illustrates the geographic impact of the virus, with circle sizes indicating the severity of cases and deaths.
      	Column Chart: On the right, a column chart shows the results for each province and territory in absolute amounts.
      	Banner: At the top, a banner provides key metrics such as total cases, total deaths, new cases, and new deaths over the last seven days.
      	Contextual Text: A text section informs users about the specific results being displayed at any given time.
  Making the Dashboard Interactive: Action filters were set up to impact the banner, contextual text element, and charts. The contextual text element was updated to reflect 
      user selections accurately.
  Formatting the Dashboard: Cosmetic changes were made to enhance the dashboard’s appearance. A calculated field was used to append “of Canada” to the contextual text     
      element when all regions were selected.

This summary highlights the key features and functionalities of the Canada COVID-19 Tracker Tableau dashboard, showcasing my skills in data visualization and dashboard design.
