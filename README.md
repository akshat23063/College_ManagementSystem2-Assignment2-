
 
 # Enhancement of Assignment - 1
 This is a modification of previous ERP-SYSTEM ,i have used  various concepts like Generic programming, 
 Object class and Exception Handling to improve the functionality of this system.



 # Implementation and New Features

1- I have implemented a feedback system using generic programming principles such as generic class and wildcards,
   this allows students to submit the feedbacks for their completed course and professors can view the feedbacks for their courses. 
   The feedback can be submitted in both, in the form of rating(Integer)  and in Text(String).

2-  I have implemented a TA class by implementing Object class property such as inheriting and using string object method like(equals) and many more.
    Here TA will implement two extra functions as compare to student in which TA can view the grades of students enrolled in his assignedCourse 
    and also assign or update the marks of students in that assignedCourse.

3- Here i have handled the robustness of the system by handling many exceptions like CoursefullException, InvalidLoginException and DeadlinePassedExceptions 
  by using try and catch Block. In CoursefullException if the enrollment_limit of any course is reached then the student cant add it to their course and 
  In InvalidLoginException if any user is entering wrong credential then the errors are handled by this function. Similarly if any student want to Drop a Course 
  after a certain Deadline then that it Handled by DeadlinePassedException.
