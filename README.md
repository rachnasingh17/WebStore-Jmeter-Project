# WebStore-Jmeter-Project
Testscript to check the performance of Product page
Test Scenario : Step 1:User Browses the website.  
                Step 2 :search the item.
                Step3 : Add  it to cart.
Script #	Pacing between Iterations	Think Time between transactions	No of user	RampUp
Script 1	No Pacing	No Think Time (Only 1 transaction in the script)	1	1
Script 2	No Pacing 	20 seconds (Fixed)	5	5
Script 3	10 seconds (Fixed)	10 seconds (Fixed)	10	5
Script 4	10 seconds (Fixed)	10 seconds (Fixed)	15	5
