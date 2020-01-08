# Communicate Data Findings Project
## by Mashael AlSaadan


## Dataset: Ford GoBike System


    The dataset contains 192082 bike trips that happended in January 2019. There are 18 Features that describe each trip in the following:

    14 Features were provided in the dataset:

        Trip Duration (seconds): Total trip's duration in the unit of time seconds
        Start Time: Trip's starting time and date
        End Time: Trip's ending time and date
        Start Station ID: The id of the trip's starting station
        Start Station Name: The name of the trip's starting station
        Start Station Latitude: The latitude of the trip's starting station
        Start Station Longitude: The longitude of the trip's starting station
        End Station ID: The id of the trip's ending station
        End Station Name: The name of the trip's ending station
        End Station Latitude: The latitude of the trip's ending station
        End Station Longitude: The longitude of the trip's ending station
        Bike ID: The id of the rented bike
        User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
        Bike share for all membership: This membership is eligible for only Bay Area residents ages 18 and older
        
    4 Features were derived from the above in the cleaning process:

        Start Day (Day of the week): The trip's starting day
        Start hour in 12-hours: The trip's starting hour in 12-hours format
        Duration in hours: Total trip's duration in the unit of time minutes
        Distance in miles: Trip's distance in the unit of miles. 


## Summary of Findings
    1. Bike trip trends and the biker types: 
        1.1. Subscriber: this type's usage demands increase on the weekdays (specially on Thursday) on 8 am and 5 pm.
        1.2. Customer: this type's usage demands increase on the weekend (Saturday) between 8 am and 6 pm.
        The above suggests that subscribers type are those who use bikes for daily school/work commute, while customers are occational riders and tourists.
        
    2. Trip duration:
        2.1. Subscribers trip's duration lasts 8-14 minutes.
        2.2. Customers trip's duration lasts 10-12 minutes.
        The results confirms the theory that we have mentioned that the majority of subscribers are workers/students and need to commute quickly. Also, It may indicate that customers 
        
    3. Bike share for all membership:
       Bike share for all membership is eligible to 18 years old residents of Bay Arena.
       3.1. 90.5% of all subscribers are subscribed to bike share for all membership.
       3.2. 9.5% of all subscribers are not members of bike share for all.
       This suggests that 9.5% of subscribers are at the age of 18 and residents of Bay Arena.

## Key Insights for Presentation

    1. Bike trip trends in unit of time and day
    2. Hourly usage during the weekday for customers and subscribers

## References
    
    “Bay Wheels,” Wikipedia, 12-Nov-2019. [Online]. Available: https://en.wikipedia.org/wiki/Bay_Wheels. [Accessed: 05-Jan-2020].
    Lyft, Inc, “System Data: Bay Wheels,” Lyft. [Online]. Available: https://www.lyft.com/bikes/bay-wheels/system-data. [Accessed: 05-Jan-2020].
    “8.1. datetime - Basic date and time types¶,” 8.1. datetime - Basic date and time types - Python 3.4.10 documentation. [Online]. Available: https://docs.python.org/3.4/library/datetime.html?highlight=weekday. [Accessed: 05-Jan-2020].
    262588213843476, “Calculate distance between latitude longitude pairs with Python,” Gist. [Online]. Available: https://gist.github.com/rochacbruno/2883505. [Accessed: 06-Jan-2020].
