# USE CASE: 1 Produce a report on the salary of all employees

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *to produce a report on the salary of all employees* so that *I can support financial reporting of the organisation.*

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the role.  Database contains finance data.

### Success End Condition

A report is available for HR Advisor to provide to finance.

### Failed End Condition

No report is produced.

### Primary Actor

HR Advisor

### Trigger

A request for salary information is sent to HR.

## MAIN SUCCESS SCENARIO

1. Finance request salary information for all employees.
2. HR Advisor gets salary information.
3. HR Advisor extracts current salary information of all employees.
4. HR Advisor provides report to finance.

## EXTENSIONS

3. **Role does not exist**:
    1. HR Advisor informs finance no role exists.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0