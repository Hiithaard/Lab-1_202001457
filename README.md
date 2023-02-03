# Lab-1_202001457

## Q1

### Functional Requirements:

1. Verify an account whenever created and grant the privileges straightaway.
2. Books can be issued only by the registered members of the LIS.
3. Send reminders to users when due date is near or if the book is overdue.
4. Accumulate a set amount of fine for any user who has overdued books.
5. Allow users to pay fine online.
6. Let the user put forth a request to re-issue a book as per their requirement.
7. Only let the librarian issue/re-issue books.
8. Don't let any user issue more than 5 books at a time.
9. Prevent a user from issuing a new book if they have an overdue book or have not cleared any fine.
10. Let any user search for a book.
11. The users should have an interface in the form of a web application to access all the functionalities.

### Non-Functional Requirements:

**1. Security:**  
The web application should run only on the institute LAN and it should have some form of encryption to store sensitive information like passwords etc and only let verified users access the application.

**2. Scalability:**  
System should be able to accomodate the ever increasing number of users.

**3. Reliable:**  
The system should perform tasks as expected and robust i.e. allow the access of functionalities as per the user roles. Student, professors and research fellows can only borrow, return, re-issue books and pay fines if any whereas Librarians have complete control over the LIS and make changes as required.

**4. Ease of use:**  
The system should have easily accessible functionalities i.e. the user interface should be user friendly and have GUI.

**5. Latency:**  
System should not take long to reflect the changes made in the LIS mainly changes pertaining the creation of new users and borrowing and returning of books.

**6. Maintainability:**  
The system designed should be easy to maintain and expand. Minor changes should not affect the overall experience and the application.


### Roles:

i) Librarian: Has complete control over the LIS i.e they can add remove users, books, manage entries, (re-)issue books, prompt users when book is overdue etc.
ii) Student: Can issue and return books during the library hours. Has access to only selected set of materials.
iii) Professors and Research Fellows: Same privileges as the student, just has access to more materials.

## Q2

### Scope:
The application can be used by people who are suffering from hearing disabilities and/or partial hearing loss.

### Functional Requirements:

1. The application should be allowed to use the microphone to register sounds to send out alerts otherwise the application would be redundant.
2. The application should send out alerts as soon as the sounds are registered.
3. The application should have the ability to send out alerts in different ways i.e. flash, vibration, sound etc.
4. The application should be able to set a threshold to give out alerts i.e. many patients may not be completely deaf and they are able to hear several sounds of a certain loudness, hence they may not need that many alerts.
5. The application should start/stop alerts as per the users requirement.


### Non-Functional Requirements:

**1. Accuracy:**  
The application should be accurate enough to identify the source of the sound.

**2. Reliability:**  
The application should not give false alerts to users.

**3. Ease of use:**  
The application should have a simple UI making it easy to use.

**4. Efficiency:**  
The application should not eat up much resources which in turn would drain the device's battery.

**5. Latency:**  
The application should give the alerts as quickly as possible so prevent any hazard.
