# ebdconstructionllc.com

Plain HTML site hosted on Netlify from GitHub. Any change pushed to GitHub goes live automatically.

## Leads
The free-consultation form (bottom of every page) uses Netlify Forms.
- In Netlify: Forms > Enable form detection (one time), then redeploy.
- Forms > consultation > Form notifications > add an email notification so each lead is emailed to you.

## Old domain
`_redirects` sends every ebdproperties.com address (including old pages like /quotes.html) to ebdconstructionllc.com.
Add ebdproperties.com as a domain alias in Netlify and point its DNS at Netlify for this to work.

## Photos
All photos in /img were resized and had location data (GPS) removed.
MLS listing photos were left out. Add them only with the listing photographer's permission.
