# Data-Analysis-End-to-End-Project-

- hotel: 
The datasets contains the booking information of two hotel. One of the hotels is a resort hotel and the other is a city hotel.

City Hotel
66%
Resort Hotel
34%
- is_canceled: 
Value indicating if the booking was canceled (1) or not (0).

- lead_time-
Number of days that elapsed between the entering date of the booking into the PMS and the arrival date.

- arrival_date_year-
Year of arrival date

- arrival_date_month-
Month of arrival date with 12 categories: “January” to “December”

- arrival_date_week_number-
Week number of the arrival date

- arrival_date_day_of_month-
Day of the month of the arrival date

- stays_in_week_nights-
Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel BO and BL/Calculated by counting the number of week nights

- adults-
Number of adults

- children-
Number of children

- babies
Number of babies

- meal
BB – Bed & Breakfast

- country
Country of origin.

- market_segment
Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”

- distribution_channel
Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”

- is_repeated_guest
Value indicating if the booking name was from a repeated guest (1) or not (0)

- previous_cancellations
Number of previous bookings that were cancelled by the customer prior to the current booking

- previous_bookings_not_canceled
Number of previous bookings not cancelled by the customer prior to the current booking

- reserved_room_type
Code of room type reserved. Code is presented instead of designation for anonymity reasons

- assigned_room_type
Code for the type of room assigned to the booking. Sometimes the assigned room type differs from the reserved room type due to hotel operation reasons (e.g. overbooking) or by customer request. Code is presented instead of designation for anonymity reasons

- booking_changes
Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation

- deposit_type
No Deposit – no deposit was made; Non Refund – a deposit was made in the value of the total stay cost; Refundable – a deposit was made with a value under the total cost of stay.

- agent
ID of the travel agency that made the booking

- company
ID of the company/entity that made the booking or responsible for paying the booking. ID is presented instead of designation for anonymity reasons

- days_in_waiting_list
Number of days the booking was in the waiting list before it was confirmed to the customer

- adr
Average Daily Rate (Calculated by dividing the sum of all lodging transactions by the total number of staying nights)

- required_car_parking_spaces
Number of car parking spaces required by the customer

- customer_type
Group – when the booking is associated to a group; Transient – when the booking is not part of a group or contract, and is not associated to other transient booking; Transient-party – when the booking is transient, but is associated to at least other transient booking

- total_of_special_requests
Number of special requests made by the customer (e.g. twin bed or high floor)

- reservation_status
Check-Out – customer has checked in but already departed; No-Show – customer did not check-in and did inform the hotel of the reason why

- reservation_status_date
Date at which the last status was set. This variable can be used in conjunction with the ReservationStatus to understand when was the booking canceled or when did the customer checked-out of the hotel

# Data Analysis Project Steps:
1. Create a Problem Statement.
2. Identify the data you want to analyze.
3. Explore and Clean the data.
4. Analyze the data to get useful insights.
5. Present the data in terms of reports or dashboards using visualization.


# Business Problem
In recent years, City and Resort hotel have seen high cancellation rates. Each hotel is now dealing with a number of issues as a result, Including fewer revenues and less than ideal hotel use. Consequently, lowering cancellation rates is both hotels is primary goal in order To increase their revenue and for us to offer through business advice to address their problem.
The analysis for hotel booking cancellation as well as other factors that have no bearing on their business and yearly revenue generation Are the main topic of the report

# Assumptions 
1. No unusual occurrences between 2005 and 2017 will have a substantial impact on the data used 
2. The information is still current and can be used to analyse a hotels possible plan in an efficient manner 
3. There are no unanticipated negative to the hotel employing any advised technique 
4. The hotel are not currently using any of the suggested solution 
5. The biggest factor affecting the effectiveness of earning income is booking cancellation 
6. Clients make reservations the same year they make cancellations


# Research Questions 
1. What are the variables that affect the hotel reservations cancellation?
2. How can we make hotels reservations cancellation lower?
3. How will hotels be assisted in making and promotional decisions?


# Hypothesis 
1. More cancellations occur when price are higher 
2. When there is longer waiting list, customers tend to cancel more frequently 
3. The majority of clients are coming from offline travel agents to make their reservations


# Analysis and finding 
1. The accompanying bar graph shows the percentage of reservations that are cancelled and those that are not. It is obvious that there are still a significant number of reservations that have not been cancelled. There are still 37% of clients who cancelled their reservation, which has a significant impact on the hotels earnings 

2. In comparison to resort hotels, the city hotels have more bookings. It’s possible that resort hotels are more expensive than those of city hotels

3. The line graph above shows that, on certain days, the average daily rate for a city hotel is less than that of a resort hotel and on other days, it even less. It goes without saying that weekends and holidays may see a rise in resort hotel rates 

4. We have developed the grouped bar graph to analyse the months with the highest and lowest reservation levels according to reservation status. As can we see, both the numbers off conformed reservations and the number of cancelled reservations are largest in month of August. Whereas January is the month with the most cancelled reservations.

5. This bar graph demonstrates that cancellations rate is directly proportional to hotel price. 

6. Now, let ‘see which country has the highest reservations cancelled. The top country is Portugal with around 70% cancellation rate

7. Let see, from which market segment hotels are getting customers. 
Market segment	Number of reservation 
- Online TA	56402
- Offline TA/TO	24159
- Groups	19806
- Direct	12448
- Corporate	5111
- Complementary	734
- Aviation	237

Market segment	Percentage of reservation 
- Online TA 	47.43
- Offline TA/TO	20.31
- Groups	16.65
- Direct 	10.46
- Corporate	4.29
- Complementary	0.61
- Aviation 	0.19
 
Cancellation as per market segment in percentage 
Market segment 	Cancellation rate in percentage 
- Online TA	46.96
- Groups	27.39
- Offline TA/TO	18.74
- Direct	4.34
- Corporate	2.21
- Complementary	0.20
- Aviation	0.11


8. As seen in the graph, reservations are cancelled when the average daily rate is higher then when it is not cancelled. So it is proved that, cancellations rate is directly proportional to hotel price. 

# Suggestion 
1.	Cancellations rate is directly proportional to hotel price. In order to arrest the cancellations of reservations, hotel need to work in pricing strategies and try to lower the specific hotels based on locations. As well as they can provide strategic discount to the customers 
2.	As per bar graph, cancellation rate is higher at the resort hotels in comparison to city hotel.so hotel may provide strategic discount based on locations, weekends as well as holidays.
3.	In month on January, hotel can start their strategic marketing campaign, this month shows highest cancellation rate compare to rest of months 
4.	There is also need to increase the quality of hotel and services, mainly in Portugal to reduce the cancellation rate 
