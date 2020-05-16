Feature: free Crm Login feature
description ::: 
#
#Scenario: Free Crm Login Page
#Given user is in the login page
#When Verify the title of the login page 
#Then user enters "krishna" and "puttu"
#Then user clicks on login button
#And User is on home page 



Scenario Outline: Free Crm Login Page
Given user is in the login page
#simple test data (number of string )
When Verify the "krishna" of the login page
#example  (it executes two time based on the test data in the Example )
Then user enters "<username>" and "<password>"
#DataTable ##Tables (need use Datatable  row and get in order to get the cell values  )
Then user clicks on login button
|naveen|XXXXX|
|Naveen1|XXXXX1|
#Table with map (need use Datatable using Map it can used for fill the form  )
And User is on home page 
|name|phone|age|salary|
|krishna1|987345|234|4324412|
|krishna2|987346|233|4324423|
|krishna3|987347|232|4324445|
|krishna4|987348|231|4324455|
Examples:
|username|password|
|Krishna|Puttu|
|naveen|Tutorial|

