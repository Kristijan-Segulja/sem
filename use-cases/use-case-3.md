# USE CASE: 3 Produce a report on the salary of employees in management department

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *department manager* I want *to produce a report on the salary of employees in my department* so that *I can support financial reporting for my department.*

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the role.  Database contains employee data.

### Success End Condition

A report is available for Department Manager to provide to finance.

### Failed End Condition

No report is produced.

### Primary Actor

Department manager

### Trigger

A request for finance information is sent to Department Manager.

## MAIN SUCCESS SCENARIO

1. Finance request salary information for a given role.
2. Department Manager captures name of the role to get salary information for.
3. Department Manager extracts current salary information of all employees of the given role.
4. Department Manager provides report to finance.

## EXTENSIONS

3. **Role does not exist**:
    1. Department Manager informs finance no role exists.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0