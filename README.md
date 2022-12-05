# WebStore-Jmeter-Project
Created the testscript to check the performance of Home Page and Product page of "https://www.webstaurantstore.com/outlet.html"
Test Scenario : Step 1: User Browses the website.  
                Step 2: Search the item.
                Step 3: Add it to cart.
Script #	Pacing between Iterations	Think Time between transactions	No of user	RampUp
Script 1	No Pacing	No Think Time (Only 1 transaction in the script)	1	1
Script 2	No Pacing 	20 seconds (Fixed)	5	5
Script 3	10 seconds (Fixed)	10 seconds (Fixed)	10	5
Script 4	10 seconds (Fixed)	10 seconds (Fixed)	15	5

Uploaded the "Websore_outlet.jmx" file which contain the jmeter script for testing the applocation.
Uploaded the csv file "ItemDetails.csv" contains the product# and Description. It is used in script to randomly use product number during the iteration.
Uploaded the WebStore Performance Report which contains the performance observations and result.

