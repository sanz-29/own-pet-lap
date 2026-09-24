# Virtual Pet Desktop Companion
# Database Design

**Project:** Virtual Pet Desktop Companion  
**Document:** Database Design  
**Version:** 1.0  
**Status:** Draft

---

# 1. Purpose

This document defines the SQLite database structure used by the Virtual Pet Desktop Companion.

The database stores application data locally on the user's Windows computer.

The database is designed to be:

- Local
- Lightweight
- Offline-first
- Persistent
- Easy to maintain
- Extensible for future features

---

# 2. Database Technology

Database:

**SQLite**

Why SQLite:

- No separate database server required
- Works locally
- Lightweight
- Suitable for desktop applications
- Supports transactions
- Supports relational data
- Works well with Rust
- Suitable for offline applications

---

# 3. Database Responsibilities

SQLite stores:

```text
SQLite
│
├── Pet Profile
├── Notes
├── Reminders
└── Application Settings