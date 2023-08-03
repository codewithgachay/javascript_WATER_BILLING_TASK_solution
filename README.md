"Watter billing" Home work
WATER BILLING TASK
Assignment Specifications
The program will compute and display information for a utility company which supplies water to its customers. For a specified customer, the program will compute and display the amount of money which the customer will be billed for water usage during the current billing period.

The program will prompt the user to enter three values (in the following order):

The customer's code (a character)
The customer's beginning meter reading (a positive integer value)
The customer's ending meter reading (a positive integer value)
It will then process that customer information and display the results. The program will continue to process customers ◊until the user enters an invalid customer code.

The program will compute the gallons of water used by the customer during the current billing period. The meter is read by a representative of the utility company at the start and at the end of the billing period, and the readings are taken from a meter which has nine digits and records tenths of a gallon.

The program will compute the amount of money that the customer will be billed, based on the customer's code and water usage, using the following information.

Code 'r' (residential):

 $5.00 plus $0.0005 per gallon used
Code 'c' (commercial):

 $1000.00 for 4 million gallons or less, and $0.00025 for each additional gallon used
Code 'i' (industrial):

 $1000.00 if usage does not exceed 4 million gallons; 
 $2000.00 if usage exceeds 4 million gallons but does not exceed 10 million gallons; 
 and $2000.00 plus $0.00025 for each additional gallon if usage exceeds 10 million gallons.
For each customer, the program will display a summary with the following information:

The customer's code
The customer's beginning meter reading
The customer's ending meter reading
The gallons of water used by the customer
The amount of money billed to the customer
Assignment Notes
As stated above, the meter's dial has nine digits and records tenths of a gallon. For example, assuming that the beginning reading was 444400003 and the ending reading was 444400135, then the customer used 13.2 gallons of water during the billing period.
Since the meter’s dial only has nine digits, the reading at the end of the billing period may be less than the reading at the beginning of the billing period. For example, assuming that the beginning reading was 999999997 and the ending reading was 000000005, then the customer used 0.8 gallons of water during the billing period.
The program is not required to check the user-supplied meter readings for errors. That is, you may assume that the user always enters valid meter readings (integer values between 0 and 999999999).
The amount of money billed to a customer should be displayed as a monetary value. That is, it should be displayed with a dollar sign and two fractional digits (for example, $125.00 or $43.87). Information about formatting output is on pages 201-204 of the textbook.
