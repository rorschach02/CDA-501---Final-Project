# Politics and Vaccination in America
## Dataset and Data Description
Due to the global impact of COVID-19, vaccinations have been a hot topic in America.
The topic of politics quickly entered the vaccine conversation, and they have been tied together
ever since. We are interested in seeing if there is any connection in between the average
American’s stance on vaccination and political orientation.

To compare the two concepts, we needed to simplify how we define political orientation.
We decided to generalize the overall political views of America on a state-by-state basis. The
simplest way to do this was to use the popular vote data from the 2020 election. Each state could
then be labeled by its overall political orientation. We used the US Election 2020 dataset, which
contains the voting information for every county in America. We also looked at the major
political parties involved, as well as which states voted the most.

We will compare our findings from the election dataset with vaccination data for each
state. We used the USA COVID-19 Vaccinations dataset, which had vaccination information for
each state including the number of vaccinations distributed, the number of vaccinations actually
used, and the number of people fully vaccinated.

## Clone the Project
You need Python on your machine in order to run the project. We recommend using Python 3.8.8.

Clone the project to your local machine:

git clone https://github.com/rorschach02/CDA-501---Final-Project.git

## Setting Up Dependencies

To install dependencies run:

pip install -r requirements.txt

## Analysis 


![Total Number of Votes in Each States](https://user-images.githubusercontent.com/46763031/146860006-eaf9ea07-fdf5-4514-9972-35d9cd4709e8.jpeg)

This map details the total 2020 election votes per state. As you might expect, California,
Texas, Florida, and New York submitted the most votes.


![RED and BLUE state](https://user-images.githubusercontent.com/46763031/146860051-1e1759d8-e26f-4ada-bf81-ceb99184d37f.jpeg)

This map shows the overall political orientation of each state, calculated by which party
won the majority vote in the election. The red states are republican states, and the blue states are
democratic states. The coastal states seem to be more democratic, while the middle states are
mainly republican.

![Total People Vaccinated](https://user-images.githubusercontent.com/46763031/146860087-64308a77-f20a-4474-af35-62107b4b652d.jpeg)

The map above shows the general percentage of people fully vaccinated for each state.
The darker the color the higher the percentage. The coastal states seem to have more fully
vaccinated people than the middle states. Comparing this map with the previous map, we can see
that the democratic states generally have a higher vaccination percentage than the republican
states.

![Democratic States](https://user-images.githubusercontent.com/46763031/146860376-a5a60cc9-0030-4bdc-af0b-f87bb22f756a.png)

This graph shows the relation between the total number of people fully vaccinated and
the total number of votes, explicitly for the democratic states. The slope of the graph is
essentially 0, meaning that there is no correlation between these two factors.

![Republican States](https://user-images.githubusercontent.com/46763031/146860410-8684c7a7-5b08-4873-83b0-1f73e750411f.png)

This graph shows the relation between the total number of people fully vaccinated and
the total number of votes, explicitly for the republican states. Again, the slope of the graph is
essentially 0, meaning that there is no correlation between these two factors either.

## Conclusion 
In conclusion, there is a small correlation between political orientation and stance on
vaccinations. When comparing the two choropleth maps above, it is clear that the democratic
states in general have a higher vaccination rate than the republican states. From the scatterplots,
we determined that there is no correlation between the number of people fully vaccinated and the
total number of state votes for the 2020 election. This indicates that there may still be some
hidden correlation between political views and vaccination stance that our datasets and analysis
did not support. For future studies, it would be good to find a better way to identify political
orientation. The 2020 election was a polarizing one, and individual votes do not necessarily
reflect true political stance.

## References
https://www.kaggle.com/unanimad/us-election-2020?select=president_county_candidate.csv
https://www.kaggle.com/paultimothymooney/usa-covid19-vaccinations









