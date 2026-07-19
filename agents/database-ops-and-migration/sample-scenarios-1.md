# Sample Scenario

## Objective

Migrate an enterprise Spring Boot application from MySQL to PostgreSQL.

---

## User Request

```
Migrate my Spring Boot application to PostgreSQL.

Repository:
customer-service

Current Database:
MySQL

Target Database:
PostgreSQL
```

---

## Agent Response

### Step 1

Repository analysis started.

✔ Spring Boot detected

✔ Java 17 detected

✔ Spring Data JPA detected

✔ MySQL Driver detected

---

### Step 2

Scanning repository...

Found:

- Repository Layer
- Entity Layer
- Operations Layer
- SQL Queries
- Configuration Files
- Unit Tests

---

### Step 3

Migration Plan

The following components require modification.

| Component | Status |
|-----------|--------|
| pom.xml | Update Driver |
| application.yml | Update URL |
| SQL Queries | Convert |
| Operations Layer | Regenerate |
| Tests | Update |

---

### Step 4

Migration Summary

✔ Driver Updated

✔ SQL Converted

✔ Operations Generated

✔ Configuration Updated

✔ Unit Tests Updated

✔ Coverage Verified (>80%)

---

### Final Output

Migration completed successfully.

Estimated manual effort:

2 Days

Estimated AI-assisted effort:

1 Hour

Migration Report Generated.
