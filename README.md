# Overtime App

## Key requirement: company needs documentation that salaried employees did or did not get overtime each week

## Models
- X Post -> date:date rationale:text
- X User -> Devise
- X AdminUser -> STI
- X AuditLog

## Features:
- X Approval Workflow
- X SMS Sending -> link to approval or overtime input -> integrate with Heroku scheduler
- X Administrate admin dashboard
- X Block non-admin and guest users
- X Email summary to managers for approval
- X Needs to be documented if employee did not log overtime
- X Create audit log for each text message
- X Need to update end_date when confirmed
- X Need to update audit log status when an overtime rejected
- X Update buttons on employee homepage so they show on mobile
- X Updated buttons to include timespan on employee homepage
- X Update button sort order on employee homepage
- X Remove unneccessary nav bar buttons for managers
- X Fix admin dashboard bug
- Implement new relic for keeping site alive

## TODO's: