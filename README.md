# Lift Tire Solutions Website v5

This version connects both website quote forms to the Cloudflare Worker:
https://lift-tire-quote-handler.bkpoovey.workers.dev/

What changed:
- Existing Quote form submits live contact data and an uploaded quote file
- New Tire Quote form submits live equipment/tire data and optional photos
- Added required contact fields
- Added success/error messages without leaving the website
- Files remain private in the lift-tire-quotes R2 bucket

Before public launch:
- Test both forms end-to-end
- Add Turnstile spam protection
- Add email notifications to sales@lifttiresolutions.com
