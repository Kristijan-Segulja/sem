# USE CASE: 6 View and employee's details

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *to view and employee's details* so that *the employee's promotion request can be supported.*

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the role.  Database contains employee data.

### Success End Condition

HR can update employee information.

### Failed End Condition

Unable to acquire employee information.

### Primary Actor

HR Advisor.

### Trigger

A request for employee information update is sent to HR.

## MAIN SUCCESS SCENARIO

1. Company request of information for a given employee.
2. HR advisor acquires employee information.

## EXTENSIONS

3. **Role does not exist**:
    1. HR advisor informs company no role exists.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0