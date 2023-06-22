## Common Functions or Views
￼
- Add user function
- Delete user function
- start project / campaign / etc function
- change account info (pass, CC, etc) function
- customer analytics view
- payment processing view
- any view with PII

## ￼Insecure direct object references

IDORs are common place in bounties, and hard to catch with scanners.

Find *any and all* UIDs
- increment
- decrement
- negative values
- Attempt to perform sensitive functions substituting another UID
  - change password
  - forgot password
  - admin only functions

Common Functions , Views, or Files:
- Everything from the CSRF Table, trying cross account attacks
- Sub: UIDs, user hashes, or emails
- Images that are non-public
-

## Business Logic Flaws
Logic flaws that are tricky, mostly manual:
- substituting hashed parameters
- step manipulation
- use negatives in quantities
- authentication bypass
- application level DoS
- Timing attacks
