# Outlook can't send or receive mail

**Reported symptom:** “My email won't send from Outlook.”  
**Applies to:** New or classic Outlook for Windows with a work account. Some controls differ by version.  
**Goal:** Determine whether the issue is local to Outlook, the network, the mailbox, or a wider service.

## Ask first

- Are messages stuck in Outbox, rejected with an error, or missing from Inbox?
- Does the problem affect all messages or one recipient or attachment?
- Is this new Outlook, classic Outlook, or Outlook on the web? Can colleagues send mail?
- When did it start, and what exact error or bounce message appears?

## Checks, in order

1. **Check connection and scope.** Confirm general web access. If several users are affected, check the organization's Microsoft 365 service notices and escalate through the normal route.
2. **Try Outlook on the web.** Sign in through the organization's official link and send a harmless test message to an account you control, if allowed. If web mail works but desktop Outlook does not, focus on the local app. If both fail, record the error and escalate as a mailbox, account, or service issue.
3. **Inspect the desktop app.** Look for connection or offline indicators. In **classic Outlook**, check **Send/Receive → Work Offline** and the Outbox. New Outlook has different controls; follow its on-screen status and your organization's guidance.
4. **Check the individual message.** If only one message fails, note whether it has a large attachment, an invalid recipient, or a non-delivery report. Do not forward private message content into a public ticket or repository.
5. **Use a supported troubleshooter when applicable.** Microsoft offers troubleshooters for **classic Outlook**; those specific tools do not apply to new Outlook. Avoid removing accounts or rebuilding profiles without approval, especially if locally stored data might be affected.

## Verify and document

Confirm one allowed test message is sent and received, and ask the user to retry the original task. Record Outlook version, web versus desktop outcome, error text, and final confirmation without exposing email addresses or message contents.

## Escalate when

- Outlook on the web also fails, several users are affected, or a service notice applies.
- A mailbox, license, account permission, or delivery rule may need admin review.
- Desktop troubleshooting would require a profile or account change outside first-line scope.

## References

- [Microsoft: Issues sending and receiving email](https://support.microsoft.com/en-us/outlook/issues-sending-and-receiving-email)
- [Microsoft: I can't send or receive messages in Outlook](https://support.microsoft.com/en-us/outlook/i-can-t-send-or-receive-messages-in-outlook)
