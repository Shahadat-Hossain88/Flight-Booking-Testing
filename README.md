Flight-Booking-Testing

Link=> https://edgepnt.testrail.io/index.php?/runs/view/3&group_by=cases:section_id&group_order=asc

using Testrail Tools.



Rewuirements:
Flat rate for flights less than 500 miles = 100

1.calculate cost based on distance and departure date for flights between 500 and 1000 miles

	10 cents per mile if departing within 7 days
	8 cents per mile if departing within 30 days
	6 cents per mile if departing within 90 days

2.calculate cost based on distance, departure date, and service class for flights over 1000 miles

	30 cents per mile if departing within 7 days
	25 cents per mile if departing within 30 days
	20 cents per mile if departing within 90 days

3.Seat Class

	not Applicable Economy class
	double the cost for Business class
	triple the cost for First class

4.Additional Cost for Extra Baggage: maximum 50kg

	For flights less than 500 miles, there is no additional cost for extra baggage.
	For flights between 500 and 1000 miles, the cost for extra baggage is $25 per kg.
	For flights over 1000 miles, the cost for extra baggage is $50 per kg.

