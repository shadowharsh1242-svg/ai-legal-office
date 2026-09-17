# AI Legal Office

Private staff dashboard for an advocate's office.

## Current deployment
- Responsive advocate-friendly dashboard
- Home, Cases, Hearings, Tasks and Clients
- Safe case closure: cases are marked Closed rather than permanently deleted
- Closure reason and closure timestamp fields aligned with the Google Sheets Cases backend
- Closed cases can be filtered and reopened
- Post-hearing update held for advocate confirmation
- No client login
- Dummy data only

## Backend alignment
The Google Sheets `Cases` tab uses `Status`, `Closed At`, `Closure Reason`, and `Updated At`. The website uses the same case lifecycle concept. Permanent deletion is intentionally not exposed in the staff UI so a legal record is not accidentally erased.

## Next integration phase
Connect the website to Google Sheets, then add WhatsApp/SMS/voice reminders, AI assistant, audit logs, and the advocate confirmation workflow.
