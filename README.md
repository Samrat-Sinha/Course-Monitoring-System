# Course-Monitoring-System


## Domain Description:

In an educational  Institute there are several courses running parallel  every day. For every course there are several batches at same/different time. Every course has a session wise/day wise schedule. It will be difficult for the Faculty Head to know the status of every batch i.e what is the session taught at each day in a batch.
So the Automated Course Monitoring System will keep the records of all the courses,batches,faculties and the daywise update for every batch. It will also help the Faculty Head to maintain the course plan .

### Types of users:

    •	Administrator.
    •	Faculty

### Role of Administrator:

    •	Login to his account
    •	 Create, Update, View Course.
    •	Create, Update, View Batch. A batch is related to a course. 
    •	Create, Update, View Faculty.
    •	Allocate faculty to a batch.
    •	Create, Update, View Course plan.
    •	View the Day wise update of every batch.
    •	 Generate Report for every batch.

### Role of Faculty:

    •	Login to his/her account
    •	View the Course Plan
    •	Fill up the day wise planner.
    •	Update his/her password.

### Admin:
    •	username
    •	password:

### Faculty:

    •	facultyid
    •	facultyname
    •	facultyaddress
    •	mobile
    •	email 
    •	username
    •	password

### Course:

    •	coursed
    •	courseName
    •	fee
    •	courseDescription

### Batch:

    •	batchId:
    •	courseId:
    •	facultyId:
    •	numberofStudents;
    •	batchstartDate
    •	duration 

### CoursPlan:

    •	planId
    •	batchId
    •	daynumber
    •	topic
    •	status: completed/pending

