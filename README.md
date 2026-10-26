# Midas Core — JPMorgan Chase Forage Simulation

Learning repository for the JPMorgan Chase Advanced Software Engineering virtual experience on Forage. This is an educational simulation, not employment at JPMorgan Chase or a production banking system.

## Project goal

Explore a Java/Spring Boot transaction-processing backend through tasks involving Kafka, persistence, an incentive service, and balance queries.

## Files currently present

- Java 17 and a Spring Boot 3.2.5 Maven parent.
- Application entry point in `src/main/java/com/jpmc/midascore/`.
- User entity, repository, and database conduit classes.
- Transaction and balance data classes.
- TaskOne through TaskFive test files and test helpers.
- Maven wrapper and a supplied incentive-service JAR.

## Current snapshot

The default branch is `flow`. Its `pom.xml` currently has an empty dependency block, and the root `application.yml` is empty. The presence of task tests does not establish that all tasks pass or that transaction processing, Kafka consumption, and REST endpoints are fully implemented. This snapshot needs dependency/configuration review before it can be described as a complete runnable solution.

## Local verification

Install JDK 17, check the Maven dependencies and Spring configuration, then run:

```bash
./mvnw test
```

The test suite was not run during this documentation update. Review each task test for required services and expected behavior.

## Portfolio context

Use this repository as a software engineering simulation project. Describe completed contributions based on the actual implementation and test outcomes rather than the full scope of the Forage task descriptions.
