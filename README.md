# Document Editor – MongoDB Implementation

This repository contains the implementation of the data model designed in Exercise 3 for a collaborative document editor.

All implementation tasks, including database creation, data insertion, and query execution, were performed using MongoDB Compass.

## Database

The implementation uses MongoDB and includes three collections:

- `Users`: Stores user information.
- `Documents`: Stores document information and embeds collaborators as an array of subdocuments.
- `Edits`: Stores edits separately. Each edit includes the related document ID and the editor's username.

## Dummy Data

The `data/` folder contains JSON files with the dummy data used in the implementation:

- `users.json`
- `documents.json`
- `edits.json`

## Example Queries

The `queries/queries.mongodb` file contains example MongoDB queries used to:

- Retrieve a document and its collaborators.
- Retrieve all edits of a specific document.
- Find documents where a specific user is a collaborator.


## Screenshots

The `screenshots/` folder contains screenshots demonstrating the database collections and example query results.
