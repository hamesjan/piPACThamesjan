This experiment is designed to measure the cummulative RSSI values for 6ft apart at tx power of 4 for 10 minutes
We will be using this baseline as the threshold for which we can compare other times and other cummulative RSSI values to make a model that describes the relationship between the time and
distance needed for the too close for too long protocol.

Control Variable: Rasberry Pis, TX power, environment.
Environment: Setting up two rasberry pis with their antennas facing toward each other. We are doing this experiment in my bedroom, with one rasberry pi on one bedpost and one rasberry pi is on a 
little makeshift shelf that is approximately 6ft apart from the other pi. there are walls on all 4 sides of the pi. The scanner is on wooden material, and the other pi is on paper material.

In this experiment, we will be measuring distance, time, and accumulated RSSI for us to make the model.

The environment might play a big factor in our data, however we will have to do.



For this experiment, we will be converting each RSSI value from dbm to Power ( mW ).
To calculate the accumulated power, we will take the sum of the entire column for power.
Each received signal will be converted into mW.

The threshold for "2 close for 2 long" will be measured by averaging the 
accumulated power for all 10 trials.


