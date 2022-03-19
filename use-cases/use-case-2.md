# USE CASE: 2 Produce a report on the salary of employees in a department

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *to produce a report on the salary of employees in a department* so that *I can support financial reporting of the organisation.*

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

A request for finance information is sent to HR.

## MAIN SUCCESS SCENARIO

1. Finance request salary information for a given role.
2. HR Advisor captures name of the role to get salary information for.
3. HR Advisor extracts current salary information of all employees of the given role.
4. HR Advisor provides report to finance.

## EXTENSIONS

3. **Role does not exist**:
    1. HR Advisor informs finance no role exists.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0