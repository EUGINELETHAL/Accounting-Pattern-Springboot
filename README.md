# Accounting-Pattern-Springboot
# Spring Boot Accounting System

## Description
This is a basic accounting system built using Spring Boot, designed to simulate financial transactions between accounts. It supports:
- Account transactions (debits and credits).
- Tracking individual entries within a transaction.
- Account-specific entries for auditing purposes.

The application ensures transactional integrity and follows domain-driven design (DDD) principles.

## Features
- **Account Transactions**: Perform transactions between accounts.
- **Transaction Entries**: Detailed records of each debit and credit.
- **Account Entries**: Maintain a history of all transactions linked to specific accounts.
- **Transaction Posting**: Ability to "post" transactions, ensuring that they are finalized.
- **Immutable Transactions**: Once posted, transactions can no longer be modified.

## Tech Stack
- **Java 17**
- **Spring Boot 3.x**
- **Spring Data JPA** (Hibernate)
- **H2 Database** (In-memory for development)
- **Postgres Database
- **Lombok** (to reduce boilerplate code)
- mvn clean install


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/springboot-accounting-system.git
   cd springboot-accounting-system
