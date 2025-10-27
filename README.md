CS 340 – Client-Server Development
Grazioso Salvare Dashboard Project
Project Overview

In this project, you will build a sample MongoDB Dashboard application that was developed for an animal rescue organization called Grazioso Salvare, in Python. This program leverages a reusable Python CRUD module to connect to a MongoDB collection that supports all Create, Read, Update, and Delete operations. The interactive Dashboard then allows users to filter, analyze, and visualize animal data on the fly.

Key Features

Module Python CRUD Module : Leverages a reusable Python CRUD Module to facilitate MongoDB collection access. The reusability and centralized logic for database access is valuable for data driven development.

Connects to MongoDB : Establishes a connection with the MongoDB Database in order to query and update data in real time.

Interactive Dashboard: Enables intuitive filtering and analysis of animal data by characteristics like Breed, Age, Outcome Type, and Location.

Code Structure: Emphasizes clean, modular and readable code design. The design and development practices are valuable for collaborative work and future maintenance.

Reflection
Write Programs for People to Read and Maintain, and Computers to Adapt

In this project, I learned to write reusable, readable and maintainable programs, in Python. The approach taken in the development of the CRUD module. The CRUD operations logic for connecting and querying the MongoDB Database, is built inside a separate Python module that can be imported and used in any program that requires database access. The module in essence, “abstracts” away all the data access logic, so the program needs to just leverage the functions in the module to interact with the database, in a consistent way. This promotes code reuse and can greatly simplify the code in other programs that need to deal with database access. For example, imagine a future data project that the organization has to work with a supplier or warehouse for inventory management. The inventory can be added, searched, queried, analyzed, etc. in a similar manner, and the code inside the database CRUD module will not need to be changed (unless of course the Database structure itself changes, in which case any program can benefit from the centralized changes).

Describe your problem-solving method

As a computer scientist, first, I began by understanding the overall problem. Namely, the client needed to filter, sort, and search a database of animal data in real time and on demand. I divided the problem into smaller chunks – data design, CRUD functionality, and the Dashboard Visualization. The reusability and centralized logic for database access is valuable for data driven development. This made the development efficient and made it easy for the integration of the data logic with the user facing UI components. This project was more difficult than many of the previous ones, as the ability to scale and data accuracy were important factors to consider.

Why Computer Scientists Do What They Do and the Importance of Computing

Computer scientists help create digital tools that empower organizations to better serve their mission. In this project, the built tool would help the organization process data faster and more effectively to help with data-driven decision making when it comes to animal rescues. This project, and others like it, demonstrate how the field can directly contribute to humanitarian and operational goals.

Technologies Used

Python

MongoDB

Dash / Plotly

PyMongo

Jupyter Notebook
