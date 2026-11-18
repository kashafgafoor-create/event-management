# Project Demo Recording Script

Record this walkthrough against the running application and a test database. Do not show real employee personal data, passwords, JWT secrets, or production connection strings.

1. Open the deployed or local application homepage.
2. Create a test organization and administrator account.
3. Save the generated organization ID and sign in.
4. Show the administrator dashboard.
5. Create a corporate event with title, date/time, location, and capacity.
6. Show the event in the event list and open its details.
7. Create a test employee account from the administrator workspace.
8. Sign out and sign in as the employee using the same organization ID.
9. Register for the event.
10. Show the employee's registration list and cancel the registration.
11. Sign back in as the administrator and show the event/registration view.
12. Open `/docs` and briefly show the API documentation.
13. Demonstrate one validation or conflict case, such as trying to exceed event capacity or deleting an event with registration history.

Suggested narration:
- Explain the problem the application solves.
- Explain the layered FastAPI architecture.
- Explain organization-scoped application access and role-based permissions.
- Explain that PostgreSQL is the intended production database and that database-level tenant isolation is not currently claimed.

Before recording, verify the deployed environment and use only synthetic test accounts/data.
