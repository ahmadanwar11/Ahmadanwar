# Agreed Findings (Draft)

These findings are based on the supplied MediTrack requirements and sample checklist runs. Review with your partner and confirm before submission.

| Finding | Requirement(s) | Problem | Suggested clarification |
|---|---|---|---|
| F-01 | R-02 | “Quickly” is not measurable. | Set response-time target and unit under expected load. |
| F-02 | R-03 | Double-booking prevention is not defined in testable detail. | Define conflicting slots, including overlapping appointments for one doctor. |
| F-03 | R-04, R-05 | Requirements conflict: duration is fixed at 15 minutes but adjustable from 10–30 minutes. | Resolve whether durations are fixed or configurable and specify authority. |
| F-04 | R-06 | Reminder timing and delivery method are unspecified. | Define schedule and channel(s) for reminders. |
| F-05 | R-07 | Cancellation updates and receptionist notifications lack timing and method details. | Specify update latency and notification channel. |
| F-06 | R-08 | “User-friendly for all age groups” is vague, especially for elderly users. | Add measurable accessibility/usability criteria. |
| F-07 | R-09 | Patient record privacy/security is too broad; access roles and protection details are missing. | Define role-based access and concrete security expectations. |
| F-08 | R-11 | “Active appointment” is undefined. | Define when an appointment counts as active (e.g., status and time). |
| F-09 | R-12 | “Normal working hours” are not stated. | List hours, days, holidays, and expected availability. |
| F-10 | R-13 | Clinic policy is referenced but not provided. | Attach or identify the policy and relevant rules. |

## Risks considered
- Double bookings and schedule conflicts.
- Patients forgetting appointments.
- Medical-record privacy/access.
- Elderly patients having difficulty using the online system.
- Emergency walk-ins not having a defined process.
- High demand on Monday mornings and unclear availability/performance expectations.