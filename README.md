
<b>Problem Statement</b>

Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests? This hotel booking dataset can help you explore those questions! This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data.

<b>Dataset</b>: The data set is taken from kaggle, contains the real world data record of hotel bookings of a city and a resort hotel containing details like bookings, cancellations, guest details etc. from 2015 to 2017. Main aim of the project is to understand and visualize dataset from hotel and customer point of view i.e.
The columns and the data it represents are listed below:

1. **hotel** : Name of the hotel (Resort Hotel or City Hotel)

2. **is_canceled** : If the booking was canceled (1) or not (0)

3. **lead_time** : Number of days before the actual arrival of the guests

4. **arrival_date_year** : Year of arrival date

5. **arrival_date_month** : Month of month arrival date

6. **arrival_date_week_number** : Week number of year for arrival date

7. **arrival_date_day_of_month** : Day of arrival date

8. **stays_in_weekend_nights** : Number of weekend nights (Saturday or Sunday) spent at the hotel by the guests.

9. **stays_in_week_nights** : Number of weeknights (Monday to Friday) spent at the hotel by the guests.

10. **adults** : Number of adults among guests

11. **children** : Number of children among guests

12. **babies** : Number of babies among guests

13. **meal** : Type of meal booked

14. **country** : Country of guests

15. **market_segment** : Designation of market segment

16. **distribution_channel** : Name of booking distribution channel

17. **is_repeated_guest** : If the booking was from a repeated guest (1) or not (0)

18. **previous_cancellations** : Number of previous bookings that were cancelled by the customer prior to the current booking

19. **previous_bookings_not_canceled** : Number of previous bookings not cancelled by the customer prior to the current booking

20. **reserved_room_type** : Code of room type reserved

21. **assigned_room_type** : Code of room type assigned

22. **booking_changes** : Number of changes/amendments made to the booking

23. **deposit_type** : Type of the deposit made by the guest

24. **agent** : ID of travel agent who made the booking

25. **company** : ID of the company that made the booking

26. **days_in_waiting_list** : Number of days the booking was in the waiting list

27. **customer_type** : Type of customer, assuming one of four categories

28. **adr** : Average Daily Rate, as defined by dividing the sum of all lodging transactions by the total number of staying nights

29. **required_car_parking_spaces** : Number of car parking spaces required by the customer

30. **total_of_special_requests** : Number of special requests made by the customer

31. **reservation_status** : Reservation status (Canceled, Check-Out or No-Show)

32. **reservation_status_date** : Date at which the last reservation status was updated

<b>Business Objective</b> 
The business objective of this project is to undertand and visulizes key factors which are driving the bookings so that company can work on those factors

<b>Steps involved</b>
**Data Preprocessing** : 

1. Getting the dataset
2. Importing libraries
3. Loading datasets
4. Shape of the data
5. Removing duplicate
6. Null Analysis
7. Data Cleaning 
8. Correlation heatmap

**Exploratory data analysis(EDA) :** 

1.Univariate Analysis

2.Hotel wise Analysis

3.Distribution Channel Wise Analysis

4.Booking Cancellation Analysis

5.Time Wise Analysis

6.Region Wise Analysis


<b>Conclustion</b>
<ul>
<li>Around 60% bookings are for City hotel and 40% bookings are for Resort hotel, therefore City Hotel is busier than Resort hotel. Also the overall adr of City hotel is slightly higher than Resort hotel.</li>
<li>Mostly guests stay for less than 5 days in hotel and for longer stays Resort hotel is preferred</li>
<li>Both hotels have significantly higher booking cancellation rates and very few guests less than 3 % return for 
another booking in City hotel. 5% guests return for stay in Resort hotel.</li>
<li>Most of the guests came from european countries, with most no. of guest coming from Portugal.</li>
<li>Guests use different channels for making bookings out of which most preferred way is TA/TO</li>
<li>For hotels higher adr deals come via GDS channel, so hotels should increase their popularity on this channel.</li>
<li>Almost 30% of bookings via TA/TO are cancelled.</li>
<li>July- August are the most busier and profitable months for both of hotels.</li>
<li>For customers, generally the longer stays (more than 15 days) can result in better deals in terms of low adr.</li>
<ul>
  
**Solution to Business Objective**
<ul>
<li>Majority of the hotels booked are city hotel. Definitely need to spend the most targeting fund on those hotel.</li>
<li>We should also target months between May to Aug. Those are peak months due to the summer period.</li>
<li>Majority of the guests are from Western Europe. We should spend a significant amount of our budget on those area.</li>
<li>Given that we do not have repeated guests, we should target our advertisement on guests to increase returning guests.</li>
</ul>

