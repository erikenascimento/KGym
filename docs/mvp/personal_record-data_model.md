# Personal Record – Data Model

## Purpose
Defines how personal records are stored and related to users and exercises for the MVP.

## Design Decisions
- Personal records are modeled as a separate entity.
- Each record belongs to exactly one user and one exercise.
- A user can have only one personal record per exercise.

## Models
- User
- Exercise
- PersonalRecord

## Constraints
- (userId, exerciseId) must be unique.
- Personal records cannot exist without a user and an exercise.

## Out of Scope
- Record history
- Multiple users
- Custom exercises