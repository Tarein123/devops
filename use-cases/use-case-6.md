# USE CASE: 6 View an Employee's Details

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *to view an employee's details* so that *the employee's promotion request can be supported.*

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the employee number. Database contains current employee information.

### Success End Condition

The employee's details are available for the HR advisor to support the promotion request.

### Failed End Condition

No employee details are displayed.

### Primary Actor

HR Advisor.

### Trigger

An employee's promotion request requires supporting information.

## MAIN SUCCESS SCENARIO

1. HR advisor receives a request to view an employee's details.
2. HR advisor captures the employee number.
3. HR advisor retrieves the employee's current details from the database.
4. HR system displays the employee's details.
5. HR advisor uses the employee's details to support the promotion request.

## EXTENSIONS

3. **Employee does not exist**:
    1. HR advisor is informed that no employee exists with the given employee number.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0