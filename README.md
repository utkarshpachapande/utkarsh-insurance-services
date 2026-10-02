# Utkarsh Insurance Services — Netlify-ready

This is a static site. Upload this folder to a Netlify site or deploy it from Git.

## Important form fix
The enquiry form uses Netlify Forms with a normal HTML POST. Do not run it through an Express/Gmail backend.

After deploying, open Netlify → Forms and confirm that the `insurance-enquiry` form is detected. Enable form notifications there if email alerts are required.

The old project contained a Gmail app password. It is not included here. Rotate that old credential if it is still active.
