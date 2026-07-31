# USE CASE: 4 Produce a report on the top N populated cities in a given area

## CHARACTERISTIC INFORMATION

### Goal in Context

As a population reporter I want to view the top N populated cities so that I can identify the largest cities in a selected area.

### Scope

World Population Reporting System.

### Level

Primary task.

### Preconditions

The database contains city population information and a valid number N is provided.

### Success End Condition

A top N city population report is generated.

### Failed End Condition

No report is produced.

### Primary Actor

Population reporter.

### Trigger

The organisation requires information about the largest cities.

## MAIN SUCCESS SCENARIO

1. The organisation requests the top N city report.
2. The population reporter enters the area and number required.
3. The system retrieves city population data.
4. The system sorts cities by population.
5. The system displays the results.

## EXTENSIONS

2. **Invalid N value**:
    1. The system asks the population reporter to enter a valid number.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: 31/07/26
