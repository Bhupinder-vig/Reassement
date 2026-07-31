# USE CASE: 3 Produce a report on cities in a given area from highest population to lowest

## CHARACTERISTIC INFORMATION

### Goal in Context

As a population reporter I want to organise cities by population so that I can compare population sizes between different cities.

### Scope

World Population Reporting System.

### Level

Primary task.

### Preconditions

The selected area exists and city population information is available in the database.

### Success End Condition

A city population report is generated.

### Failed End Condition

No city report is produced.

### Primary Actor

Population reporter.

### Trigger

The organisation requires information about city populations.

## MAIN SUCCESS SCENARIO

1. The organisation requests city population information.
2. The population reporter selects an area.
3. The system retrieves city data from the database.
4. The system organises cities from highest population to lowest.
5. The report is displayed.

## EXTENSIONS

3. **No cities found**:
    1. The system informs the population reporter that no cities exist in the selected area.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: 31/07/26


