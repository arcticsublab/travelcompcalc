# Calculation Assumptions

Document the business rules, schedule assumptions, rounding rules,
and known limitations for the calculator here.
# Travel Compensatory Time Calculator — Calculation Assumptions

## Purpose

This document records the assumptions, inputs, limitations, and validation
requirements used by the Travel Compensatory Time Calculator.

The calculator is intended as a decision-support and documentation aid. It does
not replace review by the employee, supervisor, timekeeper, human-resources
office, approving official, or other authority designated by applicable policy.

## Intended Policy References

The calculator is intended to support application of:

- UWDCINST 12610.1A
- Joint Travel Regulations (JTR)
- Any applicable Department of the Navy, command, civilian-human-resources, or
  local implementing guidance

Before operational use, validate the current policy source, edition, paragraph,
and local procedures applicable to the user and travel situation.

## Inputs Required From the User

The calculator requires the user to provide or verify, as applicable:

- Employee name and pay plan / series / grade
- Home city or normal commute origin
- Normal one-way permanent duty station commute time
- Work schedule type
- Pay-period reference date
- Baseline workday hours
- Travel purpose or justification
- TDY/TAD destination
- Origination and final-arrival locations
- Travel itinerary legs, dates, times, and locations
- Ground travel and waiting-time information
- Any schedule changes, delays, or exceptions that affect the calculation

## Work-Schedule Assumptions

The calculator provides user-selectable support for:

- Standard eight-hour weekday schedules
- 5-4-9 compressed schedules
- Maxi-Flex schedules using user-provided pay-period data

The user is responsible for confirming that the selected schedule and entered
workday information accurately represent the employee's approved schedule for
the relevant travel dates.

## Travel-Time Assumptions

- Itinerary times are entered or interpreted as scheduled local times.
- The calculator may derive a time-zone offset from a state code.
- The user may override the time-zone offset when the automatic value is not
  appropriate.
- Users should edit itinerary-leg fields to reflect delays or other actual
  travel circumstances and document the justification for the change.
- Ground travel may be identified separately from flight travel.
- Travel legs should be reviewed for correct sequence, date, time, location,
  type, and time-zone treatment before calculation.

## Commute Assumption

The calculator accepts a user-entered normal one-way PDS commute time.

The user must validate that the commute value, its use in the calculation, and
any exceptions are consistent with applicable policy and local guidance.

## Calculation Output

The calculator produces an estimated travel compensatory-time computation based
on the entered itinerary, work schedule, commute information, travel-day
settings, and any manual adjustments.

The output is not automatically authoritative. The user must review the result
and supporting travel information before using it for official documentation,
submission, or approval.

## PDF and Text Itinerary Import

The calculator supports:

1. Importing a DTS itinerary PDF, when the required PDF-processing library is
   available; or
2. Pasting itinerary text for parsing.

Imported or parsed itineraries must be reviewed by the user. Parsing does not
guarantee that every travel leg, time, location, time zone, delay, or travel
mode was interpreted correctly.

## Known Limitations

- The calculator depends on accurate user inputs.
- PDF parsing may not work on restricted networks or when the required PDF
  library is unavailable.
- Automatically derived time-zone information may require manual correction.
- Nonstandard schedules, split-duty periods, leave, holidays, mission-specific
  exceptions, and unusual travel circumstances may require manual review.
- The tool does not replace policy interpretation or an approving official's
  judgment.
- No real employee, itinerary, or travel data should be committed to the source
  repository or used as repository test data.

## Required User Review Before Official Use

Before relying on an output, the user should confirm:

- The applicable policy and local guidance
- The employee's actual approved work schedule
- Travel-leg sequence and scheduled or actual times
- Time zones and date transitions
- Commute information
- Ground-travel and waiting-time entries
- Any delays, exceptions, leave, holidays, or other nonroutine circumstances
- The final computation and supporting documentation

## Change Log

| Version | Date | Summary of Change | Author/Reviewer |
|---|---|---|---|
| 0.5b | YYYY-MM-DD | Initial documented assumptions | [Name] |
