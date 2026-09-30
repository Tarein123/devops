# USE CASE: 3 Produce a Report on the Salary of Employees in My Department

## CHARACTERISTIC INFORMATION

### Goal in Context

As a *department manager* I want *to produce a report on the salary of employees in my department* so that *I can support financial reporting for my department.*

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the department of the department manager. Database contains current employee salary data.

### Success End Condition

A report is available for the department manager to support financial reporting for their department.

### Failed End Condition

No report is produced.

### Primary Actor

Department Manager.

### Trigger

A request for financial information for the department is made.

## MAIN SUCCESS SCENARIO

1. Department manager requires salary information for their department.
2. Department manager identifies their department.
3. Department manager extracts current salary information of all employees in their department.
4. Department manager uses the report to support financial reporting for the department.

## EXTENSIONS

3. **No employee salary information exists for the department**:
    1. Department manager is informed that no employee salary information is available.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0