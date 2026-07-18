# CYCLONE GURU ACADEMY

# FIRESTORE DATABASE STRUCTURE

## Version

v1.0

# Main Collections

users

admins

founder

roles

permissions

courses

subjects

study_material

current_affairs

monthly_current_affairs

test_series

questions

results

payments

transactions

notifications

bookmarks

reading_history

referrals

coupons

rewards

reports

ai_notes

settings

login_history

# users

Fields

uid

name

email

phone

profileImage

role

status

createdAt

lastLogin

# admins

Fields

uid

name

email

role

permissions

status

createdBy

createdAt

# founder

Fields

name

role

masterAccess

email

status

createdAt

# courses

Fields

title

description

category

price

thumbnail

pdfAccess

status

createdBy

createdAt

# study_material

Fields

title

subject

medium

pdfUrl

price

visibility

uploadedBy

createdAt

# current_affairs

Fields

title

description

category

date

image

createdBy

# monthly_current_affairs

Fields

month

year

pdfUrl

price

status

# test_series

Fields

title

subject

price

duration

launchDate

status

createdBy

# questions

Fields

question

optionA

optionB

optionC

optionD

correctAnswer

explanation

# payments

Fields

userId

amount

method

screenshot

status

verifiedBy

createdAt

# login_history

Fields

userId

role

device

loginTime

status

# settings

Fields

appName

maintenanceMode

adsEnabled

dailyAdLimit

# Reserved Collections

teachers

live_classes

assignments

certificates

leaderboard

job_portal

marketplace

offline_sync

# Status

Draft v1.0

Future Expansion Enabled