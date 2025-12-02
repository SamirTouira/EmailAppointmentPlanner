# PHP Email-based Appointment Workflow

This is a lightweight, automated appointment management system in PHP.

It handles the full workflow by email:

- A client submits an appointment request via a form.
- The recipient (coach, business owner, etc.) receives an email and can:
  - accept the requested time,
  - decline it,
  - or refuse it and propose a new time slot via an internal HTML form.
- The client then receives a follow-up email and can accept or decline the new time slot.
- Each step is secured with tokens and tracked via simple JSON files.

You just need to call the main PHP endpoint when a form is submitted - the rest of the logic (tokens, validation, rescheduling and emails) is handled for you.

More detailed documentation and examples coming soon.
