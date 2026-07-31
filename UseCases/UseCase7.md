# USE CASE: 7 Produce Language Report

## CHARACTERISTIC INFORMATION

### Goal in Context

As a population reporter I want to generate a language report showing total speakers and percentages so that the organisation can understand global language usage.

### Scope

World Database System.

### Level

Primary task.

### Preconditions

The database contains country language information.

### Success End Condition

A language report is generated showing languages ordered by number of speakers.

### Failed End Condition

No language report is produced.

### Primary Actor

Population Reporter.

### Trigger

The organisation requests worldwide language statistics.

## MAIN SUCCESS SCENARIO

1. The organisation requests language information.
2. The population reporter selects the language report.
3. The system calculates total speakers.
4. The system calculates world population percentages.
5. The system displays languages from highest to lowest speakers.

## EXTENSIONS

3. **Language data unavailable:**
    1. The system informs the population reporter.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: 31/07/26
