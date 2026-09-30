# USE CASE: 5 Add a New Employee's Details

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *to add a new employee's details* so that *I can ensure the new employee is paid.*

### Scope

Company.

### Level

Primary task.

### Preconditions

The new employee's details are available. The HR advisor has access to the HR system.

### Success End Condition

The new employee's details are stored in the database.

### Failed End Condition

The new employee's details are not added to the database.

### Primary Actor

HR Advisor.

### Trigger

A new employee joins the company.

## MAIN SUCCESS SCENARIO

1. HR advisor receives the new employee's details.
2. HR advisor enters the new employee's details into the HR system.
3. HR system validates the employee's details.
4. HR system stores the new employee's details in the database.
5. HR advisor confirms that the new employee has been added.

## EXTENSIONS

3. **Employee details are invalid or incomplete**:
    1. HR system informs the HR advisor that the employee's details are invalid or incomplete.
    2. HR advisor corrects the employee's details.
    3. Use case continues from step 3.

4. **Employee details cannot be stored**:
    1. HR system informs the HR advisor that the employee could not be added.
    2. No employee record is created.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0