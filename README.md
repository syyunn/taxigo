# taxigo

### Goal 
To predict taxi demand at certain time and location

### Why
For taxi pre-allocation in business aspect 

### How
Model the complex spatial dependencies and temporal dynamics

### Data Shapes

    demand      time                 location 
    2           1300hrs/20190419     37.47/126.93
    4           1100hrs/20190420     37.47/126.93
    [?] (required to predict) w/ time/location query 

### Previous Works 

     ARIMA / KalmanFiltering 
     study traffic time series for each `individual` location
     
### Recent Trends 

    - Started taking into account spatial information 
      (e.g., adding regularizations on model similarity for nearby locations)
      
    - Added External context information 
    (e.g., adding features of venue information, weather condition, and local events)
    
### 