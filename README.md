# mongodb-lecture-project

MongoDB implementation of a chat application schema for "Database II" at DHBW Stuttgart.

## Project Overview

This project explores MongoDB as a document-oriented NoSQL database solution. We migrate and analyze a chat application database schema originally designed for relational databases to demonstrate MongoDB's capabilities, advantages, and use cases.

### Database Schema

The project implements a real-time chat application with the following entities:
- **Users**: User accounts with authentication
- **Groups**: Chat groups/channels
- **Group Members**: Many-to-many relationship between users and groups
- **Chat Messages**: Messages sent within groups
- **Files**: File attachments shared in conversations

**Original Schema References:**
- Visual diagram: [docs/Relational_DB_Schema.png](docs/Relational_DB_Schema.png)
- SQL implementation: [src/relational/script.sql](src/relational/script.sql)

These files serve as the baseline for our MongoDB migration.

## Project Structure

- `docs/` - Project documentation and milestones
- `src/` - MongoDB implementation + orginal SQL implementation for comparison
- `presentation/` - Presentation materials
- `ebook/` - eBook chapter

For detailed project timeline and deliverables, see [docs/milestones.md](docs/milestones.md).

## Presentation Structure

The project presentation covers:

1. Introduction to Document Store Databases
2. MongoDB: History and Overview
3. From SQL to NoSQL: Why Document Stores?
4. MongoDB Data Modeling
5. Practical Example: Messaging Service Migratio
6. MongoDB API
7. CAP Theorem: MongoDB’s Trade-offs
8. Conclusion and Recommendations
9. References (APA style)

## eBook Chapter Structure

The written chapter includes:

1. Introduction to Document Store Databases
2. MongoDB: History and Overview
3. From SQL to NoSQL: Why Document Stores?
4. MongoDB Data Modeling
5. Installation and Setup
6. Practical Example: Messaging Service Migratio
7. MongoDB API
8. ⁠MongoDB Ecosystem and Deployment
9. CAP Theorem: MongoDB’s Trade-offs
10. Conclusion and Recommendations
11. References (APA style)

## License

This project is created for educational purposes as part of the Database II course at DHBW Stuttgart.