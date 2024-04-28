# World Biodiversity Visualization Dashboard

## Visualization 1: Explore Animal Populations Over Time

This visualization was developed in D3 and displays animal populations on a world map. There is a slider where you can explore the distributions of animal populations over the years from 1950 to 2020. There is also an option to filter by animal class so you can better investigate the distributions of specific animal groups (especially since the fish populations dominate the overall visualization).

## Visualization 2: Explore Distributions of Animal Populations Over Time

This visualization was also developed in D3 and displays the populations of each animal class over time. The slider from visualization 1 also interacts with this visualization to create a more cohesive view over time. We also included interaction with visualization 1's filter toggle since the fish populations are so great that they dominate the other populations. This option allows you to compare all animal class population counts and also explore the specific numbers for each group. We were unable to implement a widget that allows you to select multiple categories at once as this is not currently supported by the underlying vega libraries.

## Visualization 3: Explore Wildlife Populations by Common Name Over Time

This visualization was developed in Tableau and depicts wildlife populations on the world map during the years 1960 and 2014. The populations are grouped by Common Name, which are set apart using color. Moreover, the number of animals observed in each recording is quantified using scale, or a proportionately sized encoding. The parallel nature of these two maps allows the viewer to easily compare populations across the two endpoints of the data. 

## Visualization 4: Explore How Wildlife Populations are Changing Over Time

This visualization was also developed in Tableau and portrays how wildlife populations are changing over time, using multiple horizontal bar charts. There are distinct bar charts for each Taxonomic group, and each bar chart is divided into increasing, stable, and decreasing populations. Each division in the bar chart (increasing, stable, or decreasing) is delineated by a unique color.

## Visualization 8: Explore Increase in Numbers of Animal Populations Over Time

This visualization was developed in Altair and depicts the 20 animals in the world with the greatest increase in population. This is portrayed using horizontal bar charts, where each bar chart represents a Common Name of animals in the data. The bar charts are ordered from descending percent of average relative change in size of populations, and an Altair color scheme is used to depict the magnitude in change. Moreover, a logarithmic scale and tooltip are implemented to make viewing easier for the reader.

## Visualization 9: Explore Decrease in Numbers of Animal Populations Over Time

This visualization was developed in Altair and depicts the 20 animals in the world with the greatest decrease in population. This is portrayed using horizontal bar charts, where each bar chart represents an Order of animals in the data. The bar charts are ordered from ascending percent of average relative change in size of populations, and an Altair color scheme is used to depict the magnitude in change. Moreover, a tooltip is implemented to make viewing easier for the reader.
