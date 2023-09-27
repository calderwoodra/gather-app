## Getting Started

A simple privacy-focused, open source app for coordinating meeting up with friends. 

This idea was born out of the idea that coordinating with friends is kinda clunky:
 - when is everyone free (which days, which times)
 - where does everyone want to go (what restaurants, what activities)
 - is everyone going to remember the details (creating calendar events, sending reminders)

Maybe this app is only ever used by myself and my friends, but I figured I'd put it out there and hope for the best.

### Privacy 

All data related to any event it deleted 24 hours after the event happens. 
Event urls are sufficiently obfuscated and only organizers can query PII data.

### Todo

- [ ] Setup Supabase
- [ ] Create event
  - [ ] What (name, url (optional), voting)
  - [ ] When (dates + times)
- [ ] Invite friends
  - [ ] Share link
- [ ] User setup
  - [ ] Name + email (optional)
  - [ ] one-time password (organizer)
  - [ ] Input when available
  - [ ] Input what you prefer
- Settle event
  - [ ] Decide What/When
  - [ ] Create ics email invite (organizer only)
