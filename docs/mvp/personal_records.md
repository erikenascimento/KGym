# Personal Record Tracker – MVP

## Goal
Allow a user to track their max weight personal record per exercise.

## In Scope
- Single user
- Predefined exercise list
- One PR value per exercise

## Out of Scope
- Authentication
- Multiple users
- PR history
- Custom exercises

## Domain Model
- User
- Exercise
- PersonalRecord

## API Overview
- GET /exercises
- GET /exercises/:id/pr
- PUT /exercises/:id/pr
