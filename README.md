# Travel Expenses

Create a GUI application that calculates and displays the total travel expenses for a business trip. The user must provide the following information:
- Number of days on the trip
- Amount of airfare, if any
- Amount paid for meals, if any
- Amount of car rental fees, if any
- Number of miles driven, if a private vehicle was used
- Amount of parking fees, if any
- Amount of taxi charges, if any
- Conference or seminar registration fees, if any
- Lodging charges, per night
	
The company reimburses travel expenses according to the following policy:

- $37 per day for meals
- Parking fees, up to $10.00 per day
- Taxi charges up to $20.00 per day
- Lodging charges up to $95.00 per day
- If a private vehicle is used, $0.27 per mile driven

The application should calculate and display the following:

- Total expenses incurred by the business person
- The total allowable expenses for the trip
- The excess that must be paid by the business person, if any
- The amount saved by the business person if the expenses were under the total allowed

The application should have the following functions:

Method|Description
---|---
CalcMeals 				| Calculates and returns the amount reimbursed for meals.
CalcMileage 			| Calculates and returns the amount reimbursed for mileage driven in a private vehicle.
CalcParkingFees 		| Calculates and returns the amount reimbursed for parking fees.
CalcTaxiFees 			| Calculates and returns the amount reimbursed for taxi charges.
CalcLodging 			| Calculates and returns the amount reimbursed for lodging.
CalcTotalReimbursement 	| Calculates and returns the total amount reimbursed.
CalcUnallowed 			| Calculates and returns the total amount of expenses that are not allowable, if any. These are parking fees that exceed $10.00 per day, taxi charges that exceed $20.00 per day, and lodging charges that exceed $95.00 per day.
CalcSaved 				| Calculates and returns the total amount of expenses under the allowable amount, if any. For example, the allowable amount for lodging is $95.00 per day. If a business person stayed in a hotel for $85.00 per day for five days, the savings would be $50.00.

Input validation: Do not accept negative numbers for any dollar amount or for miles driven in a private vehicle. Do not accept numbers less than 1 for the number of days.
