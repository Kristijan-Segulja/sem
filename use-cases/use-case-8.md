# USE CASE: 8 Delete an employee's details

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *to delete an employee's details* so that *the company is compliant with data retention legislation.*

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the role.  Database contains employee data.

### Success End Condition

HR can delete employee information.

### Failed End Condition

Unable to delete employee information.

### Primary Actor

HR Advisor.

### Trigger

A request for employee information deletion is sent to HR.

## MAIN SUCCESS SCENARIO

1. Company request information deletion for a given employee.
2. HR advisor deletes employee information.

## EXTENSIONS

3. **Role does not exist**:
    1. HR advisor informs company no role exists.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0