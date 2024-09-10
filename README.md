![Baseball Flights](baseball_flights.png)


To the Office of Transportation at The 22nd Century Sporting League,

After the inaugural 2101 season, The League is looking for ways to optimize the game scheduling process and reduce costs. Transportation logistics are a major factor to consider during scheduling.

The primary focus areas include determining the number of jets The League needs to own and managing fuel costs for flights. To ensure The League's continued success, it is crucial to control transportation expenses effectively.

The schedule data for the upcoming 2102 season is being shared. Each row includes information about which teams will be traveling to their next set of games, the estimated departure time (based on game duration estimates), and the projected landing time.

Additionally, fuel prices paid each day during the past 2101 season are provided. Fuel prices fluctuate over time, but projecting future costs will assist with the analysis.


## The Data

### team_flights.csv

| Column     | Description              |
|------------|--------------------------|
| `team_name` | Official team name |
| `departure_datetime` | Date and Time (in UTC) when the flight will depart |
| `landing_datetime` | Date and Time (in UTC) when the flight will land |


### fuel_price.csv

| Column     | Description              |
|------------|--------------------------|
| `date` | Date when the fuel price was recorded |
| `fuel_price` | Corresponding fuel price (in $ per gallon) |


### Important Things to Know
- Assuming that the flight's average speed is 500 MPH. (So, as an example, a 2-hour flight would travel 1000 miles)
- Assuming that each team’s jet fills up with fuel equivalent to 1 gallon per mile-of-travel 
- Assuming that the jet is fueled on the day the travel departs (and thus can use the fuel price corresponding to the departure date)
