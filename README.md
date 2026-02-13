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

1. Type of Database & History
2. Improvements over Relational DB Design
3. DB Design (Advantages/Disadvantages)
4. Test Examples (Using Former SQL Project)
5. Query Performance & Indexing
6. API
7. Advantages and Disadvantages (eco system, usage tiers, ...)
8. CAP Theorem Analysis
9. Conclusion

## eBook Chapter Structure

The written chapter includes:

1. Type of Database & History
2. Improvements over Relational DB Design
3. DB Design (Advantages/Disadvantages)
4. Installation (Process, Requirements, Challenges)
5. Test Examples (Using Former SQL Project)
6. Query Performance & Indexing
7. API
8. Advantages and Disadvantages (eco system, usage tiers, ...)
9. CAP Theorem Analysis
10. Conclusion
11. References (APA Style)

## License

This project is created for educational purposes as part of the Database II course at DHBW Stuttgart.