
# USE CASE: 7 Produce a language report

## CHARACTERISTIC INFORMATION

### Goal in Context

As a population reporter I want to view language statistics so that I can understand the distribution of major languages.

### Scope

World Population Reporting System.

### Level

Primary task.

### Preconditions

Language information exists in the database.

### Success End Condition

A language report showing speakers and percentages is produced.

### Failed End Condition

No report is produced.

### Primary Actor

Population reporter.

### Trigger

The organisation requires language population statistics.

## MAIN SUCCESS SCENARIO

1. The organisation requests language information.
2. The system retrieves language data.
3. The system calculates total speakers.
4. The system calculates world percentage.
5. The report is displayed.

## EXTENSIONS

2. **Language data unavailable**:
    1. The system informs the population reporter.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: 31/07/26
