Problem 2.1 : 
https://www.codechef.com/learn/course/sql-intermediate/SQ00BS02/problems/GSQ66

Solution : 
select * from Arts 
union 
select * from Science;

Problem 2.2 :
https://www.codechef.com/learn/course/sql-intermediate/SQ00BS07/problems/GSQ78A

Solution :
select emp_name
from employee
union all 
select emp_name
from pt_employee


Problem 2.3 :
https://www.codechef.com/learn/course/sql-intermediate/SQ00BS06/problems/GSQ76

solution:
select f_name from fruit
intersect
select inv_name from inventory;


Problem 2.4 :
https://www.codechef.com/learn/course/sql-intermediate/SQ00BS06/problems/GSQ77

Solution:
select f_name from fruit
except
select inv_name from inventory;