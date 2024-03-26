# 4610-Project-1
## Team Name:
61608 Group 5
## Team Members:
1. Manafie Kabir @manafiekabir
2. Avanish Thota @avanish-thota
3. Albert Sun @Glockgeta
4. Haley Ford @HaleyFord
5. Nicholas Price @nickprice347
6. Sydney Seid @sydneyseid
## Problem Description
The current scenario involves creating a relational database for a tennis club to ensure all data is properly allocated, and the business runs smoothly and efficiently. The majority of the model is centered around the entity “Members”. Members are at the forefront of the business since they determine which transactions take place, what divisions and leagues to join, what courts to reserve in conjunction with the coaches, which coaching programs to be a part of, and more. In addition to members, the club also employs a variety of general staff employees who can fulfill maintenance requests on various courts. The goal of the model is to accurately use and generate data, show the relationships between the various entities, and allow for queries to promptly be asked and solved to easily allow the analysis of data.

## Data Model
*Numbers Match Up With Our Client’s Points*
Our model is structured around a tennis club and its various entities are representative of key daily functions. The members entity is a key aspect of our model, and therefore is present in multiple different relationships. 
& 2. 
Starting with entities one and two from our client, we created a many to many relationship between members and courts. Members can reserve many courts and courts can have multiple members present on them. The many to many relationship resulted in an associative entity, court reservations. 
3.
Next, members can belong to many coaching programs and coaching programs have multiple members present in them. These two entities form an associative entity, sessions. Coaching programs and members may also at times have no sessions. Additionally, the coaching programs are led by coaches. Coaches have a one to many relationship with coaching programs, as one coach can teach many coaching programs, but a coaching program can only be led by one coach at a time. Additionally, the coaches entity has a one to many relationship with the court reservation entity as a coach can make multiple court reservations, but a reservation can only belong to one coach.  
4. 
 Members can belong to many tennis leagues, and a tennis league is made up of many members. These two entities have a many to many relationship, which results to an associative entity divisions. 
5.
The Pro Shop Inventory entity can belong to many transactions, and the transactions can consist of multiple pro shop items. These two entities resulted in an associative entity, transaction details. 
Additionally, members can make multiple transactions from the proshop, but a singular transaction can only belong to one member. 
6. & 7. 
Our general staff entity can perform maintenance on multiple courts, and each court can have multiple faculty working on its upkeep. Thus an associative entity maintenance request is created to symbolize this many to many relationship.
<img width="660" alt="finalGroupDM" src="https://github.com/manafiekabir/4610-Project-1/assets/163012589/11b1af97-7dd3-49f3-8edf-e3f2ada6a5ba">

## Data Dictionary

## Queries:
## Database Information:
