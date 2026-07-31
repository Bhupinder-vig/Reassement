# USE CASE: 5 Produce Population Summary Report

## CHARACTERISTIC INFORMATION

### Goal in Context

As a population reporter I want to generate population summaries so that the organisation can compare populations inside and outside cities.

### Scope

World Database System.

### Level

Primary task.

### Preconditions

The database contains population information for countries and cities.

### Success End Condition

A population summary containing total population, city population and non-city population is generated.

### Failed End Condition

No population summary is produced.

### Primary Actor

Population Reporter.

### Trigger

The organisation requests population distribution information.

## MAIN SUCCESS SCENARIO

1. The organisation requests a population summary.
2. The population reporter selects an area.
3. The system calculates total population.
4. The system calculates people living in cities.
5. The system calculates people not living in cities.
6. The system displays the summary with percentages.

## EXTENSIONS

3. **Invalid area selected:**
    1. The system informs the population reporter.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: 31/07/26
