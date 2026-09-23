# Printer is offline

**Reported symptom:** “I sent a document, but the office printer shows offline.”  
**Applies to:** Windows 11 with a USB or network printer.  
**Goal:** Find out whether the printer, connection, queue, or app is causing the failure.

## Ask first

- Which printer and location? Is there an error on its display?
- Can anyone else print to it? Can you print from a different app?
- Is the print job stuck, missing, or showing an error? When did printing last work?

## Checks, in order

1. **Check the printer itself.** Confirm it is powered on and awake. Look for paper, jam, toner, and connection warnings. If a shared printer displays an error, record it and contact its owner or support team.
2. **Check scope.** If everybody is affected, treat it as a printer or shared service issue. If one user is affected, check that user's Windows printer setup and queue.
3. **Check the selected printer.** In **Settings → Bluetooth & devices → Printers & scanners**, confirm the intended printer is installed and chosen for the job. For a network printer, check that the laptop is on the required network or VPN.
4. **Inspect the queue.** Open the printer's queue and check for jobs with errors or a paused queue. Ask before cancelling jobs; remove only the user's own stuck jobs when authorized. Avoid clearing a shared queue that contains other people's work.
5. **Run the printer troubleshooter.** On Windows 11, use the printer troubleshooter in **Get Help** and record its finding. Follow your organization's process before changing drivers, ports, or a shared print server.
6. **Test narrowly.** Print a Windows test page or a simple non-sensitive document. If that works but one application fails, record the application and file type for app-specific investigation.

## Verify and document

Ask the user to retry the original document and confirm it comes out at the correct printer. Record the printer's generic location, scope, queue state, troubleshooting result, and final test. Keep document contents and printer addresses out of public notes.

## Escalate when

- Several users cannot print, the printer panel reports hardware trouble, or the shared queue is affected.
- A driver, server, permission, or network change is needed.
- The test page fails after the basic checks.

## Reference

- [Microsoft: Fix printer connection and printing problems in Windows](https://support.microsoft.com/en-us/windows/hardware/printer/fix-printer-connection-and-printing-problems-in-windows)
