# AAJ Express Corporate Login

Responsive log-in page recreated from the "AAJ Corporate Log-In" design (`index.html` + `assets/`).

## Before launch
Edit the `CONFIG` object at the top of the script in `index.html`:
- `loginEndpoint`: POST endpoint taking `{ email, password }` (blank = form validates but no sign-in is attempted)
- `redirectAfterLogin`, `registerUrl`, `forgotPasswordUrl`

The form validates email format and a required password; it contains no authentication logic of its own.
