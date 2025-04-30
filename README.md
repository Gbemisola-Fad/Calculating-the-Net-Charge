# Calculating-the-Net-Charge
 Calculating the Net Charge of Insulin by Using Python Lists and Loops

In this lab, I did:

1. Created a dictionary of pKa values (which indicate the strength of an acid) that will be used in the net charge calculations
2. Used the count() method to get a count of amino acids
3. Used a while loop to calculate the net charge of insulin from pH 0 to pH 14

The dictionary pKa_values contains the pKa values for the amino acids that can contribute to the charge of insulin.

The insulin_sequence is a string representing the sequence of insulin. 
The dictionary comprehension counts the occurrences of each amino acid.

The while loop iterates through pH values from 0 to 14. For each pH, it calculates the net charge based on the pKa values and the counts of each amino acid. 
If the pH is below the pKa, the amino acid is positively charged; if above, it is negatively charged.

Finally, the results are printed, showing the pH and the corresponding net charge.
You can modify the insulin_sequence and the pKa_values as needed to fit your specific requirements.

This project calculates the net charge of the insulin protein at varying pH levels, ranging from 0 to 14, by analyzing the contributions of specific amino acids based on their pKa values.

The project utilizes Python, leveraging dictionaries to store pKa values and lists to represent the insulin sequence. 
It employs a while loop to iterate through pH values, calculating the net charge by counting the occurrences of relevant amino acids and determining their charge state based on the relationship between pH and pKa. 
The results are then printed in a clear format, showing the net charge at each pH level.


