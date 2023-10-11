# Data Storage

## Status
Proposed

## Context
We need to determine the data storage solution for our transportation app, including user profiles, ride history, and payment information.

## Decision
For storing structured data, we have decided to use MySQL as our relational database management system (RDBMS). This choice is in line with the requirement for simple management of ride-related data, user accounts, and payments. Additionally, we will manage unstructured data including user-generated content and media files using Google Cloud Storage for object storage. This strategy ensures that we have a scalable and dependable base to handle the data storage requirements of our transportation application.

## Consequences/Rationale
The selection of MySQL and Google Cloud Storage for structured and unstructured data in the transportation app directly supports the app's objectives by ensuring data accuracy, scalability, and affordability. Google Cloud Storage effectively handles unstructured content like photos and videos, ensuring the app can efficiently store and retrieve multimedia files. Meanwhile, MySQL's relational capabilities are well-suited for maintaining structured data, such as trip records and user accounts, enabling seamless and efficient querying for ride history and user profiles. This combination of technologies not only ensures data integrity and scalability to accommodate growing user bases but also facilitates the efficient querying necessary for a seamless user experience, ultimately contributing to the creation of a powerful and responsive transportation app for both passengers and drivers.

Decision record template by Michael Nygard