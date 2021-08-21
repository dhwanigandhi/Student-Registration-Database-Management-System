# Student-Registration-Database-Management-System
## Project Summary
Navlakhi® Tutorials is an educational service running for the past 25 years in Mumbai, India. It is a renowned organization in the Education Sector specializing in Engineering courses. There are approximately 100 students who enroll in the tutorials every semester. As of today, there is no automated database management system to store the details of the incoming students. 

Currently the process of registering is manual. The data is stored in various Excel Spreadsheets. The students need to come over or call to register themselves. To know which subjects are available for the current semester they must do the same.

A relational database will be able to store the data of the incoming students who want to register for the tutorials automatically and in a logical format. There will be a student entity storing information about the student registering for the tutorials. The data stored would consist of his name, phone number, the college he goes to, the branch he is studying in and his email. The database would include a table of all those colleges across Mumbai selected by the tutorials and the respective branches available in those colleges. The database will also include all the subjects available in each branch at each college. We create another entity to store the semester when the subject is available. This is then connected with the student username so that we can know about all the subjects the student has ever taken up in the tutorials. We have also created a payment entity to keep a track of the payment made by each student for an individual subject. 

Data can be drawn out of the system easily regarding who is registered for which subject. The students can now register for the course without any difficulty.

The users of the system are categorized into two groups:
1.	Students: Enroll for the tutorials and register for subjects by viewing the available subjects.
2.	Admin: Enters payment information, views reports and updates data when needed.

The following business rules were followed while developing the project.
1.	A student needs to register only once unless his/her college or branch changes.
2.	New registrations are done every six months. 
3.	If a student fails a subject and he takes up that subject at the tutorials again, he need not pay for the subject again i.e. he can continue that subject free of cost.
4.	The payment should be made for each subject individually by a student.
5.	The student registration is confirmed only once the payment is done.
