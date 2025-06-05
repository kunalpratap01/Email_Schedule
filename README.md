**Email Scheduler Application**
This project provides an email scheduling service using Quartz Scheduler and Spring Boot. It allows users to schedule emails with a specific subject and body to be sent at a future date and time.

## Assumptions
- The project assumes that you have **Java 11** or later installed on your system.
- **Maven** is used for project dependency management.
- **Quartz Scheduler** is used to manage email jobs.
- The time zone provided in the request should be valid and in the format recognized by `ZoneId.of()`.
- The scheduled time must be in the future.

## Setup Instructions

### Prerequisites
1. **Java 11+**: Ensure you have Java 11 or a later version installed on your machine.
2. **Maven**: Ensure you have Maven installed to handle dependencies and build the project.

### Clone the Repository
First, clone the repository to your local machine.
