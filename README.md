# Demo Java Service ISP 2024

## Application description

This is a demo Java service for the ISP 2024 course. 
- It demonstrate creation of a simple HTTP API (see `TicketsController`).
- It demonstrate how to use REST repositories (see `EventTicketRepository` and `PurchasedTicketRepository`).
- Database access is done using Spring Data JPA. A MySQL database is used.
- Testing is done using JUnit and H2 in-memory database.
- The service is containerized using Docker.
- The service is deployed using Docker Compose.

For running the application, you need to have Docker installed on your machine. When application is run using Docker Compose, it will start a MySQL database and the Java service. Details of the configuraiotns could be found in the `compose.yaml` file.



