# Manual testing checklist

## Authentication

- [ ] Register with valid details
- [ ] Reject empty fields
- [ ] Reject password shorter than 6 characters
- [ ] Reject duplicate email
- [ ] Login with correct password
- [ ] Reject incorrect password
- [ ] Logout works

## Student workflow

- [ ] Student can view opportunities
- [ ] Student can search opportunities
- [ ] Student can filter by category
- [ ] Student can register once
- [ ] Duplicate registration is rejected
- [ ] Student can view registration status

## Organizer workflow

- [ ] Organizer can create opportunity
- [ ] Required fields are validated
- [ ] Invalid capacity is rejected
- [ ] Organizer can edit own opportunity
- [ ] Organizer can delete own opportunity
- [ ] Organizer can view registrations
- [ ] Organizer can approve/reject
- [ ] Organizer can mark attendance
- [ ] Organizer cannot edit another organizer's opportunity

## UI

- [ ] Works on mobile width
- [ ] Navigation links work
- [ ] Flash messages appear
- [ ] Forms show required validation
- [ ] Tables can scroll horizontally on small screens
