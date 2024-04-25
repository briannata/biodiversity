# World Biodiversity Visualization Dashboard

## Graph 1: Explore Animal Populations Over Time

This graph was developed in D3 and displays animal populations on a world map. There is a slider where you can explore the distributions of animal populations over the years from 1950 to 2020. There is also an option to filter by animal class so you can better investigate the distributions of specific animal groups (especially since the fish populations dominate the overall graph).

## Graph 2: Explore Distributions of Animal Populations Over Time

This graph was also developed in D3 and displays the populations of each animal class over time. The slider from graph 1 also interacts with this visualization to create a more cohesive view over time. We also included interaction with graph 1's filter toggle since the fish populations are so great that they dominate the other populations. This option allows you to compare all animal class population counts and also explore the specific numbers for each group. We were unable to implement a widget that allows you to select multiple categories at once as this is not currently supported by the underlying vega libraries.

## Graph 5: Explore Numbers of Species and Populations Over Time

This graph was developed in Altair and shows the increase in the number of populations and species over time. This graph is interactive and has a tooltip to help further explore individual data points.