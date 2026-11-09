# Enquiry Desk

A responsive contact form and protected enquiry dashboard.

## Backend
- Supabase project: `dytalupmqacqoyeugtyc`
- Table: `public.enquiries`
- Row Level Security enabled. Anonymous visitors may insert validated enquiries. Only the allowlisted admin email can read/update records.
- Admin sign-in uses Supabase email OTP/magic link.

## Run locally
Serve this folder with any static web server. The Supabase URL and publishable key are configured in `app.js` (publishable keys are intended for browser use; the service-role key is never used here).

## Deployment
Set the Netlify publish directory to `contact-enquiry-portal` when connecting this repository. Enable Supabase email authentication and configure the site's URL plus redirect URL in Supabase Auth settings.

Admin allowlist: `nforngawe1@gmail.com`.
