## Lesson 4 Homework: Command Line Chipotle

#### Submitting Your Homework

* Create a Markdown file that includes your answers **and** the code you used to arrive at those answers.
* Add this Markdown file to a GitHub repo that you'll use for all of your coursework.
* Submit a link to your repo using the homework submission form listed just below the course schedule on the class repo on the main README.md page. [(submission form)](https://docs.google.com/forms/d/e/1FAIpQLSewUusL-wsvGaqetR3PhKGmAWOqeMCJ28dq2S0dvplKors3yg/viewform)

#### Command Line Tasks

1. Look at the head and the tail of **chipotle.tsv** in the **data** subdirectory of this repo. Think for a minute about how the data is structured. What do you think each column means? What do you think each row means? Tell me! (If you're unsure, look at more of the file contents.)
   * *A: Each Column represents a dimension of the order.  Each row represents an item in an order*

2. How many orders do there appear to be?
   * *A: 1,834 orders total*

3. How many lines are in this file?
   * *A: 4,623 lines total*

4. Which burrito is more popular, steak or chicken?
   * *A: chicken (553 orders vs. 368)*
   
5. Do chicken burritos more often have black beans or pinto beans?
   * *A: Black Beans (282 orders vs. 105)*

6. Make a list of all of the CSV or TSV files in the [our class repo] (https://github.com/ga-students/DS-SEA-07). repo (using a single command). You will be working on your local repo on your laptop.  Think about how wildcard characters can help you with this task.
  * *Command: $ find -name '*.csv' -o -name '*.tsv'*
    *Files:
    ./data/airlines.csv
./data/Airline_on_time_west_coast.csv
./data/bank-additional.csv
./data/bikeshare.csv
./data/chipotle.tsv
./data/citibike_feb2014.csv
./data/drinks.csv
./data/drones.csv
./data/hitters.csv
./data/icecream.csv
./data/imdb_1000.csv
./data/mtcars.csv
./data/NBA_players_2015.csv
./data/ozone.csv
./data/pronto_cycle_share/2015_station_data.csv
./data/pronto_cycle_share/2015_trip_data.csv
./data/pronto_cycle_share/2015_weather_data.csv
./data/rossmann.csv
./data/rt_critics.csv
./data/sms.tsv
./data/stores.csv
./data/syria.csv
./data/time_series_train.csv
./data/titanic.csv
./data/ufo.csv
./data/vehicles_test.csv
./data/vehicles_train.csv
./data/yelp.csv
*

7. Count the approximate number of occurrences of the word "dictionary" (regardless of case) across all files of [our class repo] (https://github.com/ga-students/DS-SEA-7).
8. **Optional:** Use the the command line to discover something "interesting" about the Chipotle data. Try using the commands from the "advanced" section!
 
