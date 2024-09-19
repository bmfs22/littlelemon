# Database Engineering Capstone
Repository for the Meta Database Engineering Capstone Project

# Requirements
* Version control to ensure the integrity of the code
* Front-end/User Interface for Little Lemon staff to be able to interact intuitively with the database

# Steps
1. Set up a GitHub repository
2. Set up a MySQL Server connection and create a database
3. Sketch the conceptual, logical, and physical models of the database. The physical model can and should be drawn using MySQL Server since it can be forward-engineered into the queries for creating the database tables. The conceptual and logical models, on the other hand, necessitate another diagramming software, such as draw.io, excalidraw and the like. 
4. Review the physical model to ensure that it conforms to the normal form requirements and that the data types, constraints, and keys are all set up correctly and linked to one another. When creating the tables, also note that you must create them in the order of dependence, that is, start with the tables whose fields do not require data from other tables to be complete. This is usually the case of the supporting tables that contain categorical tables used in the other tables.
5. Implement the physical model.
6. Design views (virtual tables) with summarized data based on the users' data access requirements.
