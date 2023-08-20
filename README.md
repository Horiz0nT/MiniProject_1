MiniProject №1

Hey. This is my first miniproject that I did ages ago, and I've decided to upload it to GitHub.

In this MiniProject I'll analyze some hotel bookings data.

Here is the list of problems that I wanted to solve:

- Import the pandas library as pd. Download the dataset bookings.csv with the separator ;. Check the size of the table, the types of variables, and then display the first 7 lines to view the data.
- Bring the column names to the lower case and replace the spaces with the lower underscore sign.
- Which country users made the most successful bookings? Indicate the top 5.
- How many nights hotels of various types are booked on average?
- Sometimes the type of room received by the client (assigned_room_type) differs from the originally booked (reserved_room_type). This can happen, for example, due to overbooking. How many similar observations were found in the dataset?
- Analyze the dates of the planned arrival. – What month was the most successful reservation in 2016? Has the most popular month changed in 2017? – Group the data by year and check for which month the City Hotel type reservations were canceled most often in each of the periods.
- Look at the numeric characteristics of the three variables: adults, children and babies. Which one has the highest average value?
- Create a total_kids column by combining children and babies. For hotels of what type was the highest value of the variable?
- Create a variable has_kids that takes True if the client indicated at least one child (total_kids) when booking, otherwise – False. Consider the ratio of the number of departed users to the total number of customers, expressed as a percentage of (churn rate). Indicate among which group the indicator is higher.

Here is a data description: 

The following variables are available:

- Hotel – hotel type (City Hotel or Resort Hotel)
- Is canceled – the reservation was canceled (1) or not (0); not canceled considered successful
- Lead time – number of days elapsed between the date of booking and the date of arrival
- Arrival full date – full arrival date
- Arrival date year – year of arrival
- Arrival date month – month of arrival
- Arrival date week number – arrival week number
- Arrival date of month – day of arrival
- Stays in weekend nights – number of weekends (Saturday or Sunday), which the guest booked for hotel accommodation
- Stays in week nights – the number of days (Monday through Friday) that the guest booked for hotel accommodation
- Stays total nights – total number of booked nights (the sum of the two previous columns)
- Adults – number of adults
- Children – number of children
- Babies – number of babies
- Meal – selected power type
- Country – customer country of origin
- Reserved room type – type of reserved room
- Assigned room type – type of room (may differ from the booked)
- Customer type – booking type
- Reservation status – value of the last status of the reservation: Canceled - was canceled by the client; Check-Out - the client has registered but has already left the hotel; No-Show - the client has not registered and informed the hotel about the reason
- Reservation status date – status update date


The project itself you'll find in [GH_Miniproject_1](https://github.com/Horiz0nT/MiniProject_1/blob/main/GH_Miniproject_1.ipynb)

The DataSet is the [bookings.csv](https://github.com/Horiz0nT/MiniProject_1/blob/main/bookings.csv)
