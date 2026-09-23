# Help Desk Troubleshooting Guide

Five practical, first-line troubleshooting guides for common Windows and Microsoft 365 support requests. This is a **portfolio project**: the scenarios are examples, not records of customer incidents. The guides show how I would gather facts, isolate a cause, verify a fix, and document an escalation.

## Start here

| User report | Guide | Main skill |
| --- | --- | --- |
| “I can't get online.” | [Windows Wi-Fi has no internet](guides/01-wifi-no-internet.md) | Separate a device issue from a network issue |
| “The printer says offline.” | [Printer is offline](guides/02-printer-offline.md) | Check the printer, queue, and connection |
| “My computer is really slow.” | [Windows PC is slow](guides/03-slow-windows-pc.md) | Narrow down the affected resource or app |
| “I can't sign in.” | [Work account is locked or password is forgotten](guides/04-work-account-access.md) | Verify identity and follow an approved recovery path |
| “Outlook won't send my email.” | [Outlook can't send or receive](guides/05-outlook-mail-issue.md) | Separate desktop app problems from mailbox or service problems |

## How to use the guides

1. Confirm the user's exact symptom, error text, start time, and scope.
2. Work through the numbered checks and record the result of each one.
3. Stop before a change that requires organizational approval or could affect other users.
4. Reproduce the original task after the fix, and record the outcome.
5. If unresolved, use the guide's escalation notes and the [ticket template](templates/ticket-note.md).

The guides assume **Windows 11** and, where relevant, a **Microsoft work or school account**. Menu names can vary by version and organization. Follow your employer's procedures for identity checks, resets, security events, and system changes.

## Example ticket note

> **Issue:** User cannot print to the office printer; Windows shows “Offline.”  
> **Scope:** One user; another user can print to the same printer.  
> **Checks:** Printer has power and no panel error. User is on the office network. Two jobs are waiting in the user's print queue.  
> **Action:** With the user's approval, cleared only their pending jobs and retried one test page.  
> **Result:** Test page printed; user confirmed their original document printed.  
> **Follow-up:** No further action needed.

This is a **fictional example**. Do not upload actual tickets, credentials, internal network information, customer data, or unredacted screenshots to a public repository.

## Project structure

```text
help-desk-troubleshooting-guide/
├── README.md
├── guides/
│   ├── 01-wifi-no-internet.md
│   ├── 02-printer-offline.md
│   ├── 03-slow-windows-pc.md
│   ├── 04-work-account-access.md
│   └── 05-outlook-mail-issue.md
└── templates/
    └── ticket-note.md
```

## About this project

I created these guides to practice documenting repeatable support decisions. My focus is on clear questions, low-risk checks first, and a verified outcome. The links at the end of each guide point to the Microsoft documentation used to check the steps. You can adapt the sample workflow to the tools and policies of a specific team.
