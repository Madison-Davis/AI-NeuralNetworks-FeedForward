# Neural Networks
# Part 1: Feed Forward on Aviation Pricing
See code for implementation.  More details shown below:</br>

Loss function after standardization and ~20 epochs: ~0.07

Dataset source: https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction

Data descripiton: 
Dataset contains information about flight booking options from the website Easemytrip for flight travel between India's top 6 metro cities. There are 300261 datapoints and 11 features in the cleaned dataset.
Features:
The various features of the cleaned dataset are explained below:
1) Airline: The name of the airline company is stored in the airline column. It is a categorical feature having 6 different airlines.
2) Flight: Flight stores information regarding the plane's flight code. It is a categorical feature.
3) Source City: City from which the flight takes off. It is a categorical feature having 6 unique cities.
4) Departure Time: This is a derived categorical feature obtained created by grouping time periods into bins. It stores information about the departure time and have 6 unique time labels.
5) Stops: A categorical feature with 3 distinct values that stores the number of stops between the source and destination cities.
6) Arrival Time: This is a derived categorical feature created by grouping time intervals into bins. It has six distinct time labels and keeps information about the arrival time.
7) Destination City: City where the flight will land. It is a categorical feature having 6 unique cities.
8) Class: A categorical feature that contains information on seat class; it has two distinct values: Business and Economy.
9) Duration: A continuous feature that displays the overall amount of time it takes to travel between cities in hours.
10)Days Left: This is a derived characteristic that is calculated by subtracting the trip date by the booking date.
11) Price: Target variable stores information of the ticket price.


# Part 2: LSTM on Great Expectations Textual Analysis
See code for implementation.  More details shown below:</br>
LSTM used to generate text from Great Expectations.  The first eight chapters were used for data preparation.  Full Text Data: https://www.gutenberg.org/ebooks/search/%3Fsort_order%3Ddownloads

Sample Output:

Random Sampled Text:
"wning at me over her work, 'what a questioner he is. ask no questions, and you’ll be told no lies.'"


Generated Text from Random Sampled Text:
i thought the courtering to see hot than the chatcct the coatse le alonsed the pea of the table
