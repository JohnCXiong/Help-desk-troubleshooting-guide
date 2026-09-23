# Work account is locked or password is forgotten

**Reported symptom:** “I can't sign in to my work account.”  
**Applies to:** Microsoft work or school accounts; exact recovery options depend on organization policy.  
**Goal:** Restore access through an approved path without weakening account security.

## Ask first

- Which sign-in fails: Windows, email, VPN, or all work services?
- What is the exact error? When did the last successful sign-in occur?
- Was the password recently changed? Does the user have access to their registered verification method?
- Is the user reporting an unexpected prompt, lost authentication device, or suspected compromise? Follow the security escalation path if so.

## Checks, in order

1. **Confirm the account and scope.** Verify the user's identity using the organization's approved procedure before discussing account details or performing any reset. Do not request their password or a one-time code.
2. **Check the sign-in context.** Confirm they are using the correct work account and official sign-in page. Capture the exact error text without including credentials or recovery codes.
3. **Use approved self-service recovery if available.** Direct the user to the organization's official password reset route. Microsoft's work or school account reset can use registered security information if the organization has enabled it; otherwise the user may be directed to an administrator.
4. **Do not bypass a lockout.** Follow organizational guidance for lockout duration, identity verification, and any authorized admin action. Repeated guesses can prolong an issue; a suspicious lockout may need security review.
5. **Retest the original service.** After the authorized recovery or unlock, have the user sign in themselves. If one app still fails, check whether it needs a fresh sign-in; do not ask them to reveal the new password.

## Verify and document

Record the affected service, exact error, identity verification **method completed** (never the answers), approved route used, and whether the user regained access. Keep recovery details and personal data out of a public portfolio.

## Escalate when

- Self-service reset is unavailable, verification methods are lost, or the account remains blocked.
- There is a suspected compromised account, unexpected MFA prompt, or repeated unexplained lockout.
- The user needs an administrator action or access to a service they were never assigned.

## Reference

- [Microsoft: Reset a work or school account password using security info](https://support.microsoft.com/en-us/accounts-billing/work-school/reset-your-microsoft-work-or-school-account-password-using-security-info)
