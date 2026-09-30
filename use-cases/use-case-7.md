# USE CASE: 7 Update an Employee's Details

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *to update an employee's details* so that *employee's details are kept up-to-date.*

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the employee. The employee exists in the database.

### Success End Condition

The employee's details are updated in the database.

### Failed End Condition

The employee's details are not updated.

### Primary Actor

HR Advisor.

### Trigger

An employee's details require updating.

## MAIN SUCCESS SCENARIO

1. HR advisor receives a request to update an employee's details.
2. HR advisor identifies the employee.
3. HR advisor retrieves the employee's current details.
4. HR advisor changes the required employee details.
5. HR system updates the employee's details in the database.
6. HR advisor confirms that the employee's details have been updated.

## EXTENSIONS

3. **Employee does not exist**:
    1. HR advisor is informed that the employee does not exist.

5. **Employee details cannot be updated**:
    1. HR advisor is informed that the employee's details could not be updated.
    2. Existing employee details remain unchanged.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0