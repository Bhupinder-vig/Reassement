# USE CASE: 1 Produce a Country Report

## CHARACTERISTIC INFORMATION

### Goal in Context

As a population reporter I want to generate a report of countries organised by population from highest to lowest so that the organisation can compare country populations.

### Scope

World Database System.

### Level

Primary task.

### Preconditions

The database contains country information including name, code, continent, region, population and capital details.

### Success End Condition

A country report is generated containing the required country information.

### Failed End Condition

No country report is produced due to missing or invalid database information.

### Primary Actor

Population Reporter.

### Trigger

The organisation requires information about countries and their populations.

## MAIN SUCCESS SCENARIO

1. The organisation requests a country population report.
2. The population reporter selects the required country report option.
3. The system retrieves country data from the database.
4. The system organises countries by population from highest to lowest.
5. The report is displayed to the population reporter.

## EXTENSIONS

4. **No country data exists:**
    1. The system informs the population reporter that no country information is available.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: 31/07/26