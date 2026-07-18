# CYCLONE GURU ACADEMY

# FIRESTORE SECURITY RULES

## Version

v1.0

## Founder Admin

Read : Allow

Write : Allow

Update : Allow

Delete : Allow

Manage Database : Allow

Manage Storage : Allow

Manage Settings : Allow

Manage Users : Allow

Manage Admins : Allow

Manage AI : Allow

Manage Payments : Allow

## Super Admin

Read : Allow

Write : Allow

Update : Allow

Delete : Allow

Manage Courses : Allow

Manage Current Affairs : Allow

Manage Study Material : Allow

Manage Test Series : Allow

Cannot Delete Founder

Cannot Change Founder Permissions

## Content Admin

Manage Courses

Manage PDFs

Manage Current Affairs

Manage Study Material

Cannot Access Payments

Cannot Access Founder Panel

## Test Admin

Manage Test Series

Manage Questions

Manage Results

Manage Answer Keys

Cannot Access Payments

## Payment Admin

Approve Payment

Reject Payment

View Transactions

Cannot Edit Courses

Cannot Edit AI

## Support Admin

View Students

View Reports

Send Notifications

Cannot Change System Settings

## Student

Read Purchased Content

Attempt Test Series

Bookmark Content

View Results

Edit Own Profile

Cannot Access Admin Collections

## Guest User

View Public Courses

View Free PDFs

Register

Login

Cannot Access Paid Content

## Collection Rules

users

Student : Own Data Only

Admin : Read

Founder : Full Access

admins

Founder : Full Access

Super Admin : Read Only

courses

Student : Read

Admin : Read Write

Founder : Full Access

study_material

Student : Purchased Only

Admin : Read Write

Founder : Full Access

current_affairs

Student : Read

Admin : Read Write

Founder : Full Access

test_series

Student : Purchased Only

Admin : Read Write

Founder : Full Access

payments

Student : Own Payment

Payment Admin : Full Access

Founder : Full Access

notifications

Student : Read

Admin : Write

Founder : Full Access

settings

Founder Only

login_history

Founder

Analytics Admin

## Emergency Mode

Founder Login Always Enabled

Maintenance Mode Bypass

Emergency Database Access

Emergency Backup Access

## Backup Permission

Founder Only

## Restore Permission

Founder Only

## Security Status

Draft v1.0

Future Expansion Enabled