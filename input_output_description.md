# Input/Output Description
- Input: The client should provide the following formatted data in CSV file (1 required).Below are the details for each CSV file.
- **_vendor_list.csv_** (*REQUIRED*): 
    
| Column               | Column Required? | Meaning                                     |
|----------------------|------------------|---------------------------------------------|
| Vendor_Name_raw      | Y                | Unique vendors' name                        |
| Spend_Amount         | N                | clients' expense on these vendors           |

	
- Output: a JSON list of objects contaning, for each record in the original orderthe following fields:
    - Vendor_Name_raw: (input) unique vendors' name
    - Spend_Amount: clients' expense on this vendor 
    - Vendor_Group_Name: (final output) group name which this vendor belongs to 
 - Reference file: sample.csv.out	
	
