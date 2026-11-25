# MediTrack Validation Findings — Malaika Aslam

**Status:** Draft findings based on checklist review.

## Main issues found
1. **Contradictory appointment length:** R-04 fixes appointments at 15 minutes, but R-05 permits doctors to choose 10–30 minutes. The SRS should clarify how these rules work together.
2. **Performance is not measurable:** R-02 says “quickly” but gives no response-time target.
3. **Double-booking prevention is underspecified:** R-03 states the goal without describing conflict checking or handling concurrent booking attempts.
4. **Reminder details are missing:** R-06 does not state reminder timing or delivery method.
5. **Cancellation process is incomplete:** R-07 lacks rules/deadlines and a schedule-update time.
6. **Usability requirement cannot be tested:** R-08 gives no concrete accessibility/usability criteria for different ages.
7. **Privacy and security are vague:** R-09 does not define access permissions or specific security requirements.
8. **Walk-in handling is unclear:** R-10 does not explain scheduling or prioritization of walk-in patients, including elderly patients.
9. **Appointment limit is unclear:** R-11 does not define how active appointments are counted.
10. **Availability lacks hours:** R-12 does not state clinic opening hours or applicable time zone.
11. **Payment policy is not provided:** R-13 refers to a policy without including it.
12. **Doctor schedule details are missing:** R-14 does not define what daily schedule information doctors can view.
13. **Peak demand is not addressed:** The SRS has no capacity/load requirement for busy Monday mornings.

## Suggested next steps
- Clarify appointment-duration rules and define a single consistent policy.
- Add measurable response-time and availability targets.
- Specify booking conflict handling, reminder timing/channel, cancellation workflow, and walk-in process.
- Add privacy/access-control requirements and testable accessibility criteria.
- Define clinic hours, payment policy, active appointment counting, doctor schedule details, and Monday peak capacity expectations.

Before submitting, fill actual run start/end times and ensure the individual runs represent your own review.
