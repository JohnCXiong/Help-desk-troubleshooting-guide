# Windows PC is slow

**Reported symptom:** “Everything on my computer is slow.”  
**Applies to:** Windows 11 desktop or laptop.  
**Goal:** Turn a broad complaint into a measurable symptom and isolate the likely bottleneck.

## Ask first

- Is the whole PC slow or only one application? What action takes longer than usual?
- When did it start? Is it slow after startup, all day, or only on calls/VPN?
- Does anyone else have the same issue? Was an update or application installed recently?
- Is work unsaved? Agree on a good time before any restart.

## Checks, in order

1. **Reproduce one example.** Time or observe a specific action, such as opening File Explorer or starting a known app. Record what “slow” means so you can compare after the fix.
2. **Check Task Manager.** Press **Ctrl+Shift+Esc**. On **Processes**, review CPU, memory, and disk use while the symptom occurs. Record the process name and sustained resource usage. A short spike alone may be normal.
3. **Check free space.** Open **Settings → System → Storage**. Low free storage can affect performance. Review large files with the user; do not delete personal or work files without consent and a retention check.
4. **Check startup load.** In Task Manager's **Startup apps**, note unnecessary user apps that launch at sign-in. Change only apps that are permitted by the organization; do not disable security or management software.
5. **Check updates and restart timing.** Note any pending Windows restart or update. Arrange a restart after the user saves work, following organization policy. Recheck the same action afterward.
6. **Separate local and remote causes.** If local apps are normal but cloud apps are slow, use the network guide and check service status. If one app alone is slow, record its name, version, and exact behavior for app-specific support.

## Verify and document

Repeat the action from step 1 and compare the result. Record the affected app, approximate delay, resource observation, storage state, changes made, and user confirmation. Avoid sharing screenshots that reveal files or personal information.

## Escalate when

- The PC repeatedly freezes, overheats, restarts, or reports disk errors.
- Resource use remains high with no clear cause, or a managed security process is involved.
- A hardware replacement or admin-level change appears necessary.

## Reference

- [Microsoft: Tips to improve PC performance in Windows](https://support.microsoft.com/en-us/windows/experience/performance-optimization/tips-to-improve-pc-performance-in-windows)
