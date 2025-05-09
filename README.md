# print first and last date of mounth
import calendar 
from datetime import date
year= 2025
month= 5
fday= date(year, month, 1)
lday= date(year, month,  calendar.monthrange(year, month)[1])
print("Firstday:", fday.strftime("%A, %y-%m-%d"))
print("lastday:", lday.strftime("%A, %y-%m-%d"))  
