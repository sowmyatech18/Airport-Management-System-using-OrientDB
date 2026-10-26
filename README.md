# FlightDB – Airport Management System

FlightDB is an airport management database developed using OrientDB as part of a DBMS case study. It demonstrates how flight, airport, and passenger information can be stored and connected using graph database concepts, with queries for managing records, flight bookings, and seat availability.

## Team Members

| S. No. | Name | Roll Number |
|---|---|---|
| 1 | Aashika A | CB.SC.U4CSE25701 |
| 2 | D Soniya Taslim | CB.SC.U4CSE25711 |
| 3 | Sowmya R | CB.SC.U4CSE25756 |

## Project Objectives

- Design an airport management database using OrientDB.
- Store and manage flight, airport, and passenger information.
- Represent relationships between records using graph database concepts.
- Implement flight booking and seat management operations.
- Demonstrate SQL-like queries and graph traversal.
- Explore ACID transactions for maintaining booking consistency.
- Understand how vertices and edges represent connected data.

## Technologies and Implementation

The project uses **OrientDB** to store and manage airport-related data through document and graph database capabilities.

- **OrientDB:** Database storage and management.
- **OrientDB SQL:** Creating classes, inserting records, updating data, and retrieving information.
- **Graph Model:** Representing entities as vertices and their relationships as edges.

### Database Workflow

```text
             FlightDB
                 |
                 v
      Create Database Schema
                 |
                 v
       Insert Airport, Flight
        and Passenger Data
                 |
                 v
       Establish Relationships
         Using Graph Edges
                 |
                 v
       Execute OrientDB Queries
                 |
                 v
      Manage Bookings and Seats
                 |
                 v
        Verify Query Outputs
```

## Database Schema

The database is named **FlightDB**.

| Entity | Purpose |
|---|---|
| Airport | Stores airport information |
| Flight | Stores flight details, fares, and seat availability |
| Passenger | Stores passenger information |
| Departs | Connects a flight to its departure airport |
| Arrives | Connects a flight to its arrival airport |
| Booked | Represents passenger flight bookings |

## Relationships

- A flight departs from an airport.
- A flight arrives at an airport.
- A passenger can book a flight.
- Booking relationships connect passengers and flights.
- Graph edges represent connections between database vertices.

## Key Database Features

### 1. Database and Schema Creation

Create the FlightDB database and define classes for vertices and edges using OrientDB.

### 2. CRUD Operations

Demonstrate the fundamental database operations:

- **Create:** Insert airport, flight, and passenger records.
- **Read:** Retrieve records using queries.
- **Update:** Modify flight details and seat availability.
- **Delete:** Remove records while respecting relationships and database constraints.

### 3. Graph Relationships

Use vertices to represent entities and edges to connect related records, enabling relationship-based queries.

### 4. Flight Booking

Demonstrate passenger bookings and updates to available seats.

### 5. Graph Queries

Use OrientDB SQL and graph traversal features to retrieve connected information about flights, airports, and passengers.

### 6. ACID Transactions

Demonstrate transactional operations for maintaining consistency when booking flights and updating seat availability.

## Project Demonstration

The project demonstration includes the OrientDB queries executed and their corresponding outputs, showcasing database creation, record manipulation, graph relationships, and flight booking operations.

## Project Files

- **Presentation:** Project overview and database design.
- **Video:** Recorded demonstration of queries and outputs.
- **Queries.txt:** OrientDB queries used in the case study.
- **README.md:** Project description, database schema, objectives, and team details.

