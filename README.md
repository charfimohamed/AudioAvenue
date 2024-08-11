# AudioAvenue - A Music Streaming Service Database

#[Report here](https://github.com/charfimohamed/AudioAvenue/blob/main/AudioAvenue%20-%20A%20music%20streaming%20service%20database.pdf)

## Project Overview

This project implements a database for AudioAvenue, a fictional music streaming service. The primary goal is to build a robust and efficient database for managing user information, a vast music catalog, and user interactions like creating and managing playlists.

The database caters to a range of user actions, including:

- **User registration and profiles:** Users can easily create accounts, choose from various subscription plans (like free or premium), and manage their personal profile information.
- **Music exploration:** A rich library of songs, albums, and artists, all categorized by genre, allows users to browse and discover new music efficiently.
- **Personalized playlists:** Users have the power to build their own playlists, adding and removing songs to craft their ideal listening experience. 


## Design and Implementation Highlights

- **Conceptual Design:** The database design starts with a clear conceptual model, represented using an Entity-Relationship (ER) diagram. This diagram visually maps out the key entities in our system (users, songs, playlists, etc.), their attributes (username, song title, playlist name, etc.), and the relationships between them (a user "creates" a playlist, a playlist "contains" songs).  This high-level design provides a strong foundation.
- **Logical Design:**  The conceptual model is then translated into a relational database schema.  This step defines the tables, columns, and data types used in the database.  Crucially, we establish primary keys to uniquely identify each record in a table and foreign keys to represent relationships between tables, ensuring data integrity.
- **Implementation:** The logical design is brought to life using SQL (Structured Query Language).  SQL scripts are written to create the tables, define constraints (e.g., ensuring data types are enforced, preventing duplicate entries where needed), and set up relationships between tables.  This implementation phase ensures the database adheres to the design specifications.
- **Data Manipulation and Queries:** A key aspect of this project is demonstrating how to interact with the database effectively.  We use SQL statements to insert sample data, giving potential users a glimpse of how information is structured.  We also craft a variety of SQL queries to retrieve specific information from the database, highlighting the flexibility and power of SQL in data manipulation.
- **Advanced Functionality with SQL:** The project goes beyond basic SQL operations by incorporating functions, procedures, and triggers.  For example, we might have a function to calculate a user's age based on their birthdate stored in the database. Procedures could be used for tasks like retrieving all songs by a specific artist or from a particular country. Triggers are implemented to maintain data integrity, such as preventing the insertion of underage users or the addition of duplicate songs to a playlist.

## Authors

- Eliot Ullmo 
- Mohamed Charfi 
- Ahmed Aziz Ben Haj Hmida
- Ghalia Bennani 
- Thibaud Bourgeois 

**Course:** Database Systems

