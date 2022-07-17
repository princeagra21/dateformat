# dateformat
This is A Java Script library for to customise Date time format accordingly in multiple languages 

This is a very lightweight date format library with the purpose to help developers with Date customization. 

YYYY : for Year in 4 digits
YY: Year in last 2 digits
mmmm : month Full Name
mmm : Month short Name
mm : Month in 2 digits
dddd : Week Days full name
ddd : week days short name
dd : for the date in 2 digits
hh : Time with AM & PM


Code : 

dateformat(date)

Result : Return the date in default date format

Code: 

dateformat(date , "dddd mm YYYY")

Result :  return the date form in passing argument style 

Code: 

dateformat(date , "dddd mm YYYY" , 'hi')

Result :  return the date form in  passing format & passing language.

Code: 
dateformat(date , "My registration month mmmm and Year yyyy at hh the day was   -- dddd ")

Result :  return date in custom format 

