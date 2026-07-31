# USE CASE: 4 Produce Top N Populated Cities Report

## CHARACTERISTIC INFORMATION

### Goal in Context

As a population reporter I want to generate the top N populated cities so that the organisation can view the largest cities in a selected area.

### Scope

World Database System.

### Level

Primary task.

### Preconditions

The user provides a valid number N and the database contains city population data.

### Success End Condition

A report showing the top N populated cities is generated.

### Failed End Condition

No report is generated.

### Primary Actor

Population Reporter.

### Trigger

The organisation requests a limited city population ranking.

## MAIN SUCCESS SCENARIO

1. The organisation requests the top N cities.
2. The population reporter enters the required number of cities.
3. The system retrieves city population data.
4. The system sorts cities from highest to lowest population.
5. The system displays the requested number of cities.

## EXTENSIONS

2. **Invalid number entered:**
    1. The system requests a valid number.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: 31/07/26
