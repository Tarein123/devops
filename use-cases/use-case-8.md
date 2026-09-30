# USE CASE: 8 Delete an Employee's Details

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *to delete an employee's details* so that *the company is compliant with data retention legislation.*

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the employee. The employee exists in the database.

### Success End Condition

The employee's details are deleted from the database.

### Failed End Condition

The employee's details are not deleted.

### Primary Actor

HR Advisor.

### Trigger

An employee's details are required to be deleted in accordance with data retention requirements.

## MAIN SUCCESS SCENARIO

1. HR advisor receives a request to delete an employee's details.
2. HR advisor identifies the employee.
3. HR advisor retrieves the employee's details.
4. HR advisor requests deletion of the employee's details.
5. HR system deletes the employee's details from the database.
6. HR advisor confirms that the employee's details have been deleted.

## EXTENSIONS

3. **Employee does not exist**:
    1. HR advisor is informed that the employee does not exist.

5. **Employee details cannot be deleted**:
    1. HR advisor is informed that the employee's details could not be deleted.
    2. The employee's details remain in the database.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0