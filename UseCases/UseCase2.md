# USE CASE: 2 Produce a report on the top N populated countries in a given area

## CHARACTERISTIC INFORMATION

### Goal in Context

As a population reporter I want to view the top N populated countries in an area so that I can identify countries with the largest populations.

### Scope

World Population Reporting System.

### Level

Primary task.

### Preconditions

The selected area exists and the user provides a valid number of countries required. Database contains country population data.

### Success End Condition

A report containing the top N populated countries is generated.

### Failed End Condition

No report is produced.

### Primary Actor

Population reporter.

### Trigger

The organisation requires a ranking of the most populated countries.

## MAIN SUCCESS SCENARIO

1. The organisation requests the top populated countries report.
2. The population reporter selects an area and enters the required number of countries.
3. The system retrieves country population data.
4. The system sorts countries by population.
5. The system displays the top N populated countries.

## EXTENSIONS

2. **Invalid number entered**:
    1. The system requests a valid number from the population reporter.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: 31/07/26
