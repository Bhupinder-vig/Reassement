# USE CASE: 1 Produce a report on countries in a given area (world, continent, region) from highest population to lowest

## CHARACTERISTIC INFORMATION

### Goal in Context

As a population reporter I want to organise countries in an area based on largest population to smallest so that I can compare the populations of countries in that area.

### Scope

World Population Reporting System.

### Level

Primary task.

### Preconditions

The selected area is known (world, continent, or region). The database contains population data for countries.

### Success End Condition

A country population report is generated and displayed for the population reporter.

### Failed End Condition

No report is produced.

### Primary Actor

Population reporter.

### Trigger

The organisation requires information about country populations in a specific area.

## MAIN SUCCESS SCENARIO

1. The organisation requests country population information.
2. The population reporter selects the required area.
3. The system retrieves country population data from the database.
4. The system organises countries from highest population to lowest.
5. The population reporter provides the generated report to the organisation.

## EXTENSIONS

3. **Area does not exist**:
    1. The system informs the population reporter that the selected area cannot be found.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: 31/07/26
