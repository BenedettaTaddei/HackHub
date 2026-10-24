# HackHub

Team project for the *Ingegneria del Software* (Software Engineering) course at the University of Camerino.

HackHub is a web platform for managing hackathons: organisers create events, teams register and submit their work, and judges and mentors follow each hackathon through its stages (registration, in progress, evaluation, concluded).

## Project phases

1. **Analysis and design:** requirements engineering, use cases, analysis and design class diagrams, and sequence diagrams. The UML models are in `HackHub.vpp` (Visual Paradigm).
2. **Implementation:** the system was then developed in Java with Spring Boot.

## Tech stack

Java 21, Spring Boot 3.2.5, Spring Web, Spring Data JPA, Bean Validation, H2 database, Maven, OpenAPI (Swagger UI)

## Getting started

Requirements: JDK 21 (Maven is included through the wrapper).

```bash
git clone https://github.com/BenedettaTaddei/HackHub.git
cd HackHub/hackhub
./mvnw spring-boot:run
```

On Windows, use `mvnw.cmd spring-boot:run`.

## Authors

Developed by a team of students of the University of Camerino. Fork maintained by Benedetta Taddei.
