# USE CASE: 3 Produce a Capital City Report

## CHARACTERISTIC INFORMATION

### Goal in Context

As a population reporter I want to generate a report of capital cities organised by population so that the organisation can compare capital city sizes.

### Scope

World Database System.

### Level

Primary task.

### Preconditions

The database contains capital city information linked to countries.

### Success End Condition

A capital city report containing city name, country and population is produced.

### Failed End Condition

No capital city report is produced.

### Primary Actor

Population Reporter.

### Trigger

The organisation requests capital city population information.

## MAIN SUCCESS SCENARIO

1. The organisation requests a capital city report.
2. The population reporter selects the required area.
3. The system identifies capital cities from the database.
4. The system orders capital cities by population.
5. The report is displayed.

## EXTENSIONS

4. **No capital cities found:**
    1. The system informs the population reporter.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: 31/07/26


