# Sample Prompts

This document contains example prompts for interacting with the AI Database Modernization Agent.

---

# Scenario 1 — Database Migration

## Prompt

```
Migrate my Spring Boot application from MySQL to PostgreSQL.

Repository:
https://github.com/example/customer-service

Requirements:
- Preserve application architecture.
- Update only database-related code.
- Generate migration report.
- Maintain compatibility with Java 17 and Spring Boot 3.
```

---

# Scenario 2 — AWS Lambda Migration

## Prompt

```
Review my AWS Lambda application.

Database:
MySQL

Target:
PostgreSQL

Requirements:
- Update JDBC driver
- Convert SQL syntax
- Update configuration
- Generate required Operations classes
- Generate migration report
```

---

# Scenario 3 — AWS Glue Migration

## Prompt

```
Migrate an AWS Glue ETL job from MySQL to PostgreSQL.

Perform:

- Query compatibility review
- JDBC updates
- Glue connection updates
- SQL conversion
- Test validation
```

---

# Scenario 4 — Repository Review

## Prompt

```
Analyze this repository for database migration readiness.

Repository:
https://github.com/example/order-service

Generate:

- Compatibility report
- SQL review
- Required code changes
- Migration complexity
- Risk assessment
```

---

# Scenario 5 — Operations Code Generation

## Prompt

```
Generate PostgreSQL Operations classes for the Customer module.

Requirements:

- Follow existing repository conventions.
- Reuse current architecture.
- Generate Unit Tests.
- Generate migration summary.
```
