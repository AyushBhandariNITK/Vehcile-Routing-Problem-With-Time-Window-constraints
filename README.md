Problem Spec

Rules

The problem is to minimise the cost of servicing orders using  trucks with time constraints and without exceeding the vehicle’s capacity

Trucks can only service 10 orders. Driving takes 1 hour per 20 km. A day lasts 10 hours. All trucks start at the beginning of the day (hour 0) and must return before the end (hour 10). Using a truck costs 100 and the price of fuel per km is 6.1p.

Trucks must deliver in the order's time window. Times windows start on the hour and last one hour. Trucks may arrive early and wait until the time window begins before delivering. For simplicity delivery is instant.

Data

Provided data comes in four columns: orderi_id uniquely identifies the order. x and y describe the relative location to the depot (at 0, 0) in Cartesian coordinates. time_window_start gives the start time (in hours) we can deliver from. So delivery is not permitted after time_window_start+1 To validate your solution data needs to be provided with these columns: truck_id - uniquely identify the truck that will make an order order_id - the order_id from orders.csv the truck should drive to sequence_number - the stage in the trucks journey it should travel to this order (i.e. 1 for the first order, 2 for the second order, etc.)


#K-MEANS CLUSTERING ALGORITHM

K-means clustering is the most popular clustering method and is used to develop separated clusters, so that each customer is assigned to exactly one cluster.The average complexity of kmeans algorithm  is o(knT) where n is number of samples and T is number of iterations.
Clustering or cluster analysis was mainly developed as an analysis tool for statistical data.
Two-step K-means algorithm.
In the first stage all the customers are partitioned in several clusters and then in the second stage a border adjustment algorithm is used to make the number of customers balanced between the clusters.
 Central point (depot) is set manually.   
Each object is included in the same cluster which have  similarities  and the  similarity of the object is measured by Euclidean distance


# dsa-project-vrp

To run the program follow these steps:

    1) open the project folder in the terminal 

    IF YOU ALREADY HAVE PANDAS SCIKIT-LEARN AND NUMPY ; IGNORE STEP 2

    2) install numpy,pandas and scikit-learn packages

        a)sudo apt-get install python-pip

        b)sudo pip install numpy

        c)sudo pip install pandas

        d)sudo pip install -U scikit-learn

    3) type command in terminal : python3 main.py

        it will create a text file with output // You can see the solution there.(The solution is near-optimal)
    
IF YOU WANT TO VALIDATE THE SOLUTION YOU CAN RUN validate.py
    
    4) run validate.py : python3 validate.py output.txt  
  
