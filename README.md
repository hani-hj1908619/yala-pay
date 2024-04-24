# YalaPay B2B Web App

## Description:
YalaPay B2B Web App streamlines invoice management, payment processing, and cheque handling for efficient financial transactions between companies and customers.

## Technologies Used:
- Vanilla HTML, CSS, JavaScript
- IndexedDB
- MongoDB
- Mongoose (for MongoDB data modeling)
- Node.js
- Express.js APIs

## Features:
- Dashboard: Display summary of invoices and cheques.
- Customer Management: List, search, add, update, and delete customers.
- Invoice Management: List, search, add, update, and delete invoices.
- Payment Management: List, search, add, update, and delete payments for invoices.
- Cheque Management: Add, list, update, and delete cheques deposits.
- Reports: Generate invoices and cheques reports by period and status.

## Screenshots:
![Screenshot](https://i.imgur.com/vupvWZy.png)
![Screenshot](https://i.imgur.com/PNppMGH.png)
![Screenshot](https://i.imgur.com/VSo5ctn.png)
![Screenshot](https://i.imgur.com/dykKgmI.png)

## Implementation Phases:

### Phase 1: WebApp UI Design and Implementation
1. Design and implement Web UI using HTML, CSS, and JavaScript.
2. Client-side data access using IndexedDB for data storage.
3. Application Design: Entities Class Diagram and Repositories Class Diagram.
4. Testing Documentation with screenshots illustrating the testing results.

### Phase 2: Web API and Data Management using MongoDB
1. Design and implement database schema using MongoDB, including schema diagram.
   ![MongoDB Schema Diagram](https://i.imgur.com/FgcBCZz.png)
2. Populate MongoDB with data from JSON files.
3. Implement repository methods to read/write data from MongoDB.
4. Implement Web API using ExpressJS repositories, services and routers.
5. Update Web UI to use Web API instead of IndexedDB for data retrieval.

