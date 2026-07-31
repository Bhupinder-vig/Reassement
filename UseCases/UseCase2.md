# USE CASE: 2 Produce a City Report

## CHARACTERISTIC INFORMATION

### Goal in Context

As a population reporter I want to generate a city report organised by population so that the organisation can analyse population distribution between cities.

### Scope

World Database System.

### Level

Primary task.

### Preconditions

The database contains city information including name, country, district and population.

### Success End Condition

A city report is generated and provided to the organisation.

### Failed End Condition

No city report is produced.

### Primary Actor

Population Reporter.

### Trigger

The organisation requires city population information.

## MAIN SUCCESS SCENARIO

1. The organisation requests a city population report.
2. The population reporter selects the required area.
3. The system retrieves city data from the database.
4. The system sorts cities by population.
5. The report is displayed.

## EXTENSIONS

4. **Area does not exist:**
    1. The system informs the population reporter that no cities were found.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: 31/07/26
