---
name: Add Persistent Data Storage
about: Migrate from in-memory storage to a proper database
title: "Feature: Database and Persistent Storage"
labels: enhancement
assignees: ''
---

## Description
Migrate from in-memory data storage to a proper database system to ensure data persistence across server restarts and handle larger datasets.

## New Features
- Persistent database (SQLite, PostgreSQL, or similar)
- Data models for activities, users, clubs, registrations
- Migration from in-memory to database
- Database backups and management
- Query optimization for performance

## Acceptance Criteria
- [ ] Database schema is properly designed
- [ ] All data persists across restarts
- [ ] Existing data is migrated correctly
- [ ] Database queries are performant
- [ ] Database backups are automated
