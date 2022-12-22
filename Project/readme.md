# 1. Archives

The following documents are included in the folder "Hotel Booking Analysis":

- `readme.md` - This markdown will explain the main archives in the folers as well the detqls of the project, including the background, objective and an explanation of the dataset as well as the main results obtained from the model.
- `final_model.ipynb` - The Python file where the classification model is developed.
- `hotel_bookings.csv` (archive folder) - the raw dataset in a csv file.
- `model_eda.pbix` - the EDA developed for the dataset in a Power BI document.


# 2. Project Details

**Background**: This hotel booking dataset allows professionals to answer different questions related to the industry, like the best time of year to book a hotel room, the optimal length of stay in order to get the best daily rate, or to predict whether or not a hotel is likely to receive a disproportionately high number of special requests.

**Objective**: The task is to build a model that will predict the cancelations of the hote bookings in order to have a better understanding of the future demand for the hotel managers as well as a more accurate forecasting of the different services needed to provide those bookings. On the other hand, to create a complete dashboard that allows to have a clear understanding of the booking dataset that both hotels have.

**Data**: The dataset consists of information on some 119,390 bookings registrations. The dataset consisted of historic transactions between 2015 and 2017. The variable to predict will be 'is_canceled'.
These are the definitions of data points provided:

- **hotel**: Resort Hotel / City Hotel
- **is_canceled**: Value indicating if the boking was canceled (1) or not (0)
- **lead_time**: Number of days that elapsed between the entering date of the booking into the PMS and the arrival date
- **arrival_date_year**: Year of arrival date
- **arrival_date_month**: Month of arrival date
- **arrival_date_week_number**: Week number of year of arrival date
- **arrival_date_day_of_month**: Day of arrival date
- **stays_in_weekend_nights**: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
- **stays_in_week_nights**: Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel
- **adults**: Number of adults
- **children**: Number of children
- **babies**: Number of babies
- **meal**: Type of meal booked; BB = Bed Breakfast / HB = Half Board (breakfast & dinner) / FB = Full Board / Undefined - SC = no meal
- **country**: Country of origin. Categories are represented in the ISO 3155–3:2013 format
- **market_segment**: Market segment designation; TA = Travel Agents / TO = Tour Operators / Groups / Direct / Corporate
- **distribution_channel**: Booking distribution channel; TA/TO / Direct / Corporate / GDS = Global Distribution System / Undefined
- **is_repeated_guest**: Value indicating if the booking name was from a repeated guest (1) or not (0)
- **previous_cancellations**: Number of previous bookings that were cancelled by the customer prior to the current booking
- **previous_bookings_not_canceled**: Number of previous bookings not cancelled by the customer prior to the current booking
- **reserved_room_type**: Code of room type reserved. Code is presented instead of designation for anonymity reasons; A / D / E / F / G
- **assigned_room_type**: Code for the type of room assigned to the booking. Sometimes the assigned room type differs from the reserved room type due; A / D / E / F / G
- **booking_changes**: Number of changes/amendments made to the booking from the moment the booking was entered on the PMS
- **deposit_type**: Indication on if the customer made a deposit to guarantee the booking; No Deposit (no deposit was made) / Non Refund (a deposit was made in the value of the total stay cost) / Refundable (a deposit was made with a value under the total cost of stay)
- **agent**: ID of the travel agency that made the booking; 9 / NULL / 240 / 1 / 14
- **company**: ID of the company/entity that made the booking or responsible for paying the booking; NULL / 40 / 223 / 67 / 45
- **days_in_waiting_list**: Number of days the booking was in the waiting list before it was confirmed to the customer
- **customer_type**: Type of booking, assuming one of four categories; Contract (when the booking has an allotment or other type of contract associated to it) / Group (when the booking is associated to a group) / Transient (when the booking is not part of a group or contract, and is not associated to other transient booking) / Transient-party (when the booking is transient, but is associated to at least other transient booking
- **adr**: Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights
- **required_car_parking_spaces**: Number of car parking spaces required by the customer
- **total_of_special_request**: Number of special requests made by the customer (e.g. twin bed or high floor)
- **reservation_status**: Reservation last status, assuming one of three categories; Cancele (booking was canceled by the customer) / Check-Out (customer has checked in but already departed) / No-Show (customer did not check-in and did inform the hotel of the reason why)
- **reservation_status_date**: Date at which the last status was set. This variable can be used in conjunction with the ReservationStatus to understand when was the booking canceled or when did the customer checked-out of the hotel



