# CYCLONE GURU ACADEMY

# FIRESTORE INDEXES

## Version

v1.0

# Purpose

Improve Firestore Query Performance

Reduce Read Time

Support Complex Queries

# Users Collection

email

phone

role

status

createdAt

lastLogin

# Admin Collection

email

role

status

createdAt

# Courses

category

subject

price

status

createdAt

# Study Material

subject

medium

price

status

createdAt

# Current Affairs

date

category

createdAt

# Monthly Current Affairs

year

month

status

# Test Series

subject

launchDate

status

price

# Questions

testId

questionNumber

# Results

studentId

testId

score

rank

submittedAt

# Payments

userId

status

amount

createdAt

verifiedBy

# Transactions

transactionId

paymentId

status

createdAt

# Notifications

targetRole

createdAt

status

# Bookmarks

userId

createdAt

# Reading History

userId

lastRead

# AI Notes

subject

topic

language

createdAt

# Reports

reportType

createdAt

status

# Composite Indexes

Courses

category + status

subject + status

price + status

Study Material

subject + medium

subject + price

Current Affairs

date + category

category + createdAt

Test Series

subject + status

launchDate + status

Payments

status + createdAt

userId + createdAt

Results

studentId + submittedAt

testId + rank

# Reserved Indexes

teachers

assignments

live_classes

job_portal

marketplace

# Status

Draft v1.0

Future Expansion Enabled