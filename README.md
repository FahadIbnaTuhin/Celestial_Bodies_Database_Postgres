# Celestial Bodies Database

A PostgreSQL relational database project built as part of the Relational Database Certification from :contentReference[oaicite:0]{index=0}.

## 📌 Project Overview

This project models a small universe containing:

- Galaxies
- Stars
- Planets
- Moons
- Additional celestial-related tables

The database demonstrates:

- Relational database design
- Primary and foreign keys
- Table relationships
- Constraints
- PostgreSQL data types
- SQL schema creation
- Data insertion and normalization

---

## 🛠 Technologies Used

- :contentReference[oaicite:1]{index=1}
- SQL
- Git & GitHub
- Linux Terminal

---

## 🗄 Database Structure

### Main Tables

| Table | Description |
|------|-------------|
| galaxy | Stores galaxy information |
| star | Stores star data linked to galaxies |
| planet | Stores planet data linked to stars |
| moon | Stores moon data linked to planets |
| additional table | Extra table for project requirements |

---

## 🔗 Relationships

```text
Galaxy → Star → Planet → Moon
