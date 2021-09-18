# Bike Share Comparison - New York and San Francisco
Master of Applied Data Science - Milestone I Project (Bike Share Comparison)
Members: Tia Burton, Zealand Cooley, Kendall Dyke
Start date: August 2nd, 2021
Completed: September 20, 2021 (Projected)

### Additional Links
[DeepNote.org](https://deepnote.com/project/Sprint-1-SIADS-591-592-nur8H1J-Rx2AfQsbDIHpwg/%2FBikeShareNotebook.ipynb)

## Assets
This github repository helped maintain early versions of our notebooks. In the second month of this project, our work transitioned from individual notebooks to a DeepNote.com environment. Given the added functionality of Big Query and GitHub integrations, we found this new tool to be useful in delivering our exploratory data analysis.

## Introduction
Transportation options are continually advancing in the United States and around the world. There are self-driving cars, high-speed trains, ride-sharing apps, and other major improvements to travel in the last couple of decades. Gathering information on travel behaviors and accessibility can be very useful in many regards; it could help to better understand where inequalities lie in a municipality, how travel trends change throughout time as advancements take place, and potentially predict future travel behaviors to better plan for them. For this project, we decided to focus our research on one main type of transportation and explore the data of the city bikeshare programs available for San Francisco and New York City. 

Our goals for this project include discovering trends in riding behaviors in 2017, exploring the relationship between these trends and the demographics of riders, and comparing the results between the two cities. We also looked at the results for an available travel-related survey for each city and used it to better understand how people view their own travel behaviors and, where we could, see how they feel about the bikeshare program available to them. We developed this project through visual exploration, statistical testing, and summarizations.

We believe that this project is a potential stepping stone for future projects with wider scopes for their impacts. As the report walks through our findings, we hope that it inspires other researchers to further investigate bikeshare programs in other cities around the world, and even potentially expand to other modes of transportation. The more information available, the better prepared we’ll be as new travel avenues develop and existing ones advance.

## Future Directions
We invite others interested in bike share analysis to leverage our data source findings and visualizations to jump start their work. Below are a few suggested ways this project could evolve.

In this exploratory data analysis, the number of rides by user type, average ride times, and destination-based ride maps helped us infer the scale of a bikeshare program in comparison to one another and where rides were most densely populated. After we concluded that there was a possible need for more stations, we brainstormed a few metrics that would provide more features to a model. Those metrics include number of bikes remaining at the station and the average rolling average time there has been no bikes available for use.

During this first phase of the project, our analysis revealed some infrastructural gaps in the data. The rides tables from San Francisco and New York lend themselves well to a machine learning problem as they both contain large amounts of relatively complete data and the team was able to find relative trends that’d support this future approach. The machine learning portion of this project would include building a model that utilizes ride trends and the distance between the stations to find the most appropriate latitude-longitude pair that would enable more rides for riders who often find an empty station or where a station might not currently be available.

In the culminating phase, we’d perform software and tool development before ingesting more data for a global expansion. We intend to continue serving bikeshare programs around the world. Nonetheless, that work starts with developing software and tools that city officials and other interested parties could utilize or access via the web. Leveraging Power BI would be a great way to share this analysis with others as it allows data savvy individuals to curate KPIs, visualizations, and maps together to distribute to others through a web application. It would also be necessary to create both a python package and an API for ease of use and integration to existing applications. Once our tools and software are complete, we imagine pursuing a strategic partnership, like with Bike Share Research, would provide the team with more open source data to integrate into our current systems. That’d enable the team to offer our services around the world.

