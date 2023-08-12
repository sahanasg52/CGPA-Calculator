# CGPA-Calculator
subjects=int(input("enter the numberof subjects:"))
total_credit_hours =0
total_weighted_grade =0

for i in range(subjects):
  print("for" ,i+1, "subjects")
  grade==input("enter the grades for the subject:")
  credit_hours =int(input("enter the hour for subjects: "))
    if grade =='A' or 'a' :
       grade_point = 4
    if grade =='B' or 'b' :
        grade_point = 3
    if grade =='C' or 'c' :
        grade_point = 2
     if grade =='D' or 'd' :
        grade_point =1
     if grade =='E' or 'e' :
         grade_point = 1
     else:
           print("Invalid input ")
      weighted_grade=grade_point * credit_hours
      total_weighted_grade += weighted_grade
      total_credit_hours+= credit_hours
      cgpa=total_weighted_grade / total_credit-hoours
      print("the cgpa is ",cgpa)
