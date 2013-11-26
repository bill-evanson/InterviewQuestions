For this exersice you will be provided with an example set of data that represents a lists of courses that cointains the course number, meeting days and instructor. The data is provided in the test-data.csv with the first row describing that particular field.

For this example you you will output two different JSON files (examples of the JSON files are also found in this repository):

	
* For the first file you are to ouput a list of the number of courses meeting on each day of the week by department. In this example assume that the series of letters preceeding the first semicolon in course number is the department number (eg. given ACCT:2200:0001, ACCT is the department). The example output for this example is in this repository and called TotalByDeptByDay.json. Also note for days of the week Thursday is respresented with the letter R and Sunday with the letter U.  SU for example would be Saturday and Sunday (not Sunday).  Output each day of the week for each department, even if there are no courses on that day.
	   
	   
* For the second file you are to output a list of every instructor in the file along with the total number of courses that instructor teaches. An example output for this file is found in this repository with name TotalByInst.json. There are several other rules to deal with instructor names that need to be follow.
		- Capitalize the first letter in each name
		- If the name starts with an 'O' capilize the 'O' add an ' and capilize the second letter as well
		