# Railway-Database-Management-System-project-using-SQL
## Contents
   
[Introduction](#introduction)

[Project Description](#project-description)

[Assumptions](#assumptions)

[Objectives of Railway Management](#objectives-of-railway-management)

[ER Diagram](#er-diagram)

[Schema](#schema)

[Queries](#queries)

[Conclusion](#conclusion)

## Introduction

The Indian Railways is one of the world's major railway networks, moving millions of passengers daily. 
An efficient database management system is crucial for managing a large transportation system. 
This system consists of a database, database engine, and database schema to ensure concurrency, security, data integrity, and consistent administration methods. 
Automating the procedure eliminates loopholes in manual record-keeping and increases data processing speed. 
The web-enabled system allows consumers to inquire about trains between stations, reducing disputes and issues with railway reservation systems.

## Project Description

The project involves developing a database with necessary information about the railway reservation system. 
It helps in facilitating the passengers to know about the train schedules and details about passenger seat number, coach number etc.
This project aims to create a database with information about trains, stations, and passengers, which could eventually be used to answer passenger queries. 

## Assumptions

- The number of trains selected is restricted to 5 only
- All the trains start from Delhi only
- The dates of the journey are only 3 days in March
- The in-between stations are not considered
- Ticket cancellation is not taken into consideration

## Objectives of Railway Management

- Create a database containing station, train, passenger, and ticket information. This helps with compliance and audits.
- Providing real-time access to train timings and coach numbers improves railway efficiency and accuracy.  
- Getting information about the passengers and trains they have booked. 
- Getting information about the trains available between the time of interest of passengers.
- Getting information about the number of passengers travelling from a particular train.

## ER Diagram

<img width="1214" height="682" alt="image" src="https://github.com/user-attachments/assets/4ada0eb8-0ac6-4bf4-b4a4-afa6a8f911db" />

## Schema
   
   <img width="1217" height="685" alt="image" src="https://github.com/user-attachments/assets/85086154-3724-4171-9e7c-c426c47fb77d" />
 Trains
 <img width="653" height="158" alt="train" src="https://github.com/user-attachments/assets/d209daa7-a85c-43e1-af44-55cfde54c557" />

Schedule
<img width="777" height="152" alt="schedule" src="https://github.com/user-attachments/assets/34658912-1b0d-490f-8150-f504c5a00c3c" />

Station
<img width="765" height="157" alt="station" src="https://github.com/user-attachments/assets/2aa9cbaa-b724-4203-b52c-f74cb1302dfe" />

Passenger
<img width="505" height="280" alt="passengers" src="https://github.com/user-attachments/assets/e6dfe3c3-1cb0-42f4-9f79-a6b77f686884" />

Ticket
<img width="1431" height="273" alt="ticket" src="https://github.com/user-attachments/assets/6ea16230-8399-4009-b3bd-ff1b3e1cb203" />

## Queries

queries can be found in the following doc.
[Queries.docx](Queries.docx)
   
## Conclusion

- Our project aims to organize the railway database system to benefit both passengers and the Railway department.
- The project enables passengers to easily find available trains for travel within a specified time range.
- The system maintains records of the number of passengers travelling on respective trains,along with the details of the seats and coaches allotted to them.
- This organized database system helps to reduce manual errors and ensures data accuracy,  leading to efficient management of the railway system.
- Overall,this project aims to provide a more convenient and hassle free experience for both  passengers and the Railway department.

