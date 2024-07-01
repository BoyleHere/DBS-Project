# DBS-Project
DBS Project for coursework: <br />
The Railway Reservation System aims to revolutionize the management of train schedules, passenger 
bookings, cancellations, and refunds. Administrators can seamlessly add new trains to the system, updating vital information on routes, available classes, fares, and departure dates. These crucial 
functionalities are designed to enhance efficiency and accuracy in the system's operation. Meanwhile, users 
will enjoy a user-friendly interface that empowers them to browse through many
available trains effortlessly, make reservations based on their desired boarding and destination points, and even apply 
concessions according to age criteria. Furthermore, the system ensures a hassle-free cancellation process, 
where users can easily cancel bookings and claim refunds, all within a secure and intuitive platform. With 
a focus on simplicity and functionality, this Railway Reservation System promises passengers a seamless and enjoyable
experience, ushering in a new era of railway travel convenience.

# Scope: <br />
The scope of the Railway Reservation System includes:
Implementation of a two-level system: Administrator and User.
Administrator Rights:
• Addition of trains to the database based on the running schedule.
• Inclusion of train information such as route, classes, fares, ticket availability, departure dates, etc.
• Storage and retrieval of booking information.
• Passenger tracking for scheduling purposes.
• Maintenance of records for passengers traveling on different trains, dates, and destinations.
User Rights:
• Access to view all trains in the database.
• Booking of tickets based on Boarding Point and Destination Point.
• Receipt of confirmed tickets with essential details (PNR, passenger names, ages, travel dates, etc.).
• Option for concession based on age criteria.
• Ability to cancel a ticket and claim the refund amount.
Constraints & Limitations:
Administrator Level:
• Only the addition of trains is permitted; deletion or modification is not possible.
• Each train route consists of only two stations: Boarding Point and Destination Point.
User Level:
• Cancellation results in the entire PNR being canceled.
• All passengers on a PNR must travel in the same class.
• No reservation available for any specific category.
• Only one booking allowed per user for a particular journey.
